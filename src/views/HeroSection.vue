<template>
<!-- Hero Section -->
<section class="hero-glow-container text-center py-32 overflow-hidden relative">
  <div class="container relative z-[2]">
    <h1 
      data-aos="fade-down"
      class="text-[3.5rem] mb-6 text-[var(--color-blue-dark)] max-w-[800px] mx-auto leading-[1.2]"
    >
      <span class="text-[var(--color-blue)] [text-shadow:var(--shadow-glow)]">
        [Demo-Empresa]
      </span>
    </h1>
    <p 
      data-aos="fade-up" 
      data-aos-delay="200"
      class="text-[1.25rem] text-[var(--color-text-muted)] max-w-[600px] mx-auto mb-12 leading-[1.8]"
    >
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum optio dolores tenetur expedita sed accusantium. Unde, aliquid expedita. Ipsam laboriosam explicabo saepe deserunt quidem aliquam distinctio dolorem eaque cumque perspiciatis?
    </p>
    <div 
      data-aos="zoom-in" 
      data-aos-delay="400"
      class="flex gap-6 justify-center flex-wrap"
    >
      <router-link 
        to="/courses"
        class="btn-primary px-[2.5rem] py-[1.2rem] text-[1.2rem] bg-[var(--color-blue-dark)]"
      >
        Ver Catálogo
      </router-link>
    </div>
  </div>
</section>

<!-- Sección SCORM -->
<section id="metodologia" class="py-8 bg-transparent">
  <div class="container text-center">
    <h2 
      data-aos="fade-up" 
      class="text-[2.5rem] mb-16"
    >
      [Reproductor Demo]
    </h2>
    <div 
      data-aos="zoom-in-up" 
      data-aos-delay="200" 
      class="monitor-mockup mb-20"
    >
      <div class="monitor-screen relative overflow-hidden rounded-[var(--border-radius-lg)]">

        <iframe class="w-full h-full" src="https://www.youtube.com/embed/Pdi1DSqBZ6Q?si=afw-iQWv4jFoTTxm"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen></iframe>

      </div>
    </div>

    <!-- GRID -->
    <div class="grid grid-cols-[repeat(auto-fit,minmax(300px,1fr))] gap-10 pt-8 mt-24">

      <!-- CARD 1 -->
      <div 
        data-aos="fade-right" 
        data-aos-delay="300" 
        class="card-glass p-10 rounded-[var(--border-radius-lg)]
              transform transition-all duration-300 ease-out
              hover:-translate-y-2 hover:shadow-[var(--shadow-hover)]"
      >
        <div class="text-[3.5rem] text-[var(--color-blue)] mb-6 [filter:drop-shadow(0_4px_6px_rgba(44,110,158,0.3))]">
          <i class="fas fa-cog"></i>
        </div>

        <h3 class="text-[1.5rem]">
          Tarjeta Demo
        </h3>

        <p class="text-[var(--color-text-muted)] mt-4">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aspernatur quis quisquam delectus, ducimus vel atque enim quasi assumenda ipsum doloribus a error asperiores officia labore earum qui consectetur. Libero, ullam.
        </p>
      </div>

      <!-- CARD 2 -->
      <div 
        data-aos="fade-left" 
        data-aos-delay="700" 
        class="card-glass p-10 rounded-[var(--border-radius-lg)]
              transform transition-all duration-300 ease-out
              hover:-translate-y-2 hover:shadow-[var(--shadow-hover)]"
      >
        <div class="text-[3.5rem] text-[var(--color-green)] mb-6 [filter:drop-shadow(0_4px_6px_rgba(164,198,57,0.3))]">
          <i class="fas fa-cog"></i>
        </div>

        <h3 class="text-[1.5rem]">
          Tarjeta Demo
        </h3>

        <p class="text-[var(--color-text-muted)] mt-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit possimus doloribus similique ad, rem numquam deleniti praesentium ex. Facilis dignissimos quisquam quibusdam consequuntur! Eveniet repellat dolore dolor dolorem ipsam dolores!
        </p>
      </div>
    </div>
    
  </div>
</section>

<!-- Ruta del Alumno (Stepper) -->
<section class="py-12 bg-transparent">
  <div class="container">
    
    <h2 
      data-aos="fade-down" 
      class="text-center text-[2.5rem] mb-10"
    >
      Path Demo
    </h2>

    <h3 class="text-[1.4rem] text-[var(--color-text-muted)] text-center mb-16">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam quod odio id tempora voluptate iure animi sapiente qui quae voluptas omnis nulla dolor saepe odit molestiae, praesentium voluptatum sed voluptatem.
    </h3>
    
    <div class="flex flex-col gap-10 max-w-[800px] mx-auto pl-[10px]">
      
      <!-- Paso 1 -->
      <div 
        data-aos="fade-up" 
        data-aos-delay="100" 
        class="roadmap-step flex gap-8 relative"
      >
        <div class="roadmap-connector"></div>

        <div class="w-16 h-16 rounded-full bg-[var(--color-blue)] text-white flex items-center justify-center text-[1.7rem] font-bold shrink-0 relative z-[2] shadow-[0_0_15px_rgba(44,110,158,0.4)]">
          1
        </div>

        <div class="card-glass p-8 rounded-[var(--border-radius-lg)] flex-grow transform transition-all duration-300 ease-out hover:translate-x-5">
          <div class="flex items-center gap-3">

            <img 
              src="https://cdn-icons-png.flaticon.com/512/5110/5110577.png" 
              alt="Icono de laptop con un libro"
              class="w-20 h-auto object-contain"
            >

            <h3 class="text-[1.4rem] text-[#021980] mt-5">
              Step 1
            </h3>

          </div>

          <p class="text-[var(--color-text-muted)] mt-2 text-[1.1rem]">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Error sequi neque facilis, ullam aut quia assumenda illo nulla, hic iure, necessitatibus modi dolores cum quisquam tempora fugit quas. Quasi, officia!
          </p>
        </div>
      </div>
      
      <!-- Paso 2 -->
      <div 
        data-aos="fade-up" 
        data-aos-delay="200" 
        class="roadmap-step flex gap-8 relative"
      >
        <div class="roadmap-connector"></div>

        <div class="w-16 h-16 rounded-full bg-[var(--color-blue)] text-white flex items-center justify-center text-[1.7rem] font-bold shrink-0 relative z-[2] shadow-[0_0_15px_rgba(44,110,158,0.4)]">
          2
        </div>

        <div class="card-glass p-8 rounded-[var(--border-radius-lg)] flex-grow transform transition-all duration-300 ease-out hover:translate-x-5">
          <div class="flex items-center gap-3">

            <img 
              src="https://cdn-icons-png.flaticon.com/512/5110/5110577.png" 
              alt="Icono de examen siendo revisado"
              class="w-20 h-auto object-contain"
            >

            <h3 class="text-[1.4rem] text-[#021980] mt-5">
              Step 2
            </h3>

          </div>

          <p class="text-[var(--color-text-muted)] mt-2 text-[1.1rem]">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Error sequi neque facilis, ullam aut quia assumenda illo nulla, hic iure, necessitatibus modi dolores cum quisquam tempora fugit quas. Quasi, officia!
          </p>
        </div>
      </div>
      
      <!-- Paso 3 -->
      <div 
        data-aos="fade-up" 
        data-aos-delay="300" 
        class="roadmap-step flex gap-8 relative"
      >
        <div class="w-16 h-16 rounded-full bg-[var(--color-green)] text-white flex items-center justify-center text-[1.7rem] font-bold shrink-0 relative z-[2] shadow-[var(--shadow-glow)]">
          <i class="fas fa-cog"></i>
        </div>

        <div class="card-glass p-8 rounded-[var(--border-radius-lg)] flex-grow border-2 border-[var(--color-green)] transform transition-all duration-300 ease-out hover:translate-x-5">
          <div class="flex items-center gap-3">

            <img 
              src="https://cdn-icons-png.flaticon.com/512/5110/5110577.png" 
              alt="Simulador"
              class="w-20 h-auto object-contain"
            >

            <h3 class="text-[1.4rem] text-[var(--color-green-dark)] mt-5">
              Step 3
            </h3>

          </div>

          <p class="text-[var(--color-text-muted)] mt-2 text-[1.1rem]">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Error sequi neque facilis, ullam aut quia assumenda illo nulla, hic iure, necessitatibus modi dolores cum quisquam tempora fugit quas. Quasi, officia!
          </p>
        </div>
      </div>
      
    </div>
  </div>
</section>

<!-- Sección Catálogo -->
<section id="cursos" class="py-12 bg-transparent">
  <div class="container">   
    <h2 
      data-aos="fade-down" 
      class="text-center text-[2.5rem] mb-16"
    >
      Catálogo de Cursos Destacados
    </h2>    
    <div class="grid grid-cols-[repeat(auto-fill,minmax(320px,1fr))] gap-8 max-w-[1000px] mx-auto">      
      <CourseCard
        badge="Badge de curso"
        title="Curso Demo"
        includes="Simulador interactivo incluido"
        image="/images/"
        link="/test-course"
      />
    </div>
  </div>
</section>
</template>

<script setup>
import CourseCard from '../components/CourseCard.vue'
</script>