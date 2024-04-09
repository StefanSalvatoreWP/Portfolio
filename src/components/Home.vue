<template>
  <div
    id="apps"
    class="home flex flex-col md:flex-row items-center justify-center bg-white"
  >
    <!-- Content Section -->
    <div class="content text-center md:text-left md:mr-8">
      <div class="intro mb-8">
        <!-- Added margin bottom for spacing -->
        <h1
          id="typed"
          class="text-2xl md:text-4xl font-extrabold leading-tight tracking-tight mb-4 text-black"
        >
          Hi, I'm Franzel Mangubat
        </h1>
        <p class="text-lg text-black font-semibold">
          An IT student pursuing technology because he loves innovation.
        </p>
      </div>
      <div class="flex flex-wrap justify-center md:justify-start space-x-4">
        <!-- Added space between buttons -->
        <!-- Button Container -->
        <router-link to="/projects.vue" class="btn btn-primary">
          Get Started
        </router-link>
        <a
          href="https://www.facebook.com/profile.php?id=100093157675050"
          class="btn btn-facebook"
        >
          <i class="fab fa-facebook-f fa-lg"></i> Facebook
        </a>
        <a href="https://twitter.com" class="btn btn-twitter">
          <i class="fab fa-twitter fa-lg"></i> Twitter
        </a>
        <a href="" class="btn btn-instagram">
          <i class="fab fa-instagram fa-lg"></i> Instagram
        </a>
      </div>
    </div>

    <!-- Image Section -->
    <div class="character max-w-xs md:max-w-md">
      <img src="/images/ako.png" alt="Ako" class="w-full h-auto" />
    </div>
    <router-view></router-view>
  </div>

  <section id="body" class="bg-violet-900 dark:bg-gray-900 antialiased">
    <div class="max-w-screen-xl px-4 py-8 mx-auto lg:px-6 sm:py-16 lg:py-24">
      <div class="max-w-4xl mx-auto text-center">
        <h2
          class="text-3xl font-extrabold leading-tight tracking-tight text-red-700 sm:text-4xl dark:text-white"
        >
          Focus Areas
        </h2>
        <br />
        <div
          class="grid grid-cols-1 mt-12 text-center sm:mt-16 gap-x-20 gap-y-12 sm:grid-cols-2 lg:grid-cols-3"
        >
          <div class="space-y-4">
            <span
              class="bg-gray-100 text-gray-900 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300"
            ></span>
            <h3
              class="text-2xl font-bold leading-tight text-red-700 dark:text-white"
            >
              BACKEND DEVELOPER
            </h3>
            <p class="text-lg font-normal text-gray-500 dark:text-gray-400">
              A backend developer in IT is a professional who specializes in
              developing and maintaining the server-side logic, databases, and
              APIs of web applications. They work on the behind-the-scenes
              functionality of websites and web applications, ensuring they run
              smoothly and efficiently.
            </p>

            <a
              href="#"
              title=""
              class="text-white bg-primary-700 justify-center hover:bg-primary-800 inline-flex items-center focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
              role="button"
            >
              View case study
              <svg
                aria-hidden="true"
                class="w-5 h-5 ml-2 -mr-1"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
          </div>

          <div class="space-y-4">
            <span
              class="bg-gray-100 text-gray-900 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300"
            ></span>
            <h3
              class="text-2xl font-bold leading-tight text-red-700 dark:text-white"
            >
              MACHINE LEARNING ENGINEER
            </h3>
            <p class="text-lg font-normal text-gray-500 dark:text-gray-400">
              A machine learning engineer is a specialist in the field of
              artificial intelligence who focuses on developing algorithms and
              models that allow computers to learn and make predictions or
              decisions based on data. They work on applications such as natural
              language processing, computer vision, and predictive analytics.
            </p>

            <a
              href="#"
              title=""
              class="text-white bg-primary-700 justify-center hover:bg-primary-800 inline-flex items-center focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
              role="button"
            >
              View case study
              <svg
                aria-hidden="true"
                class="w-5 h-5 ml-2 -mr-1"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
          </div>

          <div class="space-y-4">
            <span
              class="bg-gray-100 text-gray-900 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300"
            ></span>
            <h3
              class="text-2xl font-bold leading-tight text-red-700 dark:text-white"
            >
              NETWORK ENGINEER
            </h3>
            <p class="text-lg font-normal text-gray-500 dark:text-gray-400">
              A network engineer in IT is a professional who specializes in
              designing, implementing, and maintaining computer networks. They
              are responsible for ensuring the smooth and efficient operation of
              network infrastructure, including routers, switches, firewalls,
              and other network devices. Network engineers also troubleshoot
              network issues and optimize network performance to meet the
              organization's needs.
            </p>

            <a
              href="#"
              title=""
              class="text-white bg-primary-700 justify-center hover:bg-primary-800 inline-flex items-center focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
              role="button"
            >
              View case study
              <svg
                aria-hidden="true"
                class="w-5 h-5 ml-2 -mr-1"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>

    <!-- Specialties Section -->
    <div class="max-w-screen-xl px-4 py-8 mx-auto lg:px-6 sm:py-16 lg:py-24">
      <div class="max-w-4xl mx-auto text-center">
        <h2
          class="text-3xl font-extrabold leading-tight tracking-tight text-red-700 sm:text-4xl dark:text-white"
        >
          Specialties
        </h2>
        <br />
        <div class="specialties-section">
          <div class="specialties-grid">
            <div class="specialty-item">
              <img src="/images/htmlog.png" alt="HTML" style="width: 90px" />
            </div>
            <!-- Repeat the following div 6 more times for a total of 7 specialties -->
            <div class="specialty-item">
              <img src="/images/csslogo1.png" alt="CSS" style="width: 100px" />
            </div>
            <div class="specialty-item">
              <img
                src="/images/vuelog.png"
                alt="Vue.js"
                style="width: 80px; margin-top: 15px"
              />
            </div>
            <div class="specialty-item">
              <img src="/images/phplog.png" alt="PHP" style="width: 100px" />
            </div>
            <div class="specialty-item">
              <img
                src="/images/reactlog.png"
                alt="React"
                style="width: 100px"
              />
            </div>
            <div class="specialty-item">
              <img src="/images/sasslog.png" alt="Sass" style="width: 100px" />
            </div>
            <div class="specialty-item">
              <img
                src="/images/chatgptlog.png"
                alt="ChatGPT"
                style="width: 100px"
              />
            </div>
            <!-- End of repeated divs -->
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Typed from 'typed.js' // Importing Typed.js library

export default {
  mounted() {
    // Initialize Typed.js
    const options = {
      strings: [
        "Hello there, I'm Franzel!",
        'Welcome to my digital space.',
        "I'm a passionate BSIT student at Cordova Public College.",
        'Join me as I explore the world of technology and innovation.',
      ],
      typeSpeed: 70, // Typing speed in milliseconds
      loop: true, // Loop the typing animation
      attr: 'text', // Set the attribute to type out
      bindInputFocusEvents: true, // Bind focus events to start/stop the animation
      autoInsertCss: true, // Automatically insert CSS for cursor and fade effects
      fadeOut: true, // Fade out typed text
      fadeOutClass: 'typed-fade-out', // CSS class for the fade out animation
      startDelay: 1000, // Delay before typing starts on page load (milliseconds)
      backDelay: 2000, // Time delay before backspacing (milliseconds)
      onComplete: function (self) {
        // Triggered when the typing animation completes
        // Advance to the next sentence after a delay
        setTimeout(function () {
          self.reset() // Reset Typed.js instance
          self.start() // Start typing the next sentence
        }, 2000) // Adjust the delay as needed
      },
    }

    const typed = new Typed('#typed', options)
  },
  methods: {
    handleGetStarted() {
      // Handle the click event of the "Get Started" button
      // Add your logic here
    },
  },
}
</script>

<style>
#apps {
  background-color: white; /* Changed background color to white */
}
#body {
  background-color: white; /* Changed background color to white */
}
#foot {
  background-color: white; /* Changed background color to white */
}

/* Additional styles for footer alignment */
#body {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  min-height: 100vh;
}

.specialties-section {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: auto;
  padding-top: 2rem; /* Adjust spacing as needed */
}

.specialties-grid {
  display: grid;
  grid-template-columns: repeat(7, 1fr); /* Changed to 7 columns */
  gap: 20px; /* Adjust spacing between items */
}

.specialty-item {
  width: 100px; /* Adjust width of items */
}

/* Style for social media icons */
.btn-facebook,
.btn-twitter,
.btn-instagram {
  position: relative;
  overflow: hidden;
}

.btn-facebook::after,
.btn-twitter::after,
.btn-instagram::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent black background */
  z-index: 1;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.btn-facebook:hover::after,
.btn-twitter:hover::after,
.btn-instagram:hover::after {
  opacity: 1;
}

.btn-facebook i,
.btn-twitter i,
.btn-instagram i {
  position: relative;
  z-index: 2;
}

/* Add this to your CSS file */
.btn-facebook {
  color: #3b5998; /* Facebook color */
}

.btn-twitter {
  color: #1da1f2; /* Twitter color */
}

.btn-instagram {
  color: #c13584; /* Instagram color */
}

.intro p {
  max-width: 30rem; /* Limiting the width of the paragraph for better readability */
}

.btn {
  display: inline-flex;
  align-items: center;
  padding: 0.5rem 1rem; /* Adjust button padding */
  border-radius: 0.25rem;
  transition: background-color 0.3s ease;
}

.btn:hover {
  filter: brightness(0.9); /* Add slight brightness on hover */
}

.btn-facebook {
  background-color: #3b5998; /* Facebook color */
  color: white;
}

.btn-twitter {
  background-color: #1da1f2; /* Twitter color */
  color: white;
}

.btn-instagram {
  background-color: #c13584; /* Instagram color */
  color: white;
}
</style>
