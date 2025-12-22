<script>
  import { redirect } from "@sveltejs/kit";
  import "../app.css";
</script>

<nav
  class="sticky top-0 z-20 w-full border-b bg-white/70 backdrop-blur supports-[backdrop-filter]:bg-white/60"
>
  <div class="padding">
    <!-- desktop (equal-width items across the full bar) -->
    <ul class="hidden w-full justify-end space-x-8 md:flex">
      <li class="mr-auto"><a href="/">Elena</a></li>
      <li><a href="/#works">Work</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </div>
</nav>

<div class="text-base/7">
  <slot />

  <div id="contact">
    <footer class="w-full border-t border-grey-300">
      <div class="padding pt-8 pb-6">
        <ul class="w-full space-x-12 flex">
          <li>
            <h3>Grab coffee with me!</h3>
            </li>
              <li>
                ☕️
              </li>
          <li>
            <a href="mailto:isabelaelenang@gmail.com" class="text-lg">Email</a>
          </li>
          <li>
            <a href="https://www.linkedin.com/in/isabelaelena/" class="text-lg">LinkedIn</a>
          </li>
        </ul>
      </div>
    </footer>
  </div>
</div>

<style>
  nav ul {
    display: flex;
    width: 100%;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  nav ul li {
    flex: 1; /* each list item takes up equal space */
    text-align: right; /* center the link text */
    font-size: 1.5rem;
  }

  nav ul li a {
    display: block;
    width: 100%;
    padding: 1rem 0; /* make the clickable area tall */
  }

  nav ul li:first-child a {
    text-align: left;
  }
</style>
