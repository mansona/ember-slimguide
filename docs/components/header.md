# Global Header

Shows the side wide header with the global navigation.

```html
<header class="es-header" role="banner">
  <nav class="es-navbar " aria-label="Primary site navigation">
    <a class="navbar-brand-wrapper" href="https://www.emberjs.com">
      <img class="navbar-brand" src="/images/ember-logo.svg" alt="home" width="83" height="40">
    </a>

    <button class="navbar-toggler" aria-expanded="false" type="button">
      Show Site Navigation
    </button>

    <ul class="navbar-list">
      <li class="navbar-list-item dropdown">
        <button class="navbar-list-item-dropdown-toggle " aria-expanded="false" type="button">
          Docs
        </button>
      </li>
      <li class="navbar-list-item dropdown">
        <button class="navbar-list-item-dropdown-toggle " aria-expanded="false" type="button">
          Releases
        </button>
      </li>
      <li class="navbar-list-item ">
        <a class="navbar-list-item-link" href="https://blog.emberjs.com">
          Blog
        </a>
      </li>
      <li class="navbar-list-item dropdown">
        <button class="navbar-list-item-dropdown-toggle " aria-expanded="false" type="button">
          Community
        </button>
      </li>
      <li class="navbar-list-item dropdown">
        <button class="navbar-list-item-dropdown-toggle " aria-expanded="false" type="button">
          About
        </button>
      </li>
    </ul>

  </nav>
</header>
```
