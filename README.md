# 2048 Game Customizer

## Introduction
Welcome to my 2048 Game Customizer, created by @calskidal! This tool allows you to customize the 2048 game to your liking by adjusting the variables in the console.

## Getting Started
1. Visit [2048 Game](//:play2048.co).
2. Open the developer tools by pressing F12 or Ctrl + Shift + I (Windows/Linux) or Cmd + Opt + I (Mac). Alternatively, right-click on the webpage and select "Inspect" from the context menu.
3. Navigate to the "Console" tab in the developer tools.

## Customization
Paste the provided code into the console and modify the variables according to your preferences. You can change values like the tile spawn value by adjusting the code.

## Example
 **Edit Tile Values:**
   - Look for the line: `var e = Math.random() < 0.9 ? 2 : 4;
   - Change the values `2` and `4` to your desired tile values (MUST BE MULTIPLES OF 2)

3. **Understand Probability:**
   - The probability is determined by `Math.random() < 0.9`. In this example, there's a 90% chance of getting the first value and a 10% chance of the second.
   - Adjust `0.9` to set your own probability. For example, `0.8` would give an 80% chance for the first value.

4. **Paste and Play:**
   - After editing, paste the code into the browser console and press Enter.
   - Now, when you make a move in the 2048 game, tiles with your specified values will appear based on the customized chances.

