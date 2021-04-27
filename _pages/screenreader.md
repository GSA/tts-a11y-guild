---
layout: page
title: Screenreader Demo Page 
permalink: /screenreader/
layout: post
---

Welcome to using a screen reader to access a website! The contents after this paragraph are visually hidden and are available when using a screen reader with your browser. No peeking!

<div class="usa-sr-only" markdown="1">

As you have probably figured out, this page can only be read by using a screen reader (or by reading the source code).

Quora user Nick Steele estimated that [about 4.4 million people in the USA use a screen reader](https://ux.stackexchange.com/a/119596). If you’re interested in a more detailed breakdown of peoples’ preferences, [WebAIM surveyed 1465 screen reader users](https://webaim.org/projects/screenreadersurvey5/) about their use of screen readers. If you’re feeling brave, try using your screen reader to read both of the pages linked previously.

Now that you’ve done some reading, let’s try filling out a form using your screen reader! The form doesn't actually send or store any data, but it should work with your screen reader to show what the experience is like. 

<h2>Screen Reader Demo Form - It doesn't submit anything.</h2>
<p>The form is for your practice with a screen reader only.</p>
  <form action="">
    <input name="Name" type="text" aria-label="name" id="name">
    <input name="Email address" type="text" aria-label="email" id="email">
    <select name="Favorite color" aria-label="What’s your favorite color?" id="color">
      <option value="red">Red</option>
      <option value="orange">Orange</option>
      <option value="yellow">Yellow</option>
      <option value="green">Green</option>
      <option value="blue">Blue</option>
      <option value="purple">Purple</option>
    </select>
    <textarea name="What’s your favorite movie and why?" id="movie"></textarea> 
    <button type="button" onclick="alert('Thanks for filling out this form! It doesn’t send any data.')">Submit</button>
  </form>
</div>
