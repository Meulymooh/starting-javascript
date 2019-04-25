https://meulymooh.github.io/starting-javascript/index.html

## Part 1

Duration: 0.5 day.

What I learned:
- Keyup event: https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_onkeyup_addeventlistener

## Part 2

Duration: 1 day.

What I learned:
- Add new row: https://www.w3schools.com/jsref/met_table_insertrow.asp
- Delete row: https://www.w3schools.com/jsref/met_table_deleterow.asp
- KeyboardEvent / keyCode Property: https://www.w3schools.com/jsref/event_key_keycode.asp

## Part 3

Duration: 1 day.

What I learned:
- Remove (text, element...): https://www.w3schools.com/jsref/met_node_removechild.asp
- Create list from array: https://memorynotfound.com/dynamically-addremove-items-list-javascript/
- Add input in separate block below the list: https://gomakethings.com/how-to-insert-an-element-after-another-one-in-the-dom-with-vanilla-javascript/
- Click out of the input => blur() method : https://www.w3schools.com/jsref/met_html_blur.asp

Remarks:
- First try: I cheated big time. Instead of "updating" the list, I actually "recreated" it with the extra ingredient in it. My list was created after I read about "Looping Array Elements" (https://www.w3schools.com/js/js_arrays.asp), but I didn't manage to find a clean way to update the list. 
- Second try: after a little bit of guidance in terms of where to look for information, I rewrote my functions "createList" and  "updateList". I also added "removeInput" (it was still there at first try).

## Part 4

What I learned:
- Filter/search list: https://www.w3schools.com/howto/howto_js_filter_table.asp (filter only first column) and https://www.experts-exchange.com/questions/29130021/JavaScript-to-Make-a-Custom-Search-for-All-Columns-in-a-Table.html (filter all columns)
- Create and add checkbox: 
- Prechecked checkbox: https://www.w3schools.com/jsref/prop_checkbox_checked.asp
- Change event: https://developer.mozilla.org/fr/docs/Web/Events/change

Remarks:
Filtering the table and adding checkboxes was relatively ok but I had a hard time making columns disappear when the boxes were unchecked. I needed some guidance and explanation. It was also very hard to find info with pure javascript. For this kind of things, almost everyone uses jquery.

## Part 5

What I learned:
- Transition: https://www.w3schools.com/jsref/prop_style_transition.asp
- Transform: https://www.w3schools.com/jsref/prop_style_transform.asp
- Timeout (for duration): https://www.w3schools.com/js/js_timing.asp
- Set interval (for repetition): https://www.w3schools.com/jsref/met_win_setinterval.asp
- Load event: https://www.w3schools.com/jsref/event_onload.asp

Remarks:
Maybe the easiest part of the exercise. Like a breath of fresh air after struggling a lot before!

## Part 6

What I learned:
- Mousemove event: https://www.w3schools.com/jsref/event_onmousemove.asp
- Clientx: https://www.w3schools.com/jsref/event_clientx.asp

Remarks:
After trying a hundred things with long and complicated code, I just add styling + clientx. I didn't manage to stop the block following the cursor out of the parent div, though. I cheated (a little) because I'm just increasing the left margin of the moving block... But it works well. :-)

## Part 7

What I learned:
- Sliders: https://www.w3schools.com/howto/howto_js_rangeslider.asp
- Change event: https://www.w3schools.com/jsref/event_onchange.asp
- Focus event: https://www.w3schools.com/jsref/event_onfocus.asp

Remarks:
Most of the exercise was relatively easy, except for three things: 
- My slider didn't show the "A" letter immediately and I had to set it (looks a bit like a hack, though).
- It took me a long while to figure out how to add a new letter in the input field. At first every new slider was only changing the first and only letter in the input field, not adding a new one.
- At some point, every time I moved the slider, it added a new letter in the main input field. I couldn't change the letter, just add a new one.

## Part 8

What I learned:
- ReplaceWith() (even though it didn't work): https://usefulangle.com/post/82/pure-javascript-replace-element
- Call a function inside another function: https://stackoverflow.com/questions/4524877/how-do-i-call-a-function-inside-of-another-function/4524890

Remarks:
- I tried clone() and replaceWith() => no success.
- I got help from Madelina who explained me that I had to make a whole function out of part 7 and call it again in part 8. Same concept is explained in Stakoverflow message indicated above.