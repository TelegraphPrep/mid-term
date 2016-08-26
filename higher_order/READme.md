### Build Flexible function
    1. Build a flexible function `talkToUser` using `loop`.
    2. It should loop through an array of strings and perform certain actions based on the `promptType`.


* [ ] Build a flexible function `talkToUser` that takes a collection of prompts and a string, `promptType`, and:

    * [ ] if the `promptType` is equal to 'log', log each prompt in the collection to the console using the native console.log function.

    * [ ] if the `promptType` is equal to 'alert', alert the user of each prompt in the collection using the native `alert` function.

    * [ ] if the `promptType` is equal to 'prompt', prompt the user with each prompt in the collection using the native `prompt` function.

Example:

```

var funFacts = [

"A moment is a medieval unit of time equal to 1.5 minutes or 1/40 of an hour.",

"It can be a protracted process but, explained simply, sake is made when rice is ground, washed and steamed.",

"A person's ABO type is determined by the presence or absence of the A or B substance on his red cells.",

"Jupiter is the fastest spinning planet in our Solar System rotating on average once in just under 10 hours. "

];

talkToUser(funFacts, 'log');

// "A moment is a medieval unit of time equal to 1.5 minutes..."
// "It can be a protracted process but, explained simply, sa..."
// "A person's ABO type is determined by the presence or abs..."
// "Jupiter is the fastest spinning planet in our Solar Syst..."

## Extra Credit:
Have your talkToUser function number the strings in the collection as it performs its action, presenting it as a numbered list. Have the list start with 1 (not zero).

Example:

talkToUser(funFacts, 'log');

// 1. "A moment is a medieval unit of time equal to 1.5 minutes..."
// 2. "It can be a protracted process but, explained simply, sa..."
// 3. "A person's ABO type is determined by the presence or abs..."
// 4. "Jupiter is the fastest spinning planet in our Solar Syst..."