# y2s19-js-meetx

## 0 &ensp; Getting Started

1. **Fork** this repository by clicking "Fork" on this page: `https://github.com/meet-projects/y2s19-js-meetx`.
2. In **Terminal**, change directory onto your Desktop:
   `cd ~/Desktop`
3. **Clone** the repository `y2s19-js-meetx` onto your Desktop, replacing `<username>` with your Github username in the following command:
   - `$ git clone https://github.com/<username>/y2s19-js-meetx`.

## 1 &ensp; JavaScript Labs

### 1.1 &ensp; Variables, Numbers, and Strings (`./vars`)

0. Make sure you are in the **`~/Desktop/y2s19-intro-js`** directory. Open `vars.html` in Sublime Text (or any other text editor). Write all of your code in between the `<script></script>` tags.
1. Use `prompt` to ask the user for the year they were born. Store this value as a Number using `parseInt` in a variable called `birthYear`.
1. Ask the user for their lucky number. Store this value as a Number using `parseInt` in a variable called `luckyNumber`.
1. Create two `String` type variables called `favFruit` and `favSubject`. `favFruit` should contain your favorite fruit, and `favSubject` should contain your favorite subject.
1. Answer the following questions:
   1. What is the remainder when `birthYear` is divided by `luckyNumber`?
   2. What is the value of `birthYear + luckyNumber`?
   3. What is the value of `birthYear + favSubject`?
   4. What is the value of `favFruit + birthYear + luckyNumber`?
   5. What is the value of `birthYear + luckyNumber + favSubject`?

**Not sure what to do?** Try Googling for the following terms:
`javascript string to int`, `javascript variables`, `javascript order of operations`

### 1.2 &ensp; Arrays (`./arrays`)

1. Ask the user for three things that they are excited for about MEET, separated by a comma and a space: `", "`.
2. **Split** their answer into an array using and **sort** the array.
3. Finally, **join** the resulting array together with `", "` and display it on the web page with `document.write`.

**Not sure what to do?** Try Googling for the following terms:
`javascript split string`, `javascript sort array`, `javascript join array`

### 1.3 &ensp; Loops (`./loops`)

1. Let's write a guessing game! The code given to you generates a random number from 1 to 100 and stores it in a variable called `randomInt`. Using loops and conditionals, write a guessing game that does the following:
   1. Prompt the user to guess a number.
   2. If their guess is greater than `randomInt`, tell them that they guessed too high. If their guess is less than `randomInt`, tell them that they guessed to low.
   3. If they guessed correctly, congratulate them and let them know how many guesses it took them to get the right answer.

### 1.4 &ensp; Functions (`./functions`)

1. A **palindrome** is a phrase that, when only letters are kept, reads the same both forwards and backwards. For example, "Madam, I'm Adam" is a palindrome, because when only letters are kept, "madamimadam" is the same as its reverse.
2. Write a function called `isPalindrome(<word>)` that returns `true` or `false`, depending on whether or not the argument is a palindrome, using our provided `isLetter(<char>)` function. A `for` loop and learning to copy an array will be helpful too.
3. Prompt the user to input a phrase, and then output to the screen a message whether or not their input is a palindrome.

## 2 &ensp; jQuery Labs

### 2.1 &ensp; Editing DOM Styles (`./style`)

0. Make sure you are in the **`~/Desktop/y2s19-js-meetx`** directory. Open `style/style.html` in Sublime Text (or any other text editor).
1. Find out how to use CSS to rotate elements with [this W3schools article](https://www.w3schools.com/cssref/css3_pr_transform.asp).
1. Open `style.js` in Sublime Text. **Use JQuery** to change the style of the MEET logo:
   - Finish the function `updateSize`. You should set the width of the the MEET logo to equal `newSize` in pixels.
   - Finish the function `updateLeftPosition` and `updateTopPosition` functions.
1. If you finished, get checked off by a TA or instructor. Nice job!

<img src="images/style.gif">

### 2.2 &ensp; JQuery Events (`./events`)

0. Make sure you are in the **`~/Desktop/y2s19-js-meetx`** directory. Open `events/events.html` in Sublime Text (or any other text editor).
1. Open `events.html` in Sublime Text.
   - Notice that there is a button with an id of `moveButton` on the page.
   - Notice that there is a paragraph with an id of `message` on the page.
1. Open `events.css` in Sublime Text.
   - Notice that `#message` has `position: fixed`. This means that you can move the paragraph in `events.html` around easily.
1. Edit `events.js` in Sublime Text. **Using jQuery**, add code so that when `moveButton` is clicked, the `message` paragraph moves to a random place on the screen. We have provided helper functions `randomX()` and `randomY()`, which return random X and Y positions on the screen.
1. If you finished, get checked off by a TA or instructor. Nice job!

<img src="images/events.gif">

### 2.3 &ensp; Editing DOM Content (`./content`)

0. Make sure you are in the **`~/Desktop/y2s19-js-meetx`** directory. Open `content/content.html` in Sublime Text (or any other text editor).
1. Open `content.js` in Sublime Text.
1. Add code to `content.js` so that every time the "Increment" button is pressed, the counter increases by `1`.
1. Add code to `content.js` so that when the "Reset" button is pressed, the counter is reset back to `0`.
1. If you finished, get checked off by a TA or instructor. Nice job!

<img src="images/counter.gif">

### 2.4 &ensp; Editing DOM Classes (`./classes`)

0. Make sure you are in the **`~/Desktop/y2s19-js-meetx`** directory. Open `classes/classes.html` in Sublime Text (or any other text editor).
1. Using Sublime Text, **add three buttons to `classes.html`**.
   - The first button should have id of `bigButton` and with `BIG Button` written on it.
   - The second button should have id of `hideButton` and with `HIDE Button` written on it.
   - The third button should have id of `rotateButton` and with `ROTATE Button` written on it.
1. Using Sublime Text, edit `classes.css`. **Finish the `.big` CSS rule.** Any element with the class of `big` should have the following style (**use Google** if you don't know how to use any of these styles):
   - Font size of 72pt.
