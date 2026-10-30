# AI Usage Record

Follow the class AI-use policy. If you did not use AI, write that below.

## AI use or no AI use

used twice

## Prompts used

"look at lines 110 and everything below, they have red swigglies, what line is the main issue"

## Suggestions or code used

"The red squiggles are likely coming from a syntax issue or a mismatch between the code and your editor. I’ll keep the original comments and helper functions and only fix what’s needed."

## Changes I made and what I understand

"The specific issue was most likely the request.onerror line.

In the original version, it was:
request.onerror = showLoadError;

That line is actually valid JavaScript, so it wasn't necessarily the cause of the red squiggles. I changed it to:
request.onerror = function () {
  showLoadError();
};

Both versions work the same way."



I learned that is wasn't a typo, it was just two different way of doing something not working with a certain line, both were typed correctly but not linked properly. 


