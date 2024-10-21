<template>
  <main>
    <main>
      <div class="fadeup flex items-center justify-between" style="">
        <img
          alt="mubeena profile picture"
          loading="lazy"
          width="75"
          height="75"
          decoding="async"
          data-nimg="1"
          class="rounded-full border-2 border-geist"
          style="color: transparent"
          srcset="/public/profile-pic.jpg"
          src="/public/profile-pic.jpg"
        />
        <div class="flex items-center gap-2 text-[#EDEDED]">
          <span class="size-2 relative flex">
            <span
              class="size-2 absolute inline-flex animate-ping rounded-full bg-[#00AC3A]"
            ></span
            ><span
              class="relative inline-flex h-[0.5rem] w-[0.8rem] rounded-full bg-[#00CA50]"
            ></span
          ></span>
          <p class="text-lg font-medium">Open to Work</p>
        </div>
      </div>
      <p class="mt-5 text-lg font-medium text-[#EDEDED]">Hi, I'm Al Mubeena</p>
      <p class="mt-2 text-lg text-geist" style="">
        As a
        <span class="text-lg font-bold capitalize text-[#EDEDED]"
          >front-end developer</span
        >, I transform ideas into dynamic, user-friendly interfaces with a focus
        on design and performance. My work merges technical expertise with a
        passion for creating seamless, engaging web experiences.
      </p>
      <div style="opacity: 1; transform: none">
        <main class="mt-8 flex w-full items-center gap-2" style="">
          <a
            class="group flex w-full items-center gap-2 rounded-lg border border-[#2E2E2E] p-2 px-3 text-sm leading-none text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] hover:text-[#FFF]"
            target="_blank"
            href="https://www.linkedin.com/in/al-mubeena-j-2b3605228/"
            style=""
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="18"
              height="18"
              fill="currentColor"
              viewBox="0 0 24 24"
            >
              <title>LinkedIn</title>
              <path
                d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"
              ></path>
            </svg>
            <p class="text-base font-medium">Connect with me</p>
            <svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="18"
              height="18"
              fill="currentColor"
              class="remixicon group-hover:text-white ml-auto text-geist duration-300 ease-out group-hover:rotate-45"
              style=""
            >
              <path
                d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
                style=""
              ></path></svg></a
          ><a
            class="group rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] hover:text-[#fff]"
            target="_blank"
            aria-label="Email"
            href="mailto:mubee.jahir@gmail.com"
            style=""
            ><svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="18"
              height="18"
              fill="currentColor"
              class="remixicon"
            >
              <path
                d="M20 12C20 7.58172 16.4183 4 12 4C7.58172 4 4 7.58172 4 12C4 16.4183 7.58172 20 12 20C13.6418 20 15.1681 19.5054 16.4381 18.6571L17.5476 20.3214C15.9602 21.3818 14.0523 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12V13.5C22 15.433 20.433 17 18.5 17C17.2958 17 16.2336 16.3918 15.6038 15.4659C14.6942 16.4115 13.4158 17 12 17C9.23858 17 7 14.7614 7 12C7 9.23858 9.23858 7 12 7C13.1258 7 14.1647 7.37209 15.0005 8H17V13.5C17 14.3284 17.6716 15 18.5 15C19.3284 15 20 14.3284 20 13.5V12ZM12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15C13.6569 15 15 13.6569 15 12C15 10.3431 13.6569 9 12 9Z"
              ></path></svg></a
          ><a
            class="group rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] hover:text-[#fff]"
            target="_blank"
            aria-label="GitHub"
            href="https://github.com/mubeejahir"
            style=""
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="18"
              height="18"
              fill="currentColor"
              viewBox="0 0 24 24"
              style=""
            >
              <title>GitHub</title>
              <path
                d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
              ></path></svg
          ></a>
        </main>
      </div>
    </main>
    <div style="opacity: 1; transform: none">
      <div class="headline-div" style="">
        <p class="text-base uppercase" style="">projects</p>
        <svg
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
          width="14"
          height="14"
          fill="currentColor"
          class="remixicon"
        >
          <path
            d="M24 12L18.3431 17.6569L16.9289 16.2426L21.1716 12L16.9289 7.75736L18.3431 6.34315L24 12ZM2.82843 12L7.07107 16.2426L5.65685 17.6569L0 12L5.65685 6.34315L7.07107 7.75736L2.82843 12ZM9.78845 21H7.66009L14.2116 3H16.3399L9.78845 21Z"
          ></path>
        </svg>
      </div>
      <main class="project-link group cursor-pointer" style="">
        <div
          class="select-none overflow-hidden rounded-md border border-[#2E2E2E] duration-300 ease-in-out group-hover:border-geist"
          style=""
        >
          <div
            style="position: relative; width: 100%; padding-bottom: 75%"
            data-radix-aspect-ratio-wrapper=""
          >
            <div
              class="flex items-center justify-center bg-[#000000]"
              style="position: absolute; top: 0; right: 0; bottom: 0; left: 0"
            >
              <img
                alt="trello clone Project"
                fetchpriority="high"
                width="450"
                height="500"
                decoding="async"
                data-nimg="1"
                class="scale-110 rounded-md"
                style="color: transparent"
                srcset="/assets/imgs/bello-tracker-app.png"
                src="/assets/imgs/bello-tracker-app.png"
              />
            </div>
          </div>
        </div>
        <section class="project-link-content">
          <div class="space-y-2">
            <p class="text-lg font-medium text-[#EDEDED]">Trello Clone</p>
            <p class="text-pretty text-base text-geist">
              A Trello clone is a task management tool that uses boards, lists,
              and cards for organizing workflows. It supports features like
              drag-and-drop, task prioritization, and user assignments for
              seamless collaboration.
            </p>
          </div>
          <div class="flex items-center justify-between">
            <div
              class="flex select-none items-center justify-start gap-2 text-geist"
            >
              <div class="border-r border-geist pr-2">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="18"
                  height="18"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                  class="hover:text-[#EDEDED]"
                >
                  <title>GitHub</title>
                  <path
                    d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
                  ></path>
                </svg>
              </div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="18"
                height="18"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                <g
                  id="SVGRepo_tracerCarrier"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                ></g>
                <g id="SVGRepo_iconCarrier">
                  <title>Nuxt.js</title>
                  <path
                    d="M10.648,25.734a1.465,1.465,0,0,1-.157-.942H3.847L13.716,7.417l4.159,7.41,1.308-.976L15.076,6.467A1.752,1.752,0,0,0,13.7,5.56a1.531,1.531,0,0,0-1.343.924l-10,17.593a1.729,1.729,0,0,0-.087,1.656,1.526,1.526,0,0,0,1.456.706H12.1a1.523,1.523,0,0,1-1.456-.7Z"
                    style="fill: #a1a1a1"
                  ></path>
                  <path
                    d="M29.636,24.112,21.589,9.823a1.692,1.692,0,0,0-1.351-.907,1.489,1.489,0,0,0-1.308.907l-1.064,1.7v3.3l2.371-4.071,7.951,14.071H25.163a1.377,1.377,0,0,1-.122.837l-.026.052a1.729,1.729,0,0,1-1.456.732h4.734a1.72,1.72,0,0,0,1.456-.732,1.548,1.548,0,0,0-.122-1.6Z"
                    style="fill: #a1a1a1"
                  ></path>
                  <path
                    d="M25.233,25.7l.026-.052.07-.139a1.278,1.278,0,0,0,.061-.7,2.11,2.11,0,0,0-.27-.724l-6.286-10.9-.95-1.656h-.017l-.959,1.648-6.277,10.9a2.18,2.18,0,0,0-.244.715,1.438,1.438,0,0,0,.148.942,1.563,1.563,0,0,0,1.482.7H23.725a1.79,1.79,0,0,0,1.508-.741ZM17.866,14.836,23.62,24.8H12.112Z"
                    style="fill: #a1a1a1"
                  ></path>
                </g>
              </svg>

              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="18"
                height="18"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <title>Tailwind CSS</title>
                <path
                  d="M12.001,4.8c-3.2,0-5.2,1.6-6,4.8c1.2-1.6,2.6-2.2,4.2-1.8c0.913,0.228,1.565,0.89,2.288,1.624 C13.666,10.618,15.027,12,18.001,12c3.2,0,5.2-1.6,6-4.8c-1.2,1.6-2.6,2.2-4.2,1.8c-0.913-0.228-1.565-0.89-2.288-1.624 C16.337,6.182,14.976,4.8,12.001,4.8z M6.001,12c-3.2,0-5.2,1.6-6,4.8c1.2-1.6,2.6-2.2,4.2-1.8c0.913,0.228,1.565,0.89,2.288,1.624 c1.177,1.194,2.538,2.576,5.512,2.576c3.2,0,5.2-1.6,6-4.8c-1.2,1.6-2.6,2.2-4.2,1.8c-0.913-0.228-1.565-0.89-2.288-1.624 C10.337,13.382,8.976,12,6.001,12z"
                ></path>
              </svg>
            </div>
            <a target="_blank" href="https://bello-tracker-app.netlify.app/">
              <svg
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="remixicon text-geist duration-300 ease-out group-hover:rotate-45 group-hover:text-[#FFF]"
              >
                <path
                  d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
                ></path>
              </svg>
            </a>
          </div>
        </section>
      </main>
    </div>

    <div style="opacity: 1; transform: none">
      <div class="headline-div">
        <p class="text-base uppercase">stack</p>
        <svg
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
          width="14"
          height="14"
          fill="currentColor"
          class="remixicon"
        >
          <path
            d="M20.0834 15.1999L21.2855 15.9212C21.5223 16.0633 21.599 16.3704 21.457 16.6072C21.4147 16.6776 21.3559 16.7365 21.2855 16.7787L12.5145 22.0412C12.1979 22.2313 11.8022 22.2313 11.4856 22.0412L2.71463 16.7787C2.47784 16.6366 2.40106 16.3295 2.54313 16.0927C2.58536 16.0223 2.64425 15.9634 2.71463 15.9212L3.91672 15.1999L12.0001 20.0499L20.0834 15.1999ZM20.0834 10.4999L21.2855 11.2212C21.5223 11.3633 21.599 11.6704 21.457 11.9072C21.4147 11.9776 21.3559 12.0365 21.2855 12.0787L12.0001 17.6499L2.71463 12.0787C2.47784 11.9366 2.40106 11.6295 2.54313 11.3927C2.58536 11.3223 2.64425 11.2634 2.71463 11.2212L3.91672 10.4999L12.0001 15.3499L20.0834 10.4999ZM12.5145 1.30864L21.2855 6.5712C21.5223 6.71327 21.599 7.0204 21.457 7.25719C21.4147 7.32757 21.3559 7.38647 21.2855 7.42869L12.0001 12.9999L2.71463 7.42869C2.47784 7.28662 2.40106 6.97949 2.54313 6.7427C2.58536 6.67232 2.64425 6.61343 2.71463 6.5712L11.4856 1.30864C11.8022 1.11864 12.1979 1.11864 12.5145 1.30864ZM12.0001 3.33233L5.88735 6.99995L12.0001 10.6676L18.1128 6.99995L12.0001 3.33233Z"
          ></path>
        </svg>
      </div>
      <div class="grid grid-cols-2 gap-2">
        <a
          target="_blank"
          class="group col-span-2 space-y-1 rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 px-3 text-sm text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] max-sm:col-span-2"
          href="https://nuxt.com/"
          ><p class="text-lg font-medium text-[#EDEDED]">Nuxt.js</p>
          <div
            class="text-pretty flex w-full items-center justify-between gap-2"
          >
            <p class="text-base text-geist">The Vue Framework for the Web</p>
            <svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              fill="currentColor"
              class="remixicon text-geist duration-300 ease-out group-hover:rotate-45 group-hover:text-[#FFF]"
            >
              <path
                d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
              ></path>
            </svg>
          </div>
        </a>

        <a
          target="_blank"
          class="undefined group space-y-1 rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 px-3 text-sm text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] max-sm:col-span-2"
          href="https://tailwindcss.com/"
          ><p class="text-lg font-medium text-[#EDEDED]">TailwindCSS</p>
          <div
            class="text-pretty flex w-full items-center justify-between gap-2"
          >
            <p class="text-base text-geist">Utility-first CSS framework</p>
            <svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              fill="currentColor"
              class="remixicon text-geist duration-300 ease-out group-hover:rotate-45 group-hover:text-[#FFF]"
            >
              <path
                d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
              ></path>
            </svg></div
        ></a>

        <a
          target="_blank"
          class="undefined group space-y-1 rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 px-3 text-sm text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] max-sm:col-span-2"
          href="https://react.dev/"
          ><p class="text-lg font-medium text-[#EDEDED]">React.js</p>
          <div
            class="text-pretty flex w-full items-center justify-between gap-2"
          >
            <p class="text-base text-geist">front-end JavaScript library</p>
            <svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              fill="currentColor"
              class="remixicon text-geist duration-300 ease-out group-hover:rotate-45 group-hover:text-[#FFF]"
            >
              <path
                d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
              ></path>
            </svg></div
        ></a>
      </div>
    </div>
    <div style="opacity: 1; transform: none">
      <div class="headline-div">
        <p class="text-base uppercase">network</p>
        <svg
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
          width="14"
          height="14"
          fill="currentColor"
          class="remixicon"
        >
          <path
            d="M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22ZM9.71002 19.6674C8.74743 17.6259 8.15732 15.3742 8.02731 13H4.06189C4.458 16.1765 6.71639 18.7747 9.71002 19.6674ZM10.0307 13C10.1811 15.4388 10.8778 17.7297 12 19.752C13.1222 17.7297 13.8189 15.4388 13.9693 13H10.0307ZM19.9381 13H15.9727C15.8427 15.3742 15.2526 17.6259 14.29 19.6674C17.2836 18.7747 19.542 16.1765 19.9381 13ZM4.06189 11H8.02731C8.15732 8.62577 8.74743 6.37407 9.71002 4.33256C6.71639 5.22533 4.458 7.8235 4.06189 11ZM10.0307 11H13.9693C13.8189 8.56122 13.1222 6.27025 12 4.24799C10.8778 6.27025 10.1811 8.56122 10.0307 11ZM14.29 4.33256C15.2526 6.37407 15.8427 8.62577 15.9727 11H19.9381C19.542 7.8235 17.2836 5.22533 14.29 4.33256Z"
          ></path>
        </svg>
      </div>
      <div class="grid grid-cols-2 gap-2">
        <a
          target="_blank"
          class="group col-span-2 space-y-1 rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 px-3 text-sm text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] max-sm:col-span-2"
          href="mailto:mubee.jahir@gmail.com"
          ><p class="text-lg font-medium text-[#EDEDED]">Send an email</p>
          <div
            class="text-pretty flex w-full items-center justify-between gap-2"
          >
            <p class="text-base text-geist">I'll get back to you asap</p>
            <svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              fill="currentColor"
              class="remixicon text-geist duration-300 ease-out group-hover:rotate-45 group-hover:text-[#FFF]"
            >
              <path
                d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
              ></path>
            </svg></div></a
        ><a
          target="_blank"
          class="undefined group space-y-1 rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 px-3 text-sm text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] max-sm:col-span-2"
          href="https://github.com/mubeejahir"
          ><p class="text-lg font-medium text-[#EDEDED]">GitHub</p>
          <div
            class="text-pretty flex w-full items-center justify-between gap-2"
          >
            <p class="text-base text-geist">Check out my GitHub profile</p>
            <svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              fill="currentColor"
              class="remixicon text-geist duration-300 ease-out group-hover:rotate-45 group-hover:text-[#FFF]"
            >
              <path
                d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
              ></path>
            </svg></div
        ></a>
        <a
          target="_blank"
          class="undefined group space-y-1 rounded-lg border border-[#2E2E2E] bg-[#0A0A0A] p-2 px-3 text-sm text-geist duration-300 ease-in-out hover:border-geist hover:bg-[#1A1A1A] max-sm:col-span-2"
          href="https://www.linkedin.com/in/al-mubeena-j-2b3605228/"
          ><p class="text-lg font-medium text-[#EDEDED]">LinkedIn</p>
          <div
            class="text-pretty flex w-full items-center justify-between gap-2"
          >
            <p class="text-base text-geist">Let's connect on LinkedIn</p>
            <svg
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              fill="currentColor"
              class="remixicon text-geist duration-300 ease-out group-hover:rotate-45 group-hover:text-[#FFF]"
            >
              <path
                d="M16.0037 9.41421L7.39712 18.0208L5.98291 16.6066L14.5895 8H7.00373V6H18.0037V17H16.0037V9.41421Z"
              ></path>
            </svg>
          </div>
        </a>
      </div>
    </div>
    <div class="mt-20 text-center" style="opacity: 1; transform: none">
      <p class="text-base font-medium text-geist">Thanks for visiting</p>
      <p class="text-sm font-medium text-[#7D7D7D]">Stay awesome</p>
      <p
        class="neonText hover:bg-indigo-500 my-6 inline-block font-holimount text-5xl font-medium text-[#EDEDED] duration-300 hover:-translate-y-1 hover:scale-110"
      >
        Al Mubeena
      </p>
      <p class="text-sm font-medium text-[#7D7D7D]">
        © {{ currentYear }} Made By Al Mubeena
      </p>
    </div>
  </main>
</template>

<script>
const date = new Date();

export default {
  data() {
    return {
      currentYear: date.getFullYear(),
    };
  },
};
</script>

<style scoped>
.neonText {
  color: #fff;
  text-shadow:
    /* White glow */ 0 0 7px #fff, 0 0 10px #fff, 0 0 21px #fff;
}
.headline-div {
  margin-top: 2.5rem;
  margin-bottom: 0.75rem;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  gap: 0.5rem;
  --tw-text-opacity: 1;
  color: rgb(161 161 161 / var(--tw-text-opacity));
}

.project-link {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  overflow: hidden;
  border-radius: 6px;
  padding: 0.5rem;
  transition-duration: 0.3s;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  animation-duration: 0.3s;
  animation-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  border-width: 1px;
  --tw-border-opacity: 1;
  border-color: rgb(46 46 46 / var(--tw-border-opacity));
}
.project-link-content {
  display: flex;
  width: 100%;
  flex-direction: column;
  gap: 0.75rem;
  padding: 0.25rem;
  font-size: 0.875rem;
  line-height: 1.25rem;
  --tw-text-opacity: 1;
  color: rgb(161 161 161 / var(--tw-text-opacity));
}

.fadeup {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeUp 1s ease-out forwards;
}

@keyframes fadeUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
