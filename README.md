# 🔴🟢🔵 nodeCommandLineColors.js
A NodeJS library that allows color codes to be used in the console's log in a readable manner. 

# 🚀 To Use
1. Create a folder called `colors` and add `index.js`
2. Define `foregroundColors`, `backgroundColors`, and `defaultColor`
   ```js
   const [ foregroundColors, backgroundColors, defaultColor ] = require("./colors");
   ```
3. Use the newly defined variables to change the text's color, don't foget to reset the color when necessary.
   ```js
   console.log(`Example text: ${foregroundColors.green}Green Foreground${defaultColor}, ${backgroundColors.red}Red Background${defaultColor}, Default Text`);
   ```
   The result cannot be directly shared here, as GitHub colored text features are limited.
