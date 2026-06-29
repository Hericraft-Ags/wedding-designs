<template>
  <section class="bg-[var(--color-bg)] text-[var(--color-text-main)]">

    <!-- HERO -->
    <div class="py-20 px-6 text-center max-w-4xl mx-auto">
      <h1 class="text-4xl md:text-5xl font-bold text-[var(--color-blue-dark)] mb-6">
        Demo Metodología
      </h1>

      <p class="text-lg text-[var(--color-text-muted)] leading-relaxed">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui cum culpa sunt assumenda itaque perspiciatis voluptate beatae, veritatis at impedit repellendus voluptatibus tenetur? Eligendi commodi sint, excepturi non animi dolorum.
      </p>
    </div>

    <!-- BLOQUE PRINCIPAL -->
    <div class="max-w-6xl mx-auto px-6 pb-20 grid md:grid-cols-2 gap-12 items-center">
      <div>
        <h2 class="text-2xl font-semibold text-[var(--color-blue)] mb-4">
          Lorem ipsum dolor.
        </h2>

        <p class="text-[var(--color-text-muted)] mb-6 leading-relaxed">
          Sit amet consectetur adipisicing elit. Dolores sint officiis facilis, veniam, praesentium dolorem natus, distinctio vel placeat beatae cupiditate reiciendis? Nulla, nesciunt recusandae soluta at voluptatibus natus rerum.
        </p>

        <ul class="space-y-3">
          <li class="flex items-start gap-3">
            <span class="text-[var(--color-green)]">✔</span>
            <span><strong class="text-[#39aa35]">Lorem, ipsum dolor sit amet consectetur adipisicing elit: </strong>. Quam maiores rerum laudantium impedit. Suscipit, fugiat.</span>
          </li>
          <li class="flex items-start gap-3">
            <span class="text-[var(--color-green)]">✔</span>
            <span><strong class="text-[#39aa35]">Lorem, ipsum dolor sit amet consectetur adipisicing elit: </strong>. Quam maiores rerum laudantium impedit. Suscipit, fugiat.</span>
          </li>
          <li class="flex items-start gap-3">
            <span class="text-[var(--color-green)]">✔</span>
            <span><strong class="text-[#39aa35]">Lorem, ipsum dolor sit amet consectetur adipisicing elit: </strong>. Quam maiores rerum laudantium impedit. Suscipit, fugiat.</span>
          </li>
        </ul>
      </div>

      <!-- IMAGEN -->
      <div>
        <img 
          src="https://st3.depositphotos.com/7865540/13627/i/450/depositphotos_136278008-stock-photo-technology-demo-concept.jpg"
          class="rounded-[var(--border-radius-lg)] shadow-[var(--shadow-soft)] transform transition-all duration-300 ease-out hover:-translate-y-1 hover:scale-[1.03]"
        />
      </div>

    </div>

    <!-- PROCESO -->
    <div class="bg-white py-20 px-6">
      
      <div class="max-w-6xl mx-auto text-center mb-16">
        <h2 class="text-3xl font-bold text-[var(--color-blue-dark)] mb-4">
          Proceso Demo
        </h2>
        <p class="text-[var(--color-text-muted)]">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
      </div>

      <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-10">

        <!-- CARD 1 -->
        <div class="p-8 rounded-[var(--border-radius-lg)]
                    border border-gray-300
                    shadow-[var(--shadow-soft)]
                    hover:shadow-[var(--shadow-hover)]
                    transition-all duration-300 ease-out
                    transform hover:-translate-y-2
                    bg-white text-center">

          <div class="text-4xl mb-4 text-[var(--color-blue)] flex justify-center">
            <i class="fas fa-laptop-code mb-1"></i>
          </div>

          <h3 class="text-xl font-semibold mb-2 text-center">
            Lorem ipsum dolor sit
          </h3>

          <p class="text-[var(--color-text-muted)] text-center">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet quibusdam officia atque maiores.
          </p>
        </div>

        <!-- CARD 2 -->
        <div class="p-8 rounded-[var(--border-radius-lg)]
                    border border-gray-300
                    shadow-[var(--shadow-soft)]
                    hover:shadow-[var(--shadow-hover)]
                    transition-all duration-300 ease-out
                    transform hover:-translate-y-2
                    bg-white text-center">

          <div class="text-4xl mb-4 text-[var(--color-green)] flex justify-center">
            <i class="fas fa-gears mb-1"></i>
          </div>

          <h3 class="text-xl font-semibold mb-2 text-center">
            Lorem ipsum dolor sit
          </h3>

          <p class="text-[var(--color-text-muted)] text-center">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet quibusdam officia atque maiores.
          </p>
        </div>

        <!-- CARD 3 -->
        <div class="p-8 rounded-[var(--border-radius-lg)]
                    border border-gray-300
                    shadow-[var(--shadow-soft)]
                    hover:shadow-[var(--shadow-hover)]
                    transition-all duration-300 ease-out
                    transform hover:-translate-y-2
                    bg-white text-center">

          <div class="text-4xl mb-4 text-[var(--color-blue-dark)] flex justify-center">
            <i class="fas fa-check-circle mb-1"></i>
          </div>

          <h3 class="text-xl font-semibold mb-2 text-center">
            Lorem ipsum dolor sit
          </h3>

          <p class="text-[var(--color-text-muted)] text-center">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet quibusdam officia atque maiores.
          </p>
        </div>

      </div>
    </div>

    <!-- CTA -->
    <div class="py-20 px-6 text-center">
      <h2 class="text-3xl font-bold text-[var(--color-blue-dark)] mb-6">
        ¿Listo para comenzar?
      </h2>

      <p class="text-[var(--color-text-muted)] mb-8">
        Explora nuestros cursos y empieza tu formación hoy mismo.
      </p>

      <router-link 
        to="/courses"
        class="px-8 py-4 bg-teal-700 text-white rounded-[var(--border-radius-lg)] shadow-[var(--shadow-soft)] transform transition-all duration-300 ease-out hover:text-lime-300"
      >
        Ver Cursos
      </router-link>
    </div>

  </section>
</template>

<script setup>
</script>