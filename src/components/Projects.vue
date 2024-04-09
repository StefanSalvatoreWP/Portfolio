<!-- Projects.vue -->
<template>
  <section class="py-8 px-4" id="project">
    <h2
      class="text-2xl md:text-4xl font-extrabold leading-tight tracking-tight mb-4 text-center text-black"
    >
      Some of my Recent Projects
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-8">
      <!-- Card component repeated six times -->
      <div
        v-for="(project, index) in projects"
        :key="index"
        class="overflow-hidden bg-black rounded-lg shadow-lg mx-auto"
      >
        <img
          :src="project.image"
          :alt="project.title"
          class="w-full h-40 md:h-48 object-cover object-center"
        />
        <div class="p-4 md:p-6 bg-black">
          <h3
            class="font-semibold text-lg md:text-xl mb-2 text-yellow-400 cursor-pointer"
          >
            {{ project.title }}
          </h3>
          <p class="text-gray-100 text-sm md:text-base cursor-pointer">
            {{ project.description }}
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          title: 'Auto Clicker',
          description:
            'Auto Clicker is a software tool designed to automate repetitive clicking tasks, such as mouse clicks or keyboard inputs, to increase efficiency and productivity.',
          image: '/images/monitoring.png',
        },
        {
          title: 'Automation/Game',
          description:
            'An automation system designed to enhance gameplay experience by automating repetitive tasks, such as resource gathering, leveling up, or completing quests. This system streamlines gameplay by efficiently managing in-game actions, allowing players to focus on strategic decision-making and enjoying the game world.',
          image: '/images/account.png',
        },
        {
          title: 'Youtube Downloader',
          description:
            'An cmd tool built with Python, providing fast connection and instant download options. Users can easily download within seconds after selection.',
          image: '/images/anime.png',
        },
        {
          title: 'Ethical Phishing site',
          description:
            'A web application built with Node.js, HTML, and CSS, designed to clone social apps for ethical phishing experiments. The server is powered by ngrok for secure tunneling and testing purposes.',
          image: '/images/spotify.jpg',
        },
        {
          title: 'QR MONITOR STUDENTS',
          description:
            "A student monitoring system developed using React.js for the frontend and PHP for the backend, featuring a QR code scanner to monitor student activity. The system is designed to track and analyze students' language usage.",
          image: '/images/milktea.png',
        },
        {
          title: 'C# UNITY GAME',
          description:
            'A game developed using the Unity game engine and assets, showcasing my skills in C# programming and game development.',
          image: '/images/port.png',
        },
      ],
    }
  },
}
</script>

<style scoped>
#project {
  background-color: white; /* Changed background color to violet */
}
/* Add your custom styles here */
</style>
