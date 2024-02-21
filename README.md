### Hello there.

Try [Currency Converter](https://tabin9.github.io/Currency-Converter/)     
Note: bg-image didn't work on github pages :(

This was one of my first React JS project. It was quite challenging. Concepts I learned / brushed up:

1. Creating custom hooks: 
    Here, I made a hook - "useCurrencyInfo" to handle the API I used to get the real time currency 
    conversions. Then returning the JSON data.
2. Creating reusable components: 
    Learned and created resusable component, in the project we see two 
    boxes, one where we enter the amount and one where the converted amount is displayed. Each box had
    a label (to / from), type text, input space (disabled in the converted amount box), select tag for 
    all the currency type options.
3. Putting it all togethe: 
    - In app.jsx I used the custom hook I made to get the data from the API. I got all the currency 
    options and their respective conversion values.
    - Swap button was pretty straight forward.
    - Added an AI generated background image.
    - Using the reusable boxes with relative arguments.
    - A submit button to end it.
