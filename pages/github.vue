<template>
  <div class="text-gray-900 bg-page-gray">
    <nav
      class="
        bg-gray-900-github
        text-white
        px-6
        py-4
        flex
        items-center
        justify-between
      "
    >
      <div class="flex items-center space-x-4">
        <a href="#">
          <svg
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            width="32"
            data-view-component="true"
            class="w-8 fill-current hover:text-gray-500"
          >
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>
        </a>
        <div class="relative">
          <input
            type="text"
            class="rounded bg-black placeholder-gray w-72 px-3 py-1 text-sm"
            placeholder="Search or jump to..."
          />
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div
              class="
                border border-gray-800
                rounded
                text-xs text-gray-500
                px-2
                mr-2
              "
            >
              /
            </div>
          </div>
        </div>
        <ul class="flex items-center font-semibold space-x-4 text-sm">
          <li class="hover:text-gray-400"><a href="#">Pull Requests</a></li>
          <li class="hover:text-gray-400"><a href="#">Issues</a></li>
          <li class="hover:text-gray-400"><a href="#">Marketplace</a></li>
          <li class="hover:text-gray-400"><a href="#">Explore</a></li>
        </ul>
      </div>
      <div class="flex items-center text-white space-x-4">
        <a href="#" class="relative">
          <svg
            aria-hidden="true"
            height="16"
            viewBox="0 0 16 16"
            version="1.1"
            width="16"
            data-view-component="true"
            class="w-4 fill-current hover:text-gray-500"
          >
            <path
              d="M8 16a2 2 0 001.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 008 16z"
            ></path>
            <path
              fill-rule="evenodd"
              d="M8 1.5A3.5 3.5 0 004.5 5v2.947c0 .346-.102.683-.294.97l-1.703 2.556a.018.018 0 00-.003.01l.001.006c0 .002.002.004.004.006a.017.017 0 00.006.004l.007.001h10.964l.007-.001a.016.016 0 00.006-.004.016.016 0 00.004-.006l.001-.007a.017.017 0 00-.003-.01l-1.703-2.554a1.75 1.75 0 01-.294-.97V5A3.5 3.5 0 008 1.5zM3 5a5 5 0 0110 0v2.947c0 .05.015.098.042.139l1.703 2.555A1.518 1.518 0 0113.482 13H2.518a1.518 1.518 0 01-1.263-2.36l1.703-2.554A.25.25 0 003 7.947V5z"
            ></path>
          </svg>
          <div
            class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0"
          ></div>
        </a>
        <a href="#" class="flex items-center hover:text-gray-500">
          <svg
            aria-hidden="true"
            height="16"
            viewBox="0 0 16 16"
            version="1.1"
            width="16"
            data-view-component="true"
            class="w-4 fill-current hover:text-gray-500"
          >
            <path
              fill-rule="evenodd"
              d="M7.75 2a.75.75 0 01.75.75V7h4.25a.75.75 0 110 1.5H8.5v4.25a.75.75 0 11-1.5 0V8.5H2.75a.75.75 0 010-1.5H7V2.75A.75.75 0 017.75 2z"
            ></path></svg
          ><svg
            class="ml-1w-3 h-3"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            ></path>
          </svg>
        </a>
        <a href="#" class="flex items-center hover:text-gray-500">
          <img
            src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
            alt="@AlexGroat"
            size="20"
            height="20"
            width="20"
            data-view-component="true"
            class="w-5 h-5 rounded-full"
          />
          <svg
            class="ml-1w-3 h-3"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            ></path>
          </svg>
        </a>
      </div>
    </nav>

    <div class=" bg-cover">
      <!-- page background -->
      <div class="repo-stats flex items-center justify-between px-8 py-4">
        <div class="flex items-center">
          <a href="">
            <svg
              class="w-6 h-6 text-gray-600"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 8h14M5 8a2 2 0 110-4h14a2 2 0 110 4M5 8v10a2 2 0 002 2h10a2 2 0 002-2V8m-9 4h4"
              ></path>
            </svg>
          </a>
          <div class="flex items-center">
            <a class="hover:underline text-xl ml-2 text-blue-600" href="#"
              >AlexGroat</a
            >
            <span class="ml-1 font-bold text-xl ml-2 text-blue-600">/</span>
            <a
              class="
                hover:underline
                ml-1
                font-semibold
                text-xl
                ml-2
                text-blue-600
              "
              href="#"
              >AlexsProject</a
            >
            <button
              class="
                rounded-r-full rounded-l-full
                border border-gray-600
                hover:border-gray-400
                text-gray-600 text-sm
                px-1
                ml-2
                font-semibold
              "
            >
              Public
            </button>
          </div>
        </div>
        <div class="flex items-center space-x-2 text-white">
          <div class="flex text-xs">
            <button
              class="
                border border-gray-800
                hover:border-gray-400
                rounded-lg rounded-r-none
                px-3
                py-1
                flex
                items-center
                space-x-1
                bg-gray-800-github
                text-gray-400
              "
            >
              <a href="" class="fill-current">
                <svg
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="w-4 h-4 mr-1 text-gray-400"
                >
                  <path
                    fill-rule="evenodd"
                    d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"
                  ></path></svg
              ></a>
              Watch
              <svg
                class="ml-1 w-3 h-3"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M19 9l-7 7-7-7"
                ></path>
              </svg>
            </button>
            <a
              href="#"
              class="
                border border-gray-800
                hover:border-gray-400
                rounded-lg rounded-l-none
                px-3
                py-1
                font-semibold
                hover:text-blue-600
                bg-gray-800-github
                text-gray-400
              "
            >
              276
            </a>
          </div>
          <div class="flex text-xs">
            <button
              class="
                border border-gray-800
                hover:border-gray-400
                rounded-lg rounded-r-none
                px-3
                py-1
                flex
                items-center
                space-x-1
                bg-gray-800-github
                text-gray-400
              "
            >
              <a href="" class="fill-current"
                ><svg
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="octicon octicon-repo-forked mr-1 text-gray-400"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"
                  ></path></svg
              ></a>
              Fork
              <svg
                class="ml-1w-3 h-3"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M19 9l-7 7-7-7"
                ></path>
              </svg>
            </button>
            <a
              href="#"
              class="
                border border-gray-800
                hover:border-gray-400
                rounded-lg rounded-l-none
                px-3
                py-1
                font-semibold
                hover:text-blue-600
                text-gray-400
                bg-gray-800-github
              "
            >
              2.1K
            </a>
          </div>
          <div class="flex text-xs">
            <button
              class="
                border border-gray-800
                hover:border-gray-400
                rounded-lg rounded-r-none
                px-3
                py-1
                flex
                items-center
                space-x-1
                bg-gray-800-github
                text-gray-400
              "
            >
              <a href="" class="fill-current"
                ><svg
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="octicon octicon-star d-inline-block mr-1 text-gray-400"
                >
                  <path
                    fill-rule="evenodd"
                    d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"
                  ></path>
                </svg>
              </a>
              Star
              <a href="" class=""
                ><svg
                  class="ml-1w-3 h-3"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M19 9l-7 7-7-7"
                  ></path>
                </svg>
              </a>
            </button>
            <a
              href="#"
              class="
                border border-gray-800
                hover:border-gray-400
                rounded-lg rounded-l-none
                px-3
                py-1
                font-semibold
                hover:text-blue-600
                bg-gray-800-github
                text-gray-400
              "
            >
              433
            </a>
          </div>
        </div>
      </div>
      <!--end repo stats -->

      <ul
        class="
          repo-nav
          border-b border-gray-900
          flex
          items-center
          px-5
          mt-4
          text-gray-400 text-sm
        "
      >
        <li class="">
          <a
            href=""
            class="
              flex
              items-center
              border-b-2 border-red-400
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-code
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M4.72 3.22a.75.75 0 011.06 1.06L2.06 8l3.72 3.72a.75.75 0 11-1.06 1.06L.47 8.53a.75.75 0 010-1.06l4.25-4.25zm6.56 0a.75.75 0 10-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 101.06 1.06l4.25-4.25a.75.75 0 000-1.06l-4.25-4.25z"
                ></path></svg
            ></a>
            <span class="ml-2">Code</span>
          </a>
        </li>
        <li class="">
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-issue-opened
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path d="M8 9.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
                <path
                  fill-rule="evenodd"
                  d="M8 0a8 8 0 100 16A8 8 0 008 0zM1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Issues</span>
            <div
              class="
                text-xs
                rounded-lg
                border border-gray-800
                hover:border-gray-400
                px-1
                ml-1
                bg-gray-700
                text-gray-400
                hover:text-blue-500
                rounded
                hover:bg-gray-700
              "
            >
              102
            </div>
          </a>
        </li>
        <li class="">
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-git-pull-request
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Pull Requests</span>
            <div
              class="
                text-xs
                rounded-lg
                border border-gray-800
                hover:border-gray-400
                px-1
                ml-1
                bg-gray-700
                text-gray-400
                hover:text-blue-500
              "
            >
              102
            </div>
          </a>
        </li>
        <li class="">
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-play
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Actions</span>
          </a>
        </li>
        <li class="">
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-table
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v3.585a.746.746 0 010 .83v8.085A1.75 1.75 0 0114.25 16H6.309a.748.748 0 01-1.118 0H1.75A1.75 1.75 0 010 14.25V6.165a.746.746 0 010-.83V1.75zM1.5 6.5v7.75c0 .138.112.25.25.25H5v-8H1.5zM5 5H1.5V1.75a.25.25 0 01.25-.25H5V5zm1.5 1.5v8h7.75a.25.25 0 00.25-.25V6.5h-8zm8-1.5h-8V1.5h7.75a.25.25 0 01.25.25V5z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Projects</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-book
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Wiki</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-shield
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Security</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-graph
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Insights</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="
              flex
              items-center
              border-b-2 border-transparent
              hover:border-gray-600
              transition
              ease-in-out
              duration
              150
              px-3
              pb-3
              rounded
              hover:bg-gray-700
            "
          >
            <a href="" class="fill-current">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-gear
                  UnderlineNav-octicon
                  d-none d-sm-inline
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M7.429 1.525a6.593 6.593 0 011.142 0c.036.003.108.036.137.146l.289 1.105c.147.56.55.967.997 1.189.174.086.341.183.501.29.417.278.97.423 1.53.27l1.102-.303c.11-.03.175.016.195.046.219.31.41.641.573.989.014.031.022.11-.059.19l-.815.806c-.411.406-.562.957-.53 1.456a4.588 4.588 0 010 .582c-.032.499.119 1.05.53 1.456l.815.806c.08.08.073.159.059.19a6.494 6.494 0 01-.573.99c-.02.029-.086.074-.195.045l-1.103-.303c-.559-.153-1.112-.008-1.529.27-.16.107-.327.204-.5.29-.449.222-.851.628-.998 1.189l-.289 1.105c-.029.11-.101.143-.137.146a6.613 6.613 0 01-1.142 0c-.036-.003-.108-.037-.137-.146l-.289-1.105c-.147-.56-.55-.967-.997-1.189a4.502 4.502 0 01-.501-.29c-.417-.278-.97-.423-1.53-.27l-1.102.303c-.11.03-.175-.016-.195-.046a6.492 6.492 0 01-.573-.989c-.014-.031-.022-.11.059-.19l.815-.806c.411-.406.562-.957.53-1.456a4.587 4.587 0 010-.582c.032-.499-.119-1.05-.53-1.456l-.815-.806c-.08-.08-.073-.159-.059-.19a6.44 6.44 0 01.573-.99c.02-.029.086-.075.195-.045l1.103.303c.559.153 1.112.008 1.529-.27.16-.107.327-.204.5-.29.449-.222.851-.628.998-1.189l.289-1.105c.029-.11.101-.143.137-.146zM8 0c-.236 0-.47.01-.701.03-.743.065-1.29.615-1.458 1.261l-.29 1.106c-.017.066-.078.158-.211.224a5.994 5.994 0 00-.668.386c-.123.082-.233.09-.3.071L3.27 2.776c-.644-.177-1.392.02-1.82.63a7.977 7.977 0 00-.704 1.217c-.315.675-.111 1.422.363 1.891l.815.806c.05.048.098.147.088.294a6.084 6.084 0 000 .772c.01.147-.038.246-.088.294l-.815.806c-.474.469-.678 1.216-.363 1.891.2.428.436.835.704 1.218.428.609 1.176.806 1.82.63l1.103-.303c.066-.019.176-.011.299.071.213.143.436.272.668.386.133.066.194.158.212.224l.289 1.106c.169.646.715 1.196 1.458 1.26a8.094 8.094 0 001.402 0c.743-.064 1.29-.614 1.458-1.26l.29-1.106c.017-.066.078-.158.211-.224a5.98 5.98 0 00.668-.386c.123-.082.233-.09.3-.071l1.102.302c.644.177 1.392-.02 1.82-.63.268-.382.505-.789.704-1.217.315-.675.111-1.422-.364-1.891l-.814-.806c-.05-.048-.098-.147-.088-.294a6.1 6.1 0 000-.772c-.01-.147.039-.246.088-.294l.814-.806c.475-.469.679-1.216.364-1.891a7.992 7.992 0 00-.704-1.218c-.428-.609-1.176-.806-1.82-.63l-1.103.303c-.066.019-.176.011-.299-.071a5.991 5.991 0 00-.668-.386c-.133-.066-.194-.158-.212-.224L10.16 1.29C9.99.645 9.444.095 8.701.031A8.094 8.094 0 008 0zm1.5 8a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM11 8a3 3 0 11-6 0 3 3 0 016 0z"
                ></path>
              </svg>
            </a>
            <span class="ml-2">Settings</span>
          </a>
        </li>
      </ul>
      <!-- end repo nav -->

      <div class="container mx-auto my-8 px-4 flex mt-6">
        <div class="file-explorer-container w-3/4 mr-8 text-white">
          <div class="branch-nav flex items-center justify-between">
            <div class="flex items-center space-x-2">
              <button
                class="
                  border border-gray-800
                  rounded-md
                  px-3
                  py-1
                  hover:bg-gray-700
                  flex
                  items-center
                  space-x-2
                  bg-gray-800-github
                  text-gray-400
                "
              >
                <svg
                  text="gray"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="octicon octicon-git-branch fill-current w-4 h-4"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                  ></path>
                </svg>
                <div class="font-semibold text-sm">main</div>
                <svg
                  class="ml-1 w-3 h-3"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M19 9l-7 7-7-7"
                  ></path>
                </svg>
              </button>

              <a
                href="#"
                class="hidden lg:flex items-center space-x-1 py-1 px-2 group"
              >
                <svg
                  class="fill-current group-hover:text-blue-600 w-4"
                  text="gray"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                  ></path>
                </svg>
                <span class="group-hover:text-blue-600">
                  <span class="font-semibold text-sm">25 </span>
                  <span class="group-hover:text-blue-600 text-gray-600 text-sm"
                    >branches</span
                  >
                </span>
              </a>
              <a
                href="#"
                class="
                  hidden
                  lg:flex
                  items-center
                  space-x-1
                  py-1
                  px-2
                  fill-current
                  group
                "
              >
                <svg
                  text="gray"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="octicon octicon-tag group-hover:text-blue-600 w-4 h-4"
                >
                  <path
                    fill-rule="evenodd"
                    d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
                  ></path>
                </svg>
                <span class="group-hover:text-blue-600">
                  <span class="font-semibold text-sm">11 </span>
                  <span class="group-hover:text-blue-600 text-gray-600 text-sm"
                    >tags</span
                  >
                </span>
              </a>
            </div>
            <div class="flex items-center space-x-2">
              <button
                class="
                  border border-gray-800
                  hover:border-gray-400 hover:bg-gray-700
                  rounded-lg
                  px-4
                  py-1
                  flex
                  items-center
                  space-x-1
                  bg-gray-800-github
                  text-sm
                  font-semibold
                  text-gray-400
                "
              >
                Go to file
              </button>
              <button
                class="
                  border border-gray-800
                  hover:border-gray-400
                  rounded-lg
                  px-4
                  py-1
                  flex
                  items-center
                  space-x-1
                  bg-gray-800-github
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-gray-700
                "
              >
                Add file
                <svg
                  class="ml-1 w-3 h-3"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M19 9l-7 7-7-7"
                  ></path>
                </svg>
              </button>
              <button
                class="
                  border border-gray-800
                  hover:border-gray-400
                  rounded-lg
                  px-4
                  py-1
                  flex
                  items-center
                  space-x-1
                  bg-green-500-github
                  hover:bg-green-600
                  text-sm
                  font-semibold
                "
              >
                Code
                <svg
                  class="ml-1 w-3 h-3"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M19 9l-7 7-7-7"
                  ></path>
                </svg>
              </button>
            </div>
          </div>
          <!-- end branch nav -->

          <div
            class="
              commits-container
              bg-gray-600-github
              border border-gray-800
              rounded-md rounded-b-none
              border-b-none
              mt-5
              px-4
              py-4
              flex
              items-center
              justify-between
            "
          >
            <div class="flex items-center space-x-2 text-sm text-gray-400">
              <a href="#" class="flex items-center hover:text-gray-500">
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  alt="@AlexGroat"
                  size="20"
                  height="20"
                  width="20"
                  data-view-component="true"
                  class="w-5 h-5 rounded-full"
                />
              </a>
              <a href="#" class="font-semibold hover:underline">AlexGroat</a>
              <a href="#" class="hover:underline hover:text-blue-500"
                >finished the top navs section</a
              >
            </div>
            <div
              class="flex items-center text-sm text-gray-500 space-x-2 group"
            >
              <a
                href="#"
                class="text-xs group-hover:text-blue-600 hover:underline"
              >
                c6a2353</a
              >
              <a
                href="#"
                class="text-sm group-hover:text-blue-600 hover:underline"
              >
                17 hours ago</a
              >
              <a href="#" class="flex items-center ml-3">
                <svg
                  text="gray"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="w-4 fill-current text-gray-400"
                >
                  <path
                    fill-rule="evenodd"
                    d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"
                  ></path>
                </svg>
                <span class="ml-1"
                  ><span class="font-semibold mr-1 text-gray-400">34</span
                  >commits</span
                >
              </a>
            </div>
          </div>
          <!-- end commits container -->

          <div
            class="
              file-explorer
              rounded-md rounded-t-none
              border border-gray-800
              text-gray-400
              divide-y divide-gray-800
              text-sm
            "
          >
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="Directory"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="fill-current w-4 h-4 mr-2 text-gray-500"
                >
                  <path
                    d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H7.5a.25.25 0 01-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">assets</p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="Directory"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="fill-current w-4 h-4 mr-2 text-gray-500"
                >
                  <path
                    d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H7.5a.25.25 0 01-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  components
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="Directory"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="fill-current w-4 h-4 mr-2 text-gray-500"
                >
                  <path
                    d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H7.5a.25.25 0 01-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">layouts</p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="Directory"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="fill-current w-4 h-4 mr-2 text-gray-500"
                >
                  <path
                    d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H7.5a.25.25 0 01-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  middleware
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="Directory"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="fill-current w-4 h-4 mr-2 text-gray-500"
                >
                  <path
                    d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H7.5a.25.25 0 01-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">pages</p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="Directory"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="fill-current w-4 h-4 mr-2 text-gray-500"
                >
                  <path
                    d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H7.5a.25.25 0 01-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">plugins</p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="Directory"
                  aria-hidden="true"
                  viewBox="0 0 16 16"
                  version="1.1"
                  data-view-component="true"
                  class="fill-current w-4 h-4 mr-2 text-gray-500"
                >
                  <path
                    d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H7.5a.25.25 0 01-.2-.1l-.9-1.2C6.07 1.26 5.55 1 5 1H1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">static</p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Praesentium nobis dicta quia facere vero adipisci sunt
                voluptatibus rerum cumque atque, maiores commodi accusantium
                laudantium iure perspiciatis aliquam fuga, iusto quod?
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  .editorconfig
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  .gitignore
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  README.md
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  nuxt.config.js
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  old_postcss.config.js
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  package-lock.json
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  package.json
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
            <div
              class="flex justify-between px-4 py-2 hover:bg-gray-800-github"
            >
              <div class="flex items-center w-4/12">
                <svg
                  aria-label="File"
                  aria-hidden="true"
                  height="16"
                  viewBox="0 0 16 16"
                  version="1.1"
                  width="16"
                  data-view-component="true"
                  class="
                    octicon octicon-file
                    color-fg-muted
                    fill-current
                    text-gray-600
                  "
                >
                  <path
                    fill-rule="evenodd"
                    d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"
                  ></path>
                </svg>
                <p class="hover:text-blue-500 hover:underline ml-2">
                  tailwind-config.js
                </p>
              </div>
              <div
                class="
                  w-6/12
                  truncate
                  text-gray-600
                  hover:text-blue-500 hover:underline
                "
              >
                commit message
              </div>
              <div class="w-2/12 text-gray-600 text-right">4 hours ago</div>
            </div>
          </div>
          <!-- end file explorer -->
          <div
            class="
              readme-container
              rounded-md
              border border-gray-800
              mt-4
              px-6
              py-3
              text-gray-400
              flex
              items-center
              justify-between
            "
          >
            <div class="flex items-center">
              <svg
                aria-hidden="true"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                data-view-component="true"
                class="
                  octicon octicon-list-unordered
                  fill-current
                  mr-4
                  text-gray-500
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M2 4a1 1 0 100-2 1 1 0 000 2zm3.75-1.5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zM3 8a1 1 0 11-2 0 1 1 0 012 0zm-1 6a1 1 0 100-2 1 1 0 000 2z"
                ></path></svg
              >README.md
            </div>
            <div>
              <svg
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
                class="
                  octicon octicon-pencil
                  fill-current
                  w-4
                  h-4
                  mr-2
                  text-gray-600
                "
              >
                <path
                  fill-rule="evenodd"
                  d="M11.013 1.427a1.75 1.75 0 012.474 0l1.086 1.086a1.75 1.75 0 010 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 01-.927-.928l.929-3.25a1.75 1.75 0 01.445-.758l8.61-8.61zm1.414 1.06a.25.25 0 00-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 000-.354l-1.086-1.086zM11.189 6.25L9.75 4.81l-6.286 6.287a.25.25 0 00-.064.108l-.558 1.953 1.953-.558a.249.249 0 00.108-.064l6.286-6.286z"
                ></path>
              </svg>
            </div>
          </div>
          <div class="border border-gray-800 rounded-md rounded-t-none">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Adipisci
            asperiores laboriosam id illum dolorem vero obcaecati dolores eius?
            Cum, id! Lorem ipsum dolor sit, amet consectetur adipisicing elit.
            Unde suscipit consequatur quo fugiat non similique rem sit ipsum
            velit veritatis, quam voluptas, cum possimus sapiente quod nostrum
            illum ipsa! Quibusdam. Lorem ipsum dolor sit amet consectetur
            adipisicing elit. Expedita cumque quia obcaecati temporibus, quam
            tempore aliquid voluptatibus consectetur qui accusantium laudantium
            velit sequi, soluta aut dicta nam ut necessitatibus blanditiis.
          </div>
          <!-- end readme container -->
        </div>
        <!-- end file exporer container -->
        <div class="sidebar w-1/4 text-gray-500">
          <div class="about">
            <h4 class="text-base font-semibold">About</h4>
            <p class="text-base mt-4 text-gray-400">
              A utility first CSS framework for rapid UI development.
            </p>

            <div class="flex items-center space-x-2 mt-4">
              <svg
                class="w-4 fill-current"
                mr="2"
                classes="flex-shrink-0"
                viewBox="0 0 16 16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"
                ></path>
              </svg>
              <a href="#" class="text-blue-600 hover:underline font-semibold"
                >tailwindcss.com/</a
              >
            </div>
          </div>

          <div
            class="tags text-xs font-semibold flex items-center flex-wrap mt-2"
          >
            <a
              href="#"
              class="
                bg-blue-900
                text-blue-500
                rounded-full
                px-2
                py-1
                mt-2
                text-tag-blue
                hover:bg-blue-700 hover:text-white
                mr-1
              "
              >tailwindcss</a
            >
            <a
              href="#"
              class="
                bg-blue-900
                text-blue-500
                rounded-full
                px-2
                py-1
                mt-2
                text-tag-blue
                hover:bg-blue-700 hover:text-white
                mr-1
              "
              >css</a
            >
            <a
              href="#"
              class="
                bg-blue-900
                text-blue-500
                rounded-full
                px-2
                py-1
                mt-2
                text-tag-blue
                hover:bg-blue-700 hover:text-white
                mr-1
              "
              >css-framework</a
            >
            <a
              href="#"
              class="
                bg-blue-900
                text-blue-500
                rounded-full
                px-2
                py-1
                mt-2
                text-tag-blue
                hover:bg-blue-700 hover:text-white
                mr-1
              "
              >postcss</a
            >
            <a
              href="#"
              class="
                bg-blue-900
                text-blue-500
                rounded-full
                px-2
                py-1
                mt-2
                text-tag-blue
                hover:bg-blue-700 hover:text-white
                mr-1
              "
              >functional-css</a
            >
            <a
              href="#"
              class="
                bg-blue-900
                text-blue-500
                rounded-full
                px-2
                py-1
                mt-2
                text-tag-blue
                hover:bg-blue-700 hover:text-white
                mr-1
              "
              >utility-classes</a
            >
            <a
              href="#"
              class="
                bg-blue-900
                text-blue-500
                rounded-full
                px-2
                py-1
                mt-2
                text-tag-blue
                hover:bg-blue-700 hover:text-white
                mr-1
              "
              >responsive</a
            >
          </div>

          <div class="text-sm">
            <a href="#" class="flex items-center space-x-2 mt-4 group">
              <svg
                class="
                  w-4
                  fill-current
                  text-gray-600
                  group-hover:text-blue-600
                  mr-2
                "
                viewBox="0 0 16 16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"
                ></path>
              </svg>
              <span class="text-gray-600 group-hover:text-blue-600"
                >Readme</span
              >
            </a>
            <a href="#" class="flex items-center space-x-2 mt-1 group text-sm">
              <svg
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
                class="octicon octicon-star w-4 h-4 mr-2 fill-current"
              >
                <path
                  fill-rule="evenodd"
                  d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"
                ></path>
              </svg>
              <span class="text-gray-600 group-hover:text-blue-600"
                >4 stars</span
              >
            </a>
            <a href="#" class="flex items-center space-x-2 mt-1 group">
              <svg
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
                class="octicon octicon-eye w-4 h-4 mr-2 fill-current"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"
                ></path>
              </svg>
              <span class="text-gray-600 group-hover:text-blue-600"
                >3 watching</span
              >
            </a>
            <a href="#" class="flex items-center space-x-2 mt-1 group">
              <svg
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
                class="octicon octicon-repo-forked mr-2 w-4 h-4 fill-current"
              >
                <path
                  fill-rule="evenodd"
                  d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"
                ></path>
              </svg>
              <span class="text-gray-600 group-hover:text-blue-600"
                >6 forks</span
              >
            </a>
          </div>
          <!-- end about -->
          <div class="releases border-t border-gray-800 mt-6 pt-6">
            <h4 class="text-base font-semibold flex items-center">
              <span class="hover:text-blue-500 hover:underline">Releases</span>
              <div
                class="text-xs rounded-lg px-2 ml-1 bg-gray-700 text-gray-400"
              >
                24
              </div>
            </h4>

            <a href="#" class="flex items-start mt-4 group">
              <svg
                class="
                  fill-current
                  mt-1
                  w-4
                  text-green-450
                  group-hover:text-blue-500
                "
                mt="1"
                classes="flex-shrink-0"
                color="green"
                viewBox="0 0 16 16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
                ></path>
              </svg>
              <span class="ml-2">
                <span class="font-semibold group-hover:text-blue-600"
                  >v1.5.1</span
                >
                <span
                  class="
                    ml-1
                    text-xs
                    border border-green-450
                    text-green-450
                    rounded-full
                    font-semibold
                    inline-block
                    px-2
                  "
                  >Latest</span
                >
                <span class="block text-xs group-hover:text-blue-600"
                  >6 days ago</span
                >
              </span>
            </a>

            <div class="mt-4">
              <a href="" class="text-blue-600 hover:underline text-sm"
                >+ 47 releases</a
              >
            </div>
          </div>
          <div class="used-by border-t border-gray-800 mt-6 pt-6">
            <h4 class="text-base font-semibold flex items-center">
              <span class="hover:text-blue-500 hover:underline">Used by</span>
              <div
                class="text-xs rounded-lg px-2 ml-1 bg-gray-700 text-gray-400"
              >
                2.1K
              </div>
            </h4>
            <div class="mt-4">
              <a href="#" class="flex items-center">
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full border-2 border-black"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full border-2 border-black -ml-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full border-2 border-black -ml-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full border-2 border-black -ml-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full border-2 border-black -ml-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full border-2 border-black -ml-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full border-2 border-black -ml-2"
                  alt="avatar"
                />
                <span
                  class="
                    text-sm text-blue-500
                    font-semibold
                    hover:underline
                    ml-2
                  "
                  >+ 2,097</span
                >
              </a>
            </div>
          </div>
          <div class="contributors border-t border-gray-800 mt-6 pt-6">
            <h4 class="text-base font-semibold flex items-center">
              <span class="hover:text-blue-500 hover:underline"
                >Contributors</span
              >
              <div
                class="text-xs rounded-lg px-2 ml-1 bg-gray-700 text-gray-400"
              >
                123
              </div>
            </h4>
            <div class="mt-2">
              <a href="#" class="flex flex-wrap items-center">
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                <img
                  src="https://avatars.githubusercontent.com/u/88314794?s=40&amp;v=4"
                  class="w-8 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
                
                <span
                  class="
                    text-sm text-blue-500
                    font-semibold
                    hover:underline
                    ml-2
                  "
                  >+ 2,097</span
                >
              </a>
            </div>
          </div>
          <div class="languages border-t border-gray-800 mt-6 pt-6">
            <h4 class="text-base font-semibold flex items-center">
              <span class="hover:text-blue-500 hover:underline">Languages</span>
            </h4>
            <div class="mt-4 flex">
              <div class="w-11/12 h-2 rounded-md rounded-r-none bg-purple-700"></div>
              <div class="w-1/12 h-2 rounded-md rounded-l-none bg-yellow-700"></div>
            </div>
          </div>
        </div>
        <!-- end sidebar -->
      </div>
    </div>
    <footer
      class="
        bg-page-gray
        relative
        container
        text-white
        mx-auto
        mt-24
        text-xs
        border-t border-gray-800
        py-12
        flex
        items-center
        justify-between
      "
    >
      <div class="space-x-2 flex items-center">
        <div class="flex items-center mr-12">
          <svg
            aria-hidden="true"
            viewBox="0 0 16 16"
            version="1.1"
            data-view-component="true"
            class="
              octicon octicon-mark-github
              fill-current
              w-6
              h-6
              text-gray-600
            "
          >
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>

          <p class="text-xs ml-2 text-gray-600">&copy; 2022 Github, Inc.</p>
        </div>

        <div>
          <ul class="flex space-x-12">
            <li class="text-blue-500 hover:underline">Terms</li>
            <li class="text-blue-500 hover:underline">Privacy</li>
            <li class="text-blue-500 hover:underline">Security</li>
            <li class="text-blue-500 hover:underline">Status</li>
            <li class="text-blue-500 hover:underline">Docs</li>
            <li class="text-blue-500 hover:underline">Contact Github</li>
            <li class="text-blue-500 hover:underline">Pricing</li>
            <li class="text-blue-500 hover:underline">API</li>
            <li class="text-blue-500 hover:underline">Training</li>
            <li class="text-blue-500 hover:underline">Blog</li>
            <li class="text-blue-500 hover:underline">About</li>
          </ul>
        </div>
      </div>
    </footer>
  </div>
</template>
