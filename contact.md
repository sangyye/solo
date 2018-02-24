---
layout: default
permalink: /contact/
---
<form name="contact" netlify>
  <p>
    <label>Your Name: <input type="text" name="name"></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email"></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

Back to [site]({{ "/" | prepend: site.github.url }})
