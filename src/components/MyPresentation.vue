<template>
  <div class="py-16 bg-white-50">
    <div class="container m-auto px-6 text-gray-600 md:px-12 xl:px-6">
      <div class="space-y-6 md:space-y-0 md:flex md:gap-6 lg:items-center lg:gap-12">
        <div class="md:5/12 lg:w-5/12">
          <img src="../assets/Moi.png" alt="Moi" loading="lazy" width="" height="">
        </div>
        <div class="md:7/12 lg:w-6/12">
          <h2 class="text-2xl text-purple-900 font-bold md:text-4xl">Qui suis-je ?</h2>
          <p class="mt-6 text-gray-600">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eum omnis voluptatem accusantium nemo perspiciatis delectus atque autem! Voluptatum tenetur beatae unde aperiam, repellat expedita consequatur! Officiis id consequatur atque doloremque!</p>
          <p class="mt-4 text-gray-600"> Nobis minus voluptati pariatur dignissimos libero quaerat iure expedita at? Asperiores nemo possimus nesciunt dicta veniam aspernatur quam mollitia.</p>
          <p><br></p>
          <div class="grid grid-cols-3 space-x-4 md:space-x-6 md:flex">
            <a aria-label="Github" href="https://github.com/KevinJ-Dev" class="p-4 border border-gray-200 rounded-md hover:border-red-600 hover:shadow-lg">
              <div class="flex justify-center space-x-4">
                <img class="w-6" src="../assets/github.png" alt="Github" loading="lazy" width="128" height="128">
                <span class="hidden font-medium md:block">Github</span>
              </div>
            </a>
            <a aria-label="Linkedin" href="https://www.linkedin.com/in/k%C3%A9vin-jourdain-211243227/" class="p-4 border border-gray-200 rounded-md hover:border-red-600 hover:shadow-lg">
              <div class="flex justify-center space-x-4">
                <img class="w-6" src="../assets/linkedin.png" alt="Linkedin" loading="lazy" width="128" height="128">
                <span class="hidden font-medium md:block">Linkedin</span>
              </div>
            </a>
            <a aria-label="Mail" href="mailto:kevin.jourdain@epitech.eu" class="p-4 border border-gray-200 rounded-md hover:border-red-600 hover:shadow-lg">
              <div class="flex justify-center space-x-4">
                <img class="w-6" src="../assets/Mail.png" alt="Mail" loading="lazy" width="128" height="128">
                <span class="hidden font-medium md:block">Mail</span>
              </div>
            </a>
<!--            <a aria-label="Phone" href="#" class="p-4 border border-gray-200 rounded-md hover:border-red-600 hover:shadow-lg">-->
<!--              <div class="flex justify-center space-x-4">-->
<!--                <img class="w-6" src="../assets/Phone.png" alt="Téléphone" loading="lazy" width="128" height="128">-->
<!--                <span class="hidden font-medium md:block">Téléphone</span>-->
<!--              </div>-->
<!--            </a>-->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyPresentation",
  components: {}
}
</script>

<style scoped>

</style>