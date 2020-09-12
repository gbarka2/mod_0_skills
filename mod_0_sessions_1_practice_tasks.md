# Session 1 Practice Tasks

The assignments listed here should take you approximately 60 minutes.

To start this assignment, click the button in the upper right-hand corner that says **Fork**. This is now your copy of the document. Click the **Edit** button when you're ready to start adding your answers. To save your work, click the green button in the bottom right-hand corner. You can always come back and re-edit your gist.

### 1. Markdown (20 min)
Markdown is the format all of your homework gists are written in.

Using [this markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), create a new gist of your own by clicking the `New Gist` button in the upper right-hand corner of the screen. Create a "Beginners Guide to data types" documenting your data types knowledge so far using Markdown.

**NOTE:** Remember to add a .md file extension to filename of your new Gist. Otherwise it will not register as markdown.

Incorporate each of the following features into your Gist:

- at least two headings of different sizes
- at least one numbered list
- at least one bullet point list
- at least one bold word/phrase
- at least one italic word/phrase
- at least one code block
- at least one inline code block (greyed text)
- at least one image

- [ ] Paste the link to your gist here: [Gary's Link] (https://gist.github.com/gbarka2/060014ac77e32b74337cb0cadc986cc1)

### 2. Documentation and Googling (20 min)

Documentation of a language, framework, or tool is the information that describes its functionality. For this part of the practice tasks, you're going to practice digging into documentation and other reference material.

**NOTE:** Remember to look for the docs! **mdn** for javascript and **ruby-doc** for ruby.

- [ ] In your own words, what does the JavaScript/Ruby string split method do (pick based on your program)? As you're explaining, be sure to provide an example. Your answer:

// JavaScript string split allows for a string to be divided into an ordered list called substrings and then relay them into a useable array using patterns be it the number of words, characters, or a carbon copy the split is searching for. Example: If I would like to take the string "I am happily married." using the const words split would number the words, and if looking to use 3rd word you could take it by entering console.log(words[3]); Similiarly for characters you could instead label for characters.

var words = ("I am happily married.")
console.log(words[3])
// Expected Result: happily

- [ ] What did you Google to help you with this task, and how did you pick your results?

// I Googled "javascript string split method mdn", I searched for the MDN example per the class last night.

- [ ] In your own words, what does the JavaScript/Ruby array slice method do (pick based on your program)? As you're explaining, be sure to provide an example. Your answer:

// An array slice uses an array previously entered to then number the array, allowing a selection of the different numbers. Example: const planets - ('mercury', 'venus', 'earth', 'mars'); could then be split into numbers 1-4, then select using console.log(planets.slice(1, 3)) this would then exclude the numbers before 1 and after 3, so that only Venus and Earth would appear in the new array.

var planets = ("mercury", "venus", "earth", "mars")
console.log(planets.slice(1, 3))
// Expected Result: venus, earth

- [ ] What did you Google to help you with this task, and how did you pick your results?

// "JavaScript array slice MDN" and "array slicing Javascript". Picked MDN per the class, and wikipedia for another definition to be sure I was understanding correctly.

### 3. Data Types and variable assignment (20 min)

Imagine that you're taking your favorite board game and turning it into a computer-based game.

- [ ] Name of board game: `Monopoly`

- [ ] Use the space below to categorize game data into each of the following data types. You should have a **minimum of two** variables assigned for each data type below. Feel free to break each variable declaration on to its own line. Pick either ruby or javascript based on your program (see examples below for how they should look)

1. String data:
```
ruby example:
player_name = 'David'

javascript example:
var gamePiece = 'Old wooden ship';
```
1. Integer and/or float data:
  var bill_type = (100)
  var player_count = (4)

1. Boolean data:
  var purchased_property = true
  var passed_go = true

1. Array data:
  var game_pieces = ('boat', 'cat', 'dinosaur', 'thimble')
  var orange_properties = ('st james place', 'new york avenue', 'tennessee avenue')

1. OPTIONAL: Hash or Object data:
  var dark_blue_properties = ('boardwalk': 400, 'park place': 350)
  var property_owner = ('tennessee avenue': 1; 'illinois avenue': 4)



### 4. Questions/Comments/Confusions

If you have any questions, comments, or confusions from the any of the readings that you would like an instructor to address, list them below:

1.
