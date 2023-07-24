<script>
  /** @type {import('./$types').PageData} */
  export let data;

  // .tailwindConfig.theme.extends.colors = {};
</script>

<!-- HERO SECTION -->
<body>
  <section id="hero">
    <div class="section-container mb-40 pt-16">
      <img src="logo.svg" alt="" class="mx-auto my-16" />
      <!-- This is gonna be repeated alot potentially default styleing diretives -->
      <h3 class="clip-h3">A history of everything you copy</h3>

      <p
        class="max-w-3xl mx-auto mb-10 text-2xl text-grayishBlue font-clipSans"
      >
        Clipboard allows you to track and organize everything you copy.
        Instantly access your clipboard on all your devices.
      </p>
      <!-- Button Container -->
      <div
        class="flex flex-col justify-center w-full space-y-6 text-xl text-white md:flex-row md:space-y-0 md:space-x-4"
      >
        <a href="#" class=" bg-strongCyan clip-button-container"
          >Download For iOS
        </a>
        <a href="#" class="bg-lightBlue clip-button-container">
          Download For Mac
        </a>
      </div>
    </div>
  </section>
  <!-- Snippets Section -->
  <section id="snippets">
    <div class="section-container my-20">
      <h3 class="clip-h3">Keep track of your snippets</h3>
      <p
        class="max-w-3xl mx-auto mb-24 text-xl leading-9 text-center text-grayishBlue font-clipSans"
      >
        Clipboard instantly stores any item you copy in the cloud, meaning you
        can access your snippets immediately on all your devices. Our Mac and
        iOS apps will help you organize everything.
      </p>
    </div>
  </section>

  <!-- Feature Section -->
  <section id="features">
    <div class="section-container my-20">
      <div class="relative flex flex-col md:flex-row md:space-x-32">
        <!-- IMG -->
        <div class="md:w-1/2">
          <img
            src="image-computer.png"
            alt=""
            class="md:absolute top-0 right-[50%]"
          />
        </div>
        <!-- Items Container -->
        <div
          class="flex flex-col mt-16 mb-24 space-y-12 text-xl
							md:w-1/2 md:mb-60 md:text-left md:pl-16"
        >
          <!-- Item 1 -->
          <div class="">
            <h5 class="mb-2 text-2xl font-bold text-darkGrayishBlue">
              Quick Search
            </h5>
            <p class="max-w-md text-grayishBlue font-clipSans">
              Easily search your snippets by content, category, web
              address,application and more.
            </p>
          </div>
          <!-- Item 2 -->
          <div class="">
            <h5 class="mb-2 text-2xl font-bold text-darkGrayishBlue">
              iCloud Sync
            </h5>
            <p class="max-w-md text-grayishBlue font-clipSans">
              Instantly saves and syncs snippets across all your devices.
            </p>
          </div>
          <!-- Item 3 -->
          <div class="">
            <h5 class="mb-2 text-2xl font-bold text-darkGrayishBlue">
              Completely History
            </h5>
            <p class="max-w-md text-grayishBlue font-clipSans">
              Retreive any snippets from the first moment you started using the
              app
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Access ANywhere Section -->
  <section id="access">
    <div class="section-container my-20">
      <h3 class="clip-h3">Access Clipboard Anywhere</h3>
      <p
        class="max-w-3xl mx-auto mb-24 text-xl leading-9 text-center text-grayishBlue"
      >
        Whether you're on the go, or at your computer, you can access all your
        Clipboard snippets in a few simple clicks.
      </p>
      <img src="image-devices.png" alt="" class="mx-auto" />
    </div>
  </section>

  <!-- SuperCharge Sectionj  -->
  <section id="supercharge">
    <div class="section-container my-20">
      <h3 class="clip-h3">Supercharge your workflow</h3>
      <p
        class="max-w-3xl mx-auto mb-16 text-xl leading-9 text-center text-grayishBlue font-clipSans"
      >
        We've got the tools to boost your productivity.
      </p>
      <!-- ITEMS CONTAINER  -->
      <div
        class="flex flex-col items-center justify-between space-y-16
						md:flex-row md:space-y-0 md:space-x-12"
      >
        <!-- Item 1 -->
        <div class="flex flex-col items-center space-y-5 font-clipSans">
          <img src="icon-blacklist.svg" alt="" class="mb-6" />
          <h5 class="mb-2 text-2xl font-bold text-darkGrayishBlue">
            Create Blacklists
          </h5>

          <p class="max-w-md text-grayishBlue font-clipSans">
            Ensure sensitive information never makes its way to your clipboard
            by excluding certain sources.
          </p>
        </div>
        <!-- Item 2 -->
        <div class="flex flex-col items-center space-y-5 font-clipSans">
          <img src="icon-text.svg" alt="" class="mb-6" />
          <h5
            class="mb-2 text-2xl font-bold text-darkGrayishBlue font-clipSans"
          >
            Plain Text Snippets
          </h5>

          <p class="max-w-md text-grayishBlue">
            Remove unwanted formatting from copied text for a consistent look.
          </p>
        </div>
        <!-- Item 3 -->
        <div class="flex flex-col items-center space-y-5 font-clipSans">
          <img src="icon-preview.svg" alt="" class="mb-6" />
          <h5
            class="mb-2 text-2xl font-bold text-darkGrayishBlue font-clipSans"
          >
            Sneak Preview
          </h5>

          <p class="max-w-md text-grayishBlue">
            Quick preview of all snippets on your Clipboard for easy access.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Rereferences Section -->
  <section id="references">
    <div
      class="flex flex-col items-center justify-between
					max-w-6xl px-10 mx-auto space-y-16 my-44
					md:flex-row md:space-y-0"
    >
      <img src="logo-google.png" alt="" />
      <img src="logo-ibm.png" alt="" />
      <img src="logo-microsoft.png" alt="" />
      <img src="logo-hp.png" alt="" />
      <img src="logo-vector-graphics.png" alt="" />
    </div>
  </section>

  <!-- Bottom CTA SECTION -->
  <section id="bottom">
    <div class="section-container my-20">
      <h3 class="clip-h3">Clipboard for iOS and Mac OS</h3>
      <p class="max-w-md mx-auto text-grayishBlue font-clipSans mb-10">
        Available for free on the App Store. Download for Mac or iOS, sync with
        iCloud and you're ready to start adding to your clipboard.
      </p>
      <!-- Button Container -->
      <div
        class="flex flex-col justify-center w-full space-y-6 text-xl text-white md:flex-row md:space-y-0 md:space-x-4"
      >
        <a href="#" class=" bg-strongCyan clip-button-container"
          >Download For iOS
        </a>
        <a href="#" class="bg-lightBlue clip-button-container">
          Download For Mac
        </a>
      </div>
    </div>
  </section>

  <footer class="bg-gray-50">
    <div class="section-container">
      <div class="flex flex-col items-center justify-between md:flex-row">
        <!-- Image -->
        <img src="logo.svg" alt="" class="scale-50" />
        <!-- Container for Menus & Social -->
        <div
          class="flex flex-col justify-between flex-1 mb-10 space-y-6
							md:mb-0 md:space-y-0 text-grayishBlue font-clipSans"
        >
          <!-- Meunus -->
          <div
            class="flex flex-col space-y-4 md:flex-row md:ml-24 md:space-x-24 md:space-y-0"
          >
            <!-- MENU 1 -->
            <div class="flex flex-col space-y-4 text-center md:text-left">
              <div class="">
                <a href="" class="hover:text-strongCyan">FAQs</a>
              </div>
              <div class="">
                <a href="" class="hover:text-strongCyan">Contact Us </a>
              </div>
            </div>
            <!-- MENU 2 -->
            <div class="flex flex-col space-y-4 text-center md:text-left">
              <div class="">
                <a href="" class="hover:text-strongCyan">Privacy Policy</a>
              </div>
              <div class="">
                <a href="" class="hover:text-strongCyan">Press Kit </a>
              </div>
            </div>
            <!-- MENU 3 -->
            <div class="flex flex-col space-y-4 text-center md:text-left">
              <div class="">
                <a href="" class="hover:text-strongCyan">Install guide </a>
              </div>
            </div>
          </div>

          <!-- Social Icons-->
        </div>
        <div class="flex justify-between w-32 py-1 mb-2 md:mb-0">
          <a href="">
            <img src="icon-facebook.svg" alt="" class="duration-200 ficon" />
          </a>
          <a href="">
            <img src="icon-twitter.svg" alt="" class="duration-200 ficon" />
          </a>
          <a href="">
            <img src="icon-instagram.svg" alt="" class="duration-200 ficon" />
          </a>
        </div>
      </div>
    </div>
  </footer>
</body>

<style>
  body {
    background-image: url("bg-header-desktop.png");
    background-repeat: no-repeat;
    background-size: contain;
  }
  @media (max-width: 576px) {
    body {
      background-image: url("bg-header-mobile.png");
    }
  }
  .ficon:hover {
    filter: invert(53%) sepia(68%) saturate(434%) hue-rotate(121deg)
      brightness(101%) contrast(94%);
  }
</style>
