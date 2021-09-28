# Card

A card component that serves as a content container for images, text and links. When used within grid layouts cards are expected to share the same content structure and matching height. For accessibility reasons cards should always be implemented as lists, and for this reason the `<EsCard>` component's root element is a `<li>` so it should always be wrapped in a `<ul>`.

Here is an example of a card

```html
<ul class="list-unstyled layout">
  <li class="card  lg:col-2">
    <div class="card__content">
      This is a card
    </div>
  </li>
</ul>
```

You can also add an image to the card using the `@image` parameter:

```html
<ul class="list-unstyled layout">
  <li class="card card--image lg:col-2">
    <img class="card__image" src="/images/ember-logo.png" alt="" role="presentation">
    <div class="card__content">
      This is a card
    </div>
  </li>
</ul>
```

Here is a fuller example of a card that has more structure in the card body

```html
<ul class="list-unstyled layout">
  <li class="card card--image lg:col-2">
    <img class="card__image" src="/images/ember-logo.png" alt="" role="presentation">
    <div class="card__content">
      <h3>Ember.js</h3>
      <p>A framework for ambitious web developers. Try it out!</p>
      <div class="flex-horizontal-between">
        <div><a href="#">Visit Website</a></div>
        <div class="text-sm text-muted">COPYRIGHT 2019 TILDE INC.</div>
      </div>
    </div>
  </li>
</ul>
```
