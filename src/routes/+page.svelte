<script lang="ts">
  import Banner from "$lib/elena.svelte";
</script>

<!-- HERO -->
<section id="home" class="flex items-center justify-center">
  <div class="padding grid items-center md:grid-cols-2">
    <div>
      <span class="text-gray-600">📍 Toronto, Canada</span>
      <h1 class="pt-6">
        Advocating progress through technology and innovation
      </h1>
      <body>
        <p>
          Hi, I'm Elena. Currently working as a Product Manager in the public
          sector across North America.
        </p>
      </body>
      <div class="mt-6 flex items-center">
        <a href="/resume.pdf" class="hover:italic">Download my resume 〉</a>
      </div>
      <!-- <div class="mt-4 flex items-center">
        <a href="/resume.pdf" class="hover:italic">Get to know me 〉</a>
      </div> -->
    </div>
    <div class="hidden justify-center px-14 pt-6 md:flex">
      <Banner />
    </div>
  </div>
</section>

<!-- WORKS / PROJECTS -->
<section class="padding" id="works">
  <div class="pt-12">
    <h2>Works & Projects</h2>
    <div
      class="grid grid-cols-1 gap-4 pb-12 pt-2 sm:grid-cols-2 md:grid-cols-3"
    >
      <a href="/works/duanyam" class="card">
        <div class="card-content">
          <div class="card-meta">
            <span class="card-tag">Design</span>
            <span class="card-tag">2018</span>
          </div>
        </div>

        <h3 class="card-title">Du'Anyam: Design Showcase</h3>
        <p class="card-desc">
          Social enterprise design system exploring ethical production and
          craft.
        </p>
      </a>

      <a href="/works/siklus" class="card">
        <div class="card-content">
          <div class="card-meta">
            <span class="card-tag">Product Management</span>
            <span class="card-tag">2021</span>
          </div>
        </div>

        <h3 class="card-title">Siklus Refill: Showcase</h3>
        <p class="card-desc">
          Social enterprise design system exploring ethical production and
          craft.
        </p>
      </a>

      <a href="/works/canadagoose" class="card">
        <div class="card-content">
          <div class="card-meta">
            <span class="card-tag">Case Study</span>
            <span class="card-tag">2022</span>
          </div>
        </div>

        <h3 class="card-title">Canada Goose: Case Study</h3>
        <p class="card-desc">
          Social enterprise design system exploring ethical production and
          craft.
        </p>
      </a>

    </div>
  </div>
</section>
