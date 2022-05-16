<template>
  <footer class="w-full py-16 bg-gray-100">
    <div class="md:px-12 lg:px-28">
      <div class="container m-auto space-y-6 text-gray-600">
        <img src="../assets/logo.png" alt="logo" class="w-40 m-auto" />
        <ul role="list" class="py-4 flex flex-col gap-4 items-center justify-center sm:flex-row sm:gap-8">
          <li role="listitem"><a href="#presentation" class="hover:text-red-500">Présentation</a></li>
          <li role="listitem"><a href="#experience" class="hover:text-red-500">Expériences</a></li>
          <li role="listitem"><a href="#projet" class="hover:text-red-500">Projets</a></li>
          <li role="listitem"><a href="#contact" class="hover:text-red-500">Contact</a></li>
          <li role="listitem"><a href="/Kevin.Jourdain.pdf" download class="hover:text-red-500">Télécharger CV</a></li>
        </ul>
        <div class="w-max m-auto flex items-center justify-between space-x-4">
          <a aria-label="Github" href="https://github.com/KevinJ-Dev">
            <div>
              <img class="w-6" src="../assets/github.png" alt="Github" width="128" height="128">
            </div>
          </a>

          <a aria-label="Linkedin" href="https://www.linkedin.com/in/k%C3%A9vin-jourdain-211243227/">
            <div>
              <img class="w-6" src="../assets/linkedin.png" alt="Linkedin" width="128" height="128">
            </div>
          </a>

          <a aria-label="Mail" href="mailto:kevin.jourdain@epitech.eu">
            <div>
              <img class="w-6" src="../assets/Mail.png" alt="Mail" width="128" height="128">
            </div>
          </a>
        </div>

        <div class="text-center">
          <span class="text-sm tracking-wide">Copyright © Kévin <span id="year"></span> | Tout droit réserver</span>
        </div>
      </div>
    </div>
  </footer>

</template>

<script>
export default {
  name: "MyFooter"
}
</script>

<style scoped>

</style>