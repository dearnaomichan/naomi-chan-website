---
layout: default
title: Style Guide
permalink: /styleguide/
---

<section class="section">
  <div class="container">

    <!-- Header -->
    <div class="mb-6 pb-4" style="border-bottom: 1px solid var(--bulma-border);">
      <p class="is-size-7 is-uppercase has-text-weight-semibold has-text-grey">Design System Reference</p>
      <h1 class="title is-1">Bulma Style Guide</h1>
      <p class="subtitle is-5">Live preview of typography, colors, buttons, forms, and UI components.</p>
    </div>

    <!-- 1. Brand & Semantic Colors -->
    <div class="mb-6">
      <h2 class="title is-4">01. Colors</h2>
      <div class="columns is-multiline">
        <div class="column is-3">
          <div class="box has-background-primary has-text-primary-invert">
            <p class="has-text-weight-bold">Primary</p>
            <p class="is-size-7"><code>$primary</code> / <code>.is-primary</code></p>
          </div>
        </div>
        <div class="column is-3">
          <div class="box has-background-link has-text-link-invert">
            <p class="has-text-weight-bold">Link</p>
            <p class="is-size-7"><code>$link</code> / <code>.is-link</code></p>
          </div>
        </div>
        <div class="column is-3">
          <div class="box has-background-info has-text-info-invert">
            <p class="has-text-weight-bold">Info</p>
            <p class="is-size-7"><code>$info</code> / <code>.is-info</code></p>
          </div>
        </div>
        <div class="column is-3">
          <div class="box has-background-success has-text-success-invert">
            <p class="has-text-weight-bold">Success</p>
            <p class="is-size-7"><code>$success</code> / <code>.is-success</code></p>
          </div>
        </div>
        <div class="column is-3">
          <div class="box has-background-warning has-text-warning-invert">
            <p class="has-text-weight-bold">Warning</p>
            <p class="is-size-7"><code>$warning</code> / <code>.is-warning</code></p>
          </div>
        </div>
        <div class="column is-3">
          <div class="box has-background-danger has-text-danger-invert">
            <p class="has-text-weight-bold">Danger</p>
            <p class="is-size-7"><code>$danger</code> / <code>.is-danger</code></p>
          </div>
        </div>
        <div class="column is-3">
          <div class="box has-background-dark has-text-light">
            <p class="has-text-weight-bold">Dark</p>
            <p class="is-size-7"><code>$dark</code> / <code>.is-dark</code></p>
          </div>
        </div>
        <div class="column is-3">
          <div class="box has-background-light has-text-dark">
            <p class="has-text-weight-bold">Light</p>
            <p class="is-size-7"><code>$light</code> / <code>.is-light</code></p>
          </div>
        </div>
      </div>
    </div>

    <hr>

    <!-- 2. Typography Scale -->
    <div class="mb-6">
      <h2 class="title is-4">02. Typography Scale</h2>
      <div class="columns">
        <div class="column is-7">
          <p class="title is-1">Title 1 (<code>$size-1</code>)</p>
          <p class="title is-2">Title 2 (<code>$size-2</code>)</p>
          <p class="title is-3">Title 3 (<code>$size-3</code>)</p>
          <p class="title is-4">Title 4 (<code>$size-4</code>)</p>
          <p class="title is-5">Title 5 (<code>$size-5</code>)</p>
          <p class="title is-6">Title 6 (<code>$size-6</code>)</p>
        </div>
        <div class="column is-5">
          <div class="content">
            <p class="is-size-4">Lead body copy (<code>.is-size-4</code>)</p>
            <p>Standard body paragraph text testing <code>$family-primary</code>, line height, and <a href="#typography">inline link color</a> styling.</p>
            <p class="is-size-7 has-text-grey">Small caption or metadata text (<code>.is-size-7</code>)</p>
            <blockquote>Blockquote styling preview for editorial callouts and notes.</blockquote>
            <p>Inline <code>code snippet</code> inside text.</p>
          </div>
        </div>
      </div>
    </div>

    <hr>

    <!-- 3. Buttons & Tags -->
    <div class="mb-6">
      <h2 class="title is-4">03. Buttons &amp; Tags</h2>
      
      <p class="is-size-7 is-uppercase has-text-weight-semibold mb-2">Solid Buttons</p>
      <div class="buttons mb-4">
        <button class="button">Default</button>
        <button class="button is-primary">Primary</button>
        <button class="button is-link">Link</button>
        <button class="button is-info">Info</button>
        <button class="button is-success">Success</button>
        <button class="button is-warning">Warning</button>
        <button class="button is-danger">Danger</button>
        <button class="button is-dark">Dark</button>
      </div>

      <p class="is-size-7 is-uppercase has-text-weight-semibold mb-2">Outlined &amp; Sizes</p>
      <div class="buttons mb-4">
        <button class="button is-primary is-outlined">Primary Outlined</button>
        <button class="button is-link is-outlined">Link Outlined</button>
        <button class="button is-primary is-light">Primary Light</button>
        <button class="button is-primary is-small">Small</button>
        <button class="button is-primary is-medium">Medium</button>
        <button class="button is-primary is-large">Large</button>
      </div>

      <p class="is-size-7 is-uppercase has-text-weight-semibold mb-2">Tags</p>
      <div class="tags">
        <span class="tag">Default</span>
        <span class="tag is-primary">Primary</span>
        <span class="tag is-link">Link</span>
        <span class="tag is-info is-light">Info Light</span>
        <span class="tag is-dark">Dark</span>
        <span class="tag is-rounded is-primary">Rounded Tag</span>
      </div>
    </div>

    <hr>

    <!-- 4. Cards, Boxes & Notifications -->
    <div class="mb-6">
      <h2 class="title is-4">04. Containers, Cards &amp; Notifications</h2>
      <div class="columns">
        <div class="column is-4">
          <div class="card">
            <div class="card-content">
              <p class="title is-5">Card Component</p>
              <p class="subtitle is-6">Testing <code>$card-radius</code> &amp; shadows</p>
              <div class="content">
                Used for project grids and case study previews.
              </div>
            </div>
            <footer class="card-footer">
              <a href="#" class="card-footer-item">View Project</a>
              <a href="#" class="card-footer-item">Source</a>
            </footer>
          </div>
        </div>

        <div class="column is-4">
          <div class="box">
            <p class="title is-5">Box Container</p>
            <p>Tests <code>$box-padding</code>, <code>$box-radius</code>, and background surface contrast.</p>
          </div>
        </div>

        <div class="column is-4">
          <div class="notification is-primary">
            <strong>Primary Notification:</strong> Tests contrast between primary fill and inverted text.
          </div>
          <div class="notification is-light">
            <strong>Light Notification:</strong> Subtle callout banner styling.
          </div>
        </div>
      </div>
    </div>

    <hr>

    <!-- 5. Form Controls -->
    <div class="mb-6">
      <h2 class="title is-4">05. Form Controls</h2>
      <div class="columns">
        <div class="column is-6">
          <div class="field">
            <label class="label">Text Input (<code>$input-radius</code> / focus ring)</label>
            <div class="control">
              <input class="input" type="text" placeholder="Standard input field">
            </div>
          </div>

          <div class="field">
            <label class="label">Primary Border Input</label>
            <div class="control">
              <input class="input is-primary" type="text" value="Active / Primary state">
            </div>
          </div>

          <div class="field">
            <label class="label">Select Dropdown</label>
            <div class="control">
              <div class="select is-fullwidth">
                <select>
                  <option>Option One</option>
                  <option>Option Two</option>
                </select>
              </div>
            </div>
          </div>
        </div>

        <div class="column is-6">
          <div class="field">
            <label class="label">Textarea</label>
            <div class="control">
              <textarea class="textarea" rows="3" placeholder="Message body..."></textarea>
            </div>
          </div>

          <div class="field">
            <div class="control">
              <label class="checkbox mr-4">
                <input type="checkbox" checked> Checkbox option
              </label>
              <label class="radio">
                <input type="radio" name="sample" checked> Radio option
              </label>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</section>