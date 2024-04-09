<template>
  <div
    class="flex justify-center flex-col md:flex-row items-center min-h-screen bg-white"
  >
    <div class="text-center md:text-left md:mr-8 md:ml-8 mb-8 md:mb-0">
      <h1 class="max-w-screen-sm text-4xl font-extrabold text-black mb-8">
        Hey,
        <span
          class="text-transparent bg-clip-text bg-gradient-to-tr from-orange-500 to-purple-700"
          >Its Franzel Mangubat</span
        >
      </h1>
      <p class="mx-auto mb-16 text-lg font-light text-black max-w-lg">
        Let me take you on a journey through my passion for technology and
        programming. As a Third-year BSIT student at CPC, my fascination with
        computers ignited during my high school days, particularly when I delved
        into the world of programming. Transitioning to senior high school, I
        eagerly pursued TVL specialized in ICT, deepening my understanding of
        the digital realm.
        <br /><br />
        It was during this time that I uncovered the building blocks of the web:
        HTML and CSS. Realizing the immense power behind crafting websites from
        scratch, my curiosity soared. With each line of code, I discovered a new
        layer of creativity and problem-solving.
        <br /><br />
        Currently immersed in the dynamic landscape of Third-year BSIT
        curriculum at CPC, I'm honing my skills in VueJS and Laravel. However,
        my appetite for knowledge knows no bounds. During breaks and free time,
        I eagerly delve into self-learning, with plans to master ReactJS
        independently. The allure of web development beckons me to explore its
        depths further, pushing the boundaries of what's possible in this
        ever-evolving field.
      </p>

      <div class="text-center">
        <button
          class="text-gray-800 inline-block px-8 py-4 mr-4 bg-white rounded-full font-semibold text-lg"
        >
          Contact Me
        </button>
      </div>
    </div>
    <div class="character max-w-xs md:max-w-md ml-auto mr-auto md:mr-0 md:ml-0">
      <img
        src="/images/me.png"
        alt=""
        class="w-full h-auto rounded-full border border-gray-200"
        style="border-radius: 50%"
      />
    </div>
  </div>
</template>

<script>
export default {
  // Component logic
}
</script>

<style scoped>
@media (min-width: 640px) {
  .h-24 {
    height: 6rem; /* Adjust the height for smaller screens */
  }
  .w-24 {
    width: 6rem; /* Adjust the width for smaller screens */
  }
}
</style>
