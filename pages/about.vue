<template>
  <div
    class="theme-switch-wrapper xl:p-40 lg:pl-36 md:pl-32 sm:pl-24 pl-14 h-screen w-screen overflow-scroll"
    data-theme="light"
  >
    <!-- Page Title -->
    <section class="g-section h-screen">
      <!-- <svg
        class=""
        width="100%"
        height="100%"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path fill="white" data-theme="light">
          <animate
            repeatCount="indefinite"
            fill="freeze"
            attributeName="d"
            dur="6.66s"
            values="M0 25.9086C277 84.5821 433 65.736 720 25.9086C934.818 -3.9019 1214.06 -5.23669 1442 8.06597C2079 45.2421 2208 63.5007 2560 25.9088V171.91L0 171.91V25.9086Z;
        
                      M0 87.1596C316 87.1597 444 160 884 52.0001C1324 -55.9999 1320.29 34.966 1538 71.251C1814 117.251 2156 189.252 2560 87.1597V233.161L0 233.161V87.1596Z;
        
                      M0 53.6584C158 11.0001 213 0 363 0C513 0 855.555 115.001 1154 115.001C1440 115.001 1626 -38.0004 2560 53.6585V199.66L0 199.66V53.6584Z;
        
                      M0 25.9086C277 84.5821 433 65.736 720 25.9086C934.818 -3.9019 1214.06 -5.23669 1442 8.06597C2079 45.2421 2208 63.5007 2560 25.9088V171.91L0 171.91V25.9086Z;
                     "
          ></animate>
        </path>
      </svg> -->

      <figure class="">
        <img class="" :src="images.imageTwo" alt="" />
      </figure>

      <!-- <svg
        class=""
        width="100%"
        height="100%"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path fill="white" data-theme="light">
          <animate
            repeatCount="indefinite"
            fill="freeze"
            attributeName="d"
            dur="3.33s"
            values="M0 25.9086C277 84.5821 433 65.736 720 25.9086C934.818 -3.9019 1214.06 -5.23669 1442 8.06597C2079 45.2421 2208 63.5007 2560 25.9088V171.91L0 171.91V25.9086Z;
        
                      M0 87.1596C316 87.1597 444 160 884 52.0001C1324 -55.9999 1320.29 34.966 1538 71.251C1814 117.251 2156 189.252 2560 87.1597V233.161L0 233.161V87.1596Z;
        
                      M0 53.6584C158 11.0001 213 0 363 0C513 0 855.555 115.001 1154 115.001C1440 115.001 1626 -38.0004 2560 53.6585V199.66L0 199.66V53.6584Z;
        
                      M0 25.9086C277 84.5821 433 65.736 720 25.9086C934.818 -3.9019 1214.06 -5.23669 1442 8.06597C2079 45.2421 2208 63.5007 2560 25.9088V171.91L0 171.91V25.9086Z;
                     "
          ></animate>
        </path>
      </svg> -->
    </section>

    <!-- About Intro -->
    <section class="g-section w-full h-full flex-wrap pl-12 pr-12">
      <div class="flex flex-row justify-center items-center md:flex-row">
        <div class="basis-2/3 max-w-2/3">
          <h3
            class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl xl:text-6xl font-bold leading-none pb-2 md:pb-6"
          >
            Hello, I'm Matthew. I design and code for the web.
          </h3>

          <div class="custom-link form-group">
            <button id="submit" class="rounded-lg" type="submit" name="submit">
              <strong class="rounded-lg">
                <a
                  href="https://www.linkedin.com/in/matthew-ricklefs-13284a1b9/"
                  ><p>Let's Connect</p></a
                >

                <b></b>
                <i></i>
              </strong>
            </button>
          </div>

          <p class="text-sm sm:text-lg pt-3">
            I'm a Full Stack Developer with a passion for developing beautiful
            applications. I have 2 years of experience designing for web but am
            most passionate about solving real-world problems utilizing
            technology at the intersection of design and code.
          </p>
        </div>

        <div class="flex items-center justify-center basis-1/3">
          <img
            class="bg-emerald-50 shadow-md object-contain rounded-full pb-32 mb-12"
            :src="images.imageSix"
            alt="picture of Matthew"
          />
        </div>
      </div>
    </section>

    <!-- Skills ----------------------------- -->
    <section class="g-section p-12">
      <div class="">
        <div class="">
          <h6
            class="flex font-thin tracking-normal uppercase text-lg sm:text-xl"
          >
            SKILLS
          </h6>

          <p class="tracking-wide mb-10 font-light text-sm sm:text-lg">
            I like learning new things. Here are a few topics I am proficient
            with.
          </p>
        </div>

        <div
          class="flex flex-col sm:flex-col md:flex-row lg:flex-row xl:flex-row items-center justify-between w-full h-full"
        >
          <figure
            class="p-3 flex flex-col items-start justify-between rounded-2xl m-3 flex flex-row w-full h-full hover:bg-emerald-100 transition-all delay-75"
          >
            <img
              class="h-15 w-12 object-contain relative basis-1/4 self-center"
              :src="icons.ui"
            />
            <figcaption class="self-center">
              <span class="text-sm font-light mb-3">01</span>
              <h4 class="text-md font-thin">UI DESIGN</h4>
            </figcaption>
          </figure>

          <figure
            class="p-3 flex flex-col items-start justify-between rounded-2xl m-3 flex flex-row w-full h-full hover:bg-emerald-200 transition-all delay-75"
          >
            <img
              class="h-15 w-12 object-contain basis-1/4 self-center"
              :src="icons.front"
            />
            <figcaption class="self-center">
              <span class="text-sm font-light">02</span>
              <h4 class="text-md font-thin">FRONT END</h4>
            </figcaption>
          </figure>

          <figure
            class="p-3 flex flex-col items-start justify-between rounded-2xl m-3 flex flex-row w-full h-full hover:bg-emerald-300 transition-all delay-75"
          >
            <img
              class="h-15 w-12 object-contain basis-1/4 self-center"
              :src="icons.back"
            />
            <figcaption class="self-center">
              <span class="text-sm font-light">03</span>
              <h4 class="text-md font-thin">BACK END</h4>
            </figcaption>
          </figure>

          <figure
            class="p-3 flex flex-col items-start justify-between rounded-2xl m-3 flex flex-row w-full h-full hover:bg-emerald-400 transition-all delay-75"
          >
            <img
              class="h-15 w-12 object-contain relative basis-1/4 self-center"
              :src="icons.ux"
            />
            <figcaption class="self-center">
              <span class="text-sm font-light">04</span>
              <h4 class="text-md font-thin">UX DESIGN</h4>
            </figcaption>
          </figure>
        </div>
      </div>
    </section>

    <!-- Technologies ------------------- -->
    <section class="g-section w-full h-full flex flex-col p-12">
      <div class="flex flex-col flex-wrap text-left w-full mb-20">
        <h6 class="flex font-thin tracking-normal uppercase text-lg sm:text-xl">
          TECHNOLOGIES
        </h6>

        <p class="tracking-wide mb-10 font-light text-sm sm:text-lg">
          Some tech I'm currently working with.
        </p>
      </div>

      <ul class="w-full h-full flex flex-row items-center space-between">
        <li
          v-for="(icon, index) in logos"
          :key="icon.key"
          :data-index="index"
          class="list-none p-0 m-0"
        >
          <img class="h-20 w-20" :src="icon" />
        </li>
      </ul>

      <!-- <div class="w-full h-full flex flex-col">
        <ul class="flex flex-row items-center justify-between">
          <li class="h-40 w-40 p-1" data-wow-delay="0.50s">
            <figure class="flex justify-center w-full rounded-full">
              <img class="h-20 w-20" :src="icon.vue" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="0.60s">
            <figure class="flex justify-center w-full rounded-full">
              <img class="h-20 w-20" :src="icon.react" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="0.70s">
            <figure class="flex justify-center w-full rounded-full">
              <img class="h-20 w-20" :src="icon.mongo" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="0.80s">
            <figure class="flex justify-center w-full rounded-full">
              <img class="h-20 w-20" :src="icon.express" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="0.90s">
            <figure class="flex justify-center w-full rounded-full">
              <img class="h-20 w-20" :src="icon.node" />
            </figure>
          </li>
        </ul>

        <ul class="flex flex-row items-center justify-between">
          <li class="h-40 w-40 p-1" data-wow-delay="1s">
            <figure class="flex justify-center w-full rounded-full">
              <img class="h-20 w-20" :src="icon.nuxt" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="1.1s">
            <figure
              class="flex justify-center list-none h-full w-full rounded-full"
            >
              <img class="h-20 w-20" :src="icon.next" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="1.2s">
            <figure
              class="flex justify-center list-none h-full w-full rounded-full"
            >
              <img class="h-20 w-20" :src="images.imageFour" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="1.3s">
            <figure
              class="flex justify-center list-none h-full w-full rounded-full"
            >
              <img class="h-20 w-20" :src="icon.graphQl" />
            </figure>
          </li>

          <li class="h-40 w-40 p-1" data-wow-delay="1.4s">
            <figure
              class="flex justify-center list-none h-full w-full rounded-full"
            >
              <img class="h-20 w-20" :src="icon.aws" />
            </figure>
          </li>
        </ul>
      </div> -->
    </section>

    <!-- Explore Ideas -->
    <section class="g-section p-12">
      <div class="">
        <h2 class="flex font-thin tracking-normal uppercase text-lg sm:text-xl">
          EXPLORE IDEAS
        </h2>

        <p class="tracking-wide mb-10 font-light text-sm sm:text-lg">
          Need a developer for your next project? Let's work together.
        </p>

        <div class="custom-link form-group">
          <button id="submit" class="rounded-lg" type="submit" name="submit">
            <strong class="rounded-lg">
              <router-link to="/contact"><p>Contact Me</p></router-link>

              <b></b>
              <i></i>
            </strong>
          </button>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import { gsap } from 'gsap'
// import ScrollTrigger from 'gsap/ScrollTrigger'

export default {
  name: 'About',
  transition: {
    appear: true,
    css: false,
    beforeEnter(el) {
      gsap.set(el.children, {
        scale: 0.6,
        opacity: 0,
      })
    },
    enter(el, done) {
      gsap.to(el.children, {
        scale: 1,
        opacity: 1,
        duration: 0.3,
        ease: 'bounce.inOut',
        stagger: 0.3,
        onComplete: done,
      })
    },
    afterEnter(el) {},
  },
  data() {
    return {
      images: {
        imageOne: require('../assets/images/matty6.jpeg'),
        imageTwo: require('../assets/images/code.jpeg'),
        imageThree: require('../assets/logo.png'),
        imageFour: require('../assets/images/coder-zen.png'),
        imageFive: require('../assets/images/matty-2.png'),
        imageSix: require('../assets/images/matty3.png'),
      },
      logos: {
        express: require('../assets/images/express-logo.png'),
        aws: require('../assets/images/aws-logo.png'),
        graphQl: require('../assets/images/graphql-logo.svg'),
        mongo: require('../assets/images/mongodb-logo.svg'),
        nuxt: require('../assets/images/nuxt.png'),
        node: require('../assets/images/node-logo.svg'),
        next: require('../assets/images/next-logo.svg'),
        redux: require('../assets/images/redux-logo.svg'),
        react: require('../assets/images/react-logo.svg'),
        vue: require('../assets/logo.png'),
      },
      icons: {
        ui: require('../assets/images/icon01.svg'),
        front: require('../assets/images/icon02.svg'),
        back: require('../assets/images/icon03.svg'),
        ux: require('../assets/images/icon04.svg'),
      },
    }
  },
  mounted: () => {
    // this.startAnimations()
  },
  methods: {
    toggleSwitch() {
      const toggleSwitch = document.querySelector(
        '.theme-switch input[type="checkbox"]'
      )

      function switchTheme(e) {
        if (e.target.checked) {
          document.documentElement.setAttribute('data-theme', 'dark')
        } else {
          document.documentElement.setAttribute('data-theme', 'light')
        }
      }

      toggleSwitch.addEventListener('change', switchTheme, false)
    },
    startAnimations: () => {
      // const tl = new Timeline({ onUpdate: updatePercentage })
      // const scene = this.$scrollmagic
      //   .scene({
      //     triggerElement: '.theme-switch-wrapper',
      //     triggerHook: 0,
      //     duration: 1,
      //   })
      //   .setPin('.theme-switch-wrapper')
      //   .setTween(tl)
      // this.$scrollmagic.addScene(scene)
      // const updatePercentage = () => {
      //   tl.progress()
      // }
    },
  },
}
</script>
