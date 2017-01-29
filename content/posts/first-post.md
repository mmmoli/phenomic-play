---
title: First Post, no hero.
date: 2016-01-22
layout: Post
---

This is the first post!

Code is highlighted by default.

```js
const StatelessComponent = (props) => {
  return (
    <div>
      I‘m a stateless component that accepts children
      { props.children }
    </div>
  )
}

// ...

  return (
    <StatelessComponent>
      Example of child
    </StatelessComponent>
  )
```
## Some cool html

<form name="contact" netlify netlify-honeypot="bot-field">
  <p><label>Email: <input name="email"></label></p>
  <p class="hidden"><label>Bot field: <input name="bot-field"></label></p>
  <p><label>Message: <textarea name="message"></textarea></label></p>
  <p><button>Send</button></p>
</form>

