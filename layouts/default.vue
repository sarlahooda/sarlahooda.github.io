<template>
  <nav>
    <div class="relative min-h-screen md:flex" data-dev-hint="container">
      <input type="checkbox" id="menu-open" class="hidden" />


      <header
        class="bg-yellow-600 text-gray-100 flex justify-between md:hidden"
        data-dev-hint="mobile menu bar"
      >
        <a
          href="#"
          class="block p-4 text-white font-bold whitespace-nowrap truncate"
        >
          भगवद्गीता
        </a>

        <label
          for="menu-open"
          id="mobile-menu-button"
          class="
            m-2
            p-2
            focus:outline-none
            hover:text-white
            hover:bg-yellow-700
            rounded-md
          "
        >
          <svg
            id="menu-open-icon"
            class="h-6 w-6 transition duration-200 ease-in-out"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"
            />
          </svg>
          <svg
            id="menu-close-icon"
            class="h-6 w-6 transition duration-200 ease-in-out"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M6 18L18 6M6 6l12 12"
            />
          </svg>
        </label>
      </header>

      <aside
        id="sidebar"
        class="
          bg-yellow-800
          text-gray-100
          md:w-96
          w-3/4
          space-y-6
          pt-6
          px-0
          absolute
          inset-y-0
          left-0
          transform
          md:relative
          md:translate-x-0
          transition
          duration-200
          ease-in-out
          md:flex md:flex-col
          md:justify-between
          overflow-y-auto
        "
        data-dev-hint="sidebar; px-0 for frameless; px-2 for visually inset the navigation"
      >
        <div
          class="flex flex-col space-y-6"
          
        >
          <a
            href="#"
            class="text-white flex items-center space-x-2 px-4"
            title="भगवद्गीता मुखपृष्ठ"
          >
            
            <span class="text-4xl font-light whitespace-nowrap truncate py-10"
              >भगवद्गीता</span
            >
          </a>

          <nav data-dev-hint="main navigation">
            <!-- <a
              href="#"
              class="
                flex
                items-center
                space-x-2
                py-2
                px-4
                transition
                duration-200
                hover:bg-yellow-700
                hover:text-white
              "
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 w-4"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path d="M12 14l9-5-9-5-9 5 9 5z" />
                <path
                  d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222"
                />
              </svg>
              <span>Introduction</span>
            </a> -->
            <a
              href="/chapter/1"
              class="
                flex
                items-center
                space-x-2
                py-2
                px-4
                transition
                duration-200
                hover:bg-yellow-700
                hover:text-white
              "
            >
              <span class="ml-6">अध्याय एक</span>
            </a>
            <a
              href="/chapter/2"
              class="
                flex
                items-center
                space-x-2
                py-2
                px-4
                transition
                duration-200
                hover:bg-yellow-700
                hover:text-white
              "
            >
              <span class="ml-6">अध्याय दो</span>
            </a>
            <a
              href="/chapter/3"
              class="
                flex
                items-center
                space-x-2
                py-2
                px-4
                transition
                duration-200
                hover:bg-yellow-700
                hover:text-white
              "
            >
              <span class="ml-6">अध्याय तीन</span>
            </a>

            <a
              href="/chapter/4"
              class="
                flex
                items-center
                space-x-2
                py-2
                px-4
                transition
                duration-200
                hover:bg-yellow-700
                hover:text-white
              "
            >
              <span class="ml-6">अध्याय चार</span>
            </a>
            <!-- <a
              href="#"
              class="
                flex
                items-center
                space-x-2
                py-2
                px-4
                transition
                duration-200
                hover:bg-yellow-700
                hover:text-white
                group
              "
            >
              <span
                class="
                  w-4
                  h-4
                  flex-shrink-0
                  border border-yellow-600
                  rounded
                  group-hover:border-gray-400
                  transition
                  duration-200
                "
              ></span>
              <span>Chapter 2</span>
            </a> -->
          </nav>
        </div>

        <nav data-dev-hint="second-main-navigation or footer navigation">
          <a
            href="#"
            class="
              block
              py-2
              px-4
              transition
              duration-200
              hover:bg-yellow-700
              hover:text-white
            "
          >
            About the Author
          </a>
          <a
            href="#"
            class="
              block
              py-2
              px-4
              transition
              duration-200
              hover:bg-yellow-700
              hover:text-white
            "
          >
            Contact
          </a>
          <a
            href="#"
            class="
              block
              py-2
              px-4
              transition
              duration-200
              hover:bg-yellow-700
              hover:text-white
            "
          >
            Copyright
          </a>
        </nav>
      </aside>

      <main id="content" class="flex-1">
        <div class="max-w-7xl mx-auto">
          <!-- Replace with your content -->
          
            <Nuxt />
         
          <!-- /End replace -->
        </div>
      </main>
    </div>
  </nav>
</template>

