<template>
  <div>
    <navbar-component></navbar-component>
    <main>
      <div
        class="relative pt-16 pb-32 flex content-center items-center justify-center"
        style="min-height: 50vh;"
      >
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style='background-image: url("https://images.unsplash.com/photo-1457369804613-52c61a468e7d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80");'
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-75 bg-black"
          ></span>
        </div>
        <div class="container relative mx-auto">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-6/10 px-4 ml-auto mr-auto text-center">
              <div class="pr-12">
                <h1 class="text-white font-semibold text-5xl">
                  AsProduktyvus.lt
                </h1>
                <p class="mt-4 text-lg text-gray-300">
                  Patarimai dirbantiems iš namų!
                </p>
              </div>
            </div>
          </div>
        </div>
        <div
          class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
          style="height: 70px; transform: translateZ(0px);"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="https://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-white fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </div>

      <section class="pt-20 pb-48">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center text-center mb-24">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold">Darbas nuotoliniu būdu</h2>
              <p class="text-lg leading-relaxed m-4 text-gray-600">
                Tai gali atrodyti tarsi siekiamybė. Tačiau norint būti efektyviam
                dirbant namuose, pravartu žinoti keletą gudrybių.
              </p>
            </div>
          </div>
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap justify-center text-center mb-24">
              <div class="px-6">
                <div class="pt-6 text-center">
                  <a href="/#/practices">
                  <h5 class="text-xl font-bold"> Darbo rutina</h5>
                  </a>
                  <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                    Kaip sau paruošti darbo vietą,
                    </br>
                    paskirti tikslus ir nustatyti darbo valandas
                  </p>

                </div>
              </div>
               <div class="px-6">
                <div class="pt-6 text-center">
                  <a href="/#/team">
                  <h5 class="text-xl font-bold">Darbas su grupe</h5>
                  </a>
                  <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                    Kaip organizuoti susirinkimus internetu
                    </br>
                   ir dirbti komandoje.
                  </p>
                </div>
              </div>
              <div class="px-6">
                <div class="pt-6 text-center">
                  <a href="/#/tools">
                  <h5 class="text-xl font-bold">Įrankiai</h5>
                  </a>
                  <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                    Programos, įgalinančios nuotolinį darbą.
                  </p>
                </div>
              </div>

            </div>
          </div>
        </div>

      </section>

    </main>
    <footer-component></footer-component>
  </div>
</template>

<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
export default {
  name: "landing-page",
  components: {
    NavbarComponent,
    FooterComponent
  }
}
</script>
