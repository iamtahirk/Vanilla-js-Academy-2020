## Project Day 07: Character Counter
[Go Make Things](https://gomakethings.com/)

In today’s project, we’re going to update the UI to display a live character count as a user types in a textarea field.


####The Template
The template has a textarea with an ID of #text, and an accompanying label.

The paragraph below it includes a span with an ID of #character-count. It’s set to 0 by default.

As the user types or pastes text into the #text field, the #character-count content should get updated in real time to display how many characters are in the field.


```html
<label for="text">Enter your text below.</label>
<textarea id="text"></textarea>

<p>You've written <strong><span id="character-count">0</span> characters</strong>.</p>
```