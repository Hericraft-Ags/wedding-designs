<template>
  <section class="min-h-screen bg-[var(--color-bg)] py-20 px-6">
    
    <!-- HEADER -->
    <div class="text-center max-w-3xl mx-auto mb-16">
      <h1 class="text-4xl md:text-5xl font-bold text-[var(--color-blue-dark)] mb-6">
        Cursos Disponibles
      </h1>

      <p class="text-[var(--color-text-muted)] text-lg leading-relaxed">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit.
      </p>
    </div>

    <!-- GRID DE CURSOS -->
    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
      
      <CourseCard
        v-for="course in courses"
        :key="course.title"
        v-bind="course"
      />

    </div>

  </section>
</template>

<script setup>
import CourseCard from '../components/CourseCard.vue'

const courses = [
  {
    badge: "Badge de curso",
    title: "Curso Demo",
    includes: "Simulador interactivo + prácticas reales",
    image: "/images/",
    link: "/test-course"
  },
  {
    badge: "Badge de curso",
    title: "Curso Demo",
    includes: "Simulador interactivo + prácticas reales",
    image: "/images/",
    link: "/test-course"
  },
  {
    badge: "Badge de curso",
    title: "Curso Demo",
    includes: "Simulador interactivo + prácticas reales",
    image: "/images/",
    link: "/test-course"
  },
  {
    badge: "Badge de curso",
    title: "Curso Demo",
    includes: "Simulador interactivo + prácticas reales",
    image: "/images/",
    link: "/test-course"
  },
  {
    badge: "Badge de curso",
    title: "Curso Demo",
    includes: "Simulador interactivo + prácticas reales",
    image: "/images/",
    link: "/test-course"
  },
  {
    badge: "Badge de curso",
    title: "Curso Demo",
    includes: "Simulador interactivo + prácticas reales",
    image: "/images/",
    link: "/test-course"
  }
]
</script>