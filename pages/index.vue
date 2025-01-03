<template>
  <div class="flex flex-col  p-10 sm:p-20 space-y-4 text-black">

    <img src="/assets/logo.svg" width="70px" class="drop-shadow-sm" />

    <div class="text-3xl text-black">fylepad — your perfect note-taking solution!
    </div>

    <div class="flex space-x-2 py-2">
      <a href="https://github.com/imrofayel/fylepad/stargazers"><img
          src="https://img.shields.io/github/stars/imrofayel/fylepad" alt="GitHub Repo stars" /></a> <a
        href="https://github.com/imrofayel/fylepad/releases/"><img
          src="https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white"
          alt="Windows Release" /></a> <a href="https://github.com/imrofayel/fylepad/releases/"><img
          src="https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=F0F0F0" alt="MacOS Release" /></a> <a
        href="https://github.com/imrofayel/fylepad/releases/"><img
          src="https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white" alt="Ubunto Release" /></a>
    </div>

    <a href="https://www.producthunt.com/posts/fylepad?embed=true&utm_source=badge-featured&utm_medium=badge&utm_souce=badge-fylepad"
      target="_blank"><img
        src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=491117&theme=neutral"
        alt="fylepad - your perfect note-taking solution! | Product Hunt" style="width: 250px; height: 54px;"
        width="250" height="54" /></a>

    <div class="text-lg drop-shadow-sm">fylepad is your savior when other apps are too complex for simple tasks or too
      simple to even
      manage a basic to-do list. Designed for note-taking and Markdown-based editing, it strikes the perfect balance
      between simplicity and power.</div>



    <img src="/assets/screenshot3.png" class="rounded-xl drop-shadow-sm border-2 border-gray-100 w-[800px]">

    <img src="/assets/screenshot2.png" class="rounded-xl drop-shadow-sm border-2 border-gray-100 w-[800px]">

    <img src="/assets/screenshot1.png" class="rounded-xl drop-shadow-sm border-2 border-gray-100 w-[800px]">

    <div class="text-xl mt-8 drop-shadow-sm space-x-2"><span>Built With</span> <img
        src="https://img.shields.io/badge/Nuxt.js-ffffff?logo=nuxt&logoColor=#00DC82" alt="Nuxt js icon"
        class="w-[80px] inline" /> <img src="https://img.shields.io/badge/Tauri-24C8D8?logo=tauri&logoColor=fff"
        alt="Tauri icon" class="w-[70px] inline" /><img
        src="https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC.svg?logo=tailwind-css&logoColor=white"
        alt="Tauri icon" class="w-[120px] inline" /></div>


    <div class="text-lg">
      <div class="space-y-4">
        <div class="text-2xl drop-shadow-sm">Features</div>
        <ol class="list-[upper-roman] pl-6 space-y-2">
          <li>Create and edit notes with full Markdown
            support. From
            simple lists to advanced formatting. Change the colors & fonts as well.</li>
          <li>Close the app anytime without worrying about losing progress. It
            remembers your work and restores it the next time you open the app.</li>
          <li>Seamlessly export your notes to PDF or Markdown and import .md files
            back.</li>
          <li>Open and work on multiple notes simultaneously with our tab-based interface.</li>
          <li>At just 5MB, it is a compact powerhouse that won't bloat your system. Powered by a Rust
            core, it is fast, secure, and memory-efficient. No bulky Chromium browser under the hood here!</li>
        </ol>

        <div class="text-2xl drop-shadow-sm mt-8">Installation</div>
        <p class="drop-shadow-sm">Download the latest version for your platform (Windows, macOS, or Linux) from the <a
            href="https://github.com/imrofayel/fylepad/releases" class="text-blue-600 hover:underline">Release</a> page
          and follow the setup instructions.</p>

        <div class="text-2xl  drop-shadow-sm mt-8">Issues and Contributions</div>
        <p class=" drop-shadow-sm">Found a bug or have a feature request? Open an
          issue in the <a href="https://github.com/imrofayel/fylepad/issues"
            class="text-blue-600 hover:underline">Issues</a> section.
        </p>
        <p class=" drop-shadow-sm">Want to contribute? Fork the repository, make your changes, and
          submit a pull request!</p>

        <div class="text-2xl mt-8  drop-shadow-sm">License</div>
        <p class=" drop-shadow-sm">fylepad is open source and available under the <a href="LICENSE"
            class="text-blue-600 hover:underline">MIT
            License</a>.</p>
      </div>
    </div>

    <div class="flex py-3 sm:flex-row items-center flex-col sm:space-x-3 sm:space-y-0 space-y-4 ">
      <div
        class="text-lg inline-block bg-[#24d86c] text-white border-transparent backdrop-blur-xl p-2 px-3 rounded-full justify-center items-center cursor-pointer roboto-mono">
        <a href="https://github.com/imrofayel/fylepad/releases/" class="roboto-mono flex space-x-1"><svg
            xmlns="http://www.w3.org/2000/svg" width="22" viewBox="0 0 24 24">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M12 5v14m7-7l-7 7l-7-7" />
          </svg><span>Download</span></a>
      </div>

      <div><a href="https://github.com/imrofayel/fylepad/">
          <svg xmlns="http://www.w3.org/2000/svg" width="36" viewBox="0 0 24 24">
            <path fill="currentColor"
              d="M12 2A10 10 0 0 0 2 12c0 4.42 2.87 8.17 6.84 9.5c.5.08.66-.23.66-.5v-1.69c-2.77.6-3.36-1.34-3.36-1.34c-.46-1.16-1.11-1.47-1.11-1.47c-.91-.62.07-.6.07-.6c1 .07 1.53 1.03 1.53 1.03c.87 1.52 2.34 1.07 2.91.83c.09-.65.35-1.09.63-1.34c-2.22-.25-4.55-1.11-4.55-4.92c0-1.11.38-2 1.03-2.71c-.1-.25-.45-1.29.1-2.64c0 0 .84-.27 2.75 1.02c.79-.22 1.65-.33 2.5-.33s1.71.11 2.5.33c1.91-1.29 2.75-1.02 2.75-1.02c.55 1.35.2 2.39.1 2.64c.65.71 1.03 1.6 1.03 2.71c0 3.82-2.34 4.66-4.57 4.91c.36.31.69.92.69 1.85V21c0 .27.16.59.67.5C19.14 20.16 22 16.42 22 12A10 10 0 0 0 12 2" />
          </svg>
        </a></div>
    </div>

    <div class="text-lg text-gray-400 pt-3">If you find fylepad useful, please consider giving us a ⭐ on GitHub! Have a
      great day!</div>

  </div>
</template>