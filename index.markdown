---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<!-- Background Container with dark theme -->
<div class="has-background-black has-text-white is-flex is-flex-direction-column justify-content-space-between" style="min-height: 100vh; overflow-x: hidden;">

  <!-- Navbar -->
  <nav class="navbar is-transparent py-4 px-5" role="navigation" aria-label="main navigation" style="background: transparent;">
    <div class="container is-fluid">
      <div class="navbar-brand">
        <!-- Logo on the left -->
        <a class="navbar-item has-text-white has-text-weight-bold is-size-5 is-uppercase tracking-wider" href="{{ '/' | relative_url }}">
          Naomi Chan
        </a>
      </div>
      
      <!-- Right aligned links -->
      <div class="navbar-end">
        <div class="navbar-items is-flex" style="gap: 1.5rem; align-items: center;">
          <a class="has-text-white is-uppercase is-size-6 tracking-wider hover-fade" href="{{ '/about/' | relative_url }}">
            About
          </a>
          <a class="has-text-white is-uppercase is-size-6 tracking-wider hover-fade" href="{{ '/projects/' | relative_url }}">
            Projects
          </a>
        </div>
      </div>
    </div>
  </nav>

  <!-- Big Name & Intro (Top Section grid) -->
  <header class="section py-6 px-5" style="flex-grow: 1;">
    <div class="container is-fluid">
      <div class="columns is-multiline">
        <!-- Big Name / Logo mark (brutalist, massive screen-filling text) -->
        <div class="column is-12 mb-6">
          <h1 class="title is-uppercase has-text-white has-text-weight-black tracking-tighter" 
              style="font-size: clamp(4rem, 15vw, 18rem); line-height: 0.8; margin-left: -0.05em;">
            NAOMI
          </h1>
        </div>

        <!-- Big Description & Metadata Column Grid -->
        <div class="column is-12">
          <div class="columns is-variable is-8">
            <!-- Big Description -->
            <div class="column is-6">
              <p class="is-size-3 is-size-4-mobile has-text-weight-light leading-snug" style="max-width: 600px;">
                CREATIVE TECHNOLOGIST &amp; DIGITAL ARTIST.<br>
                Crafting immersive experiences at the intersection of code, design, and interactive media.
              </p>
            </div>
            
            <!-- Context / Quick Metadata in tiny typography, similar to the photo -->
            <div class="column is-3 is-offset-1">
              <div class="content is-size-7 is-uppercase tracking-wide has-text-grey-light">
                <p class="has-text-white has-text-weight-semibold mb-1">Focus</p>
                <p class="mb-0">Creative Coding</p>
                <p class="mb-0">Web Development</p>
                <p class="mb-0">Generative Design</p>
              </div>
            </div>

            <!-- More tiny meta data -->
            <div class="column is-2">
              <div class="content is-size-7 is-uppercase tracking-wide has-text-grey-light">
                <p class="has-text-white has-text-weight-semibold mb-1">Location</p>
                <p>Seattle, WA <br> 47.6062° N, 122.3321° W</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>

  <!-- Huge Video / Interactive Visual "Big Space" (100vh / 100vw) -->
  <section class="video-container" style="position: relative; width: 100vw; height: 100vh; overflow: hidden; background-color: #0d0d0d;">
    <!-- Tiny label over the video, brutalist placement -->
    <div style="position: absolute; top: 2rem; left: 2rem; z-index: 10; font-family: monospace;" class="is-size-7 is-uppercase tracking-wider">
      [01] Interactive canvas / Background environment
    </div>

    <!-- Replace with your <video> or <iframe> once you are ready. Below is a placeholder aesthetic -->
    <div style="width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; border-top: 1px solid #333; border-bottom: 1px solid #333;">
      <!-- Interactive Visual / Video Placeholder: This can be a 3D Canvas, video player, etc. -->
      <div class="has-text-grey is-size-4 is-uppercase tracking-widest has-text-centered px-4">
        [ Video / Generative Art Placeholder goes here ]
        <p class="is-size-7 has-text-grey-light mt-2">( 100vh / 100vw Fullscreen Area )</p>
      </div>
    </div>
  </section>

  <!-- Minimal Footer -->
  <footer class="footer has-background-black has-text-grey-light py-5 px-5" style="border-top: 1px solid #1a1a1a;">
    <div class="container is-fluid">
      <div class="columns is-vcentered is-mobile is-multiline">
        <div class="column is-6-tablet is-12-mobile mb-3-mobile">
          <p class="is-size-7 is-uppercase tracking-wider">
            &copy; {{ site.time | date: "%Y" }} NAOMI CHAN. All rights reserved.
          </p>
        </div>
        <div class="column is-6-tablet is-12-mobile has-text-right-tablet">
          <p class="is-size-7 is-uppercase tracking-wider">
            Built with Jekyll &amp; Bulma
          </p>
        </div>
      </div>
    </div>
  </footer>

</div>