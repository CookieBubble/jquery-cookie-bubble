# jquery-cookie-bubble

`jquery-cookie-bubble` is the easy and beautiful way to inform users that your website is using cookies. 

Demo:</br>
https://cookiebubble.netlify.com

## Getting Started

1. Install jquery-cookie-bubble

    ```
    yarn install jquery-cookie-bubble
    or
    npm i jquery-cookie-bubble 
    ```
2. Include cookieBubble.min.css somewhere in your head tag
```css
 <link href="https://unpkg.com/jquery-cookie-bubble@1.0.0/dist/cookieBubble.min.css"/>
```
3. Include cookieBubble.min.js at the bottom of your body tag

```js
<script src="https://unpkg.com/jquery-cookie-bubble@1.0.0/dist/cookieBubble.min.js"/>

```

4. Usage
```js
<script>
   (function($) {
      $.cookieBubble({
         messageText:"My custom message",
         iconVisibility:false
         ...
      });
  })(jQuery);
</script>
```
## Versioning
The `jquery-cookie-bubble` library follows [Semantic Versioning](https://semver.org/). </br>
`[MAJOR].[MINOR].[PATCH]` 

## Support
If you encounter an issue or want to request a feature, you can [create an issue](https://github.com/CookieBubble/jquery-cookie-bubble/issues/new).

## Similar Projects
- [jQuery implementation of cookieBubble](https://github.com/CookieBubble/jquery-cookie-bubble)  ✅
- [React implementation of cookieBubble](https://github.com/CookieBubble/react-cookie-bubble)  ✅
</br>soon:</br>
- [Vanilla implementation of cookieBubble](https://github.com/CookieBubble/vanilla-cookie-bubble)  🔜
- [Vue implementation of cookieBubble](https://github.com/CookieBubble/vue-cookie-bubble) 🔜
