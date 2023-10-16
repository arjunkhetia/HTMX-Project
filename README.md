# HTMX Project

HTMX is a library that allows user to access modern browser features directly from HTML, rather than using javascript. HTMX is a dependency-free, browser-oriented javascript library. This means that using it is as simple as adding a <script> tag to our document head. No need for complicated build steps or systems.

```html
<button class="btn btn-primary" hx-get="http://localhost:3000/users" hx-swap="outerHTML">
  Get API Demo
</button>
```
