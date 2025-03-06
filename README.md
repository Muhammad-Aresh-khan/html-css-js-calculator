# Calculator Project  

## Overview  
This is a simple **JavaScript Calculator** that allows users to perform basic mathematical operations, including addition, subtraction, multiplication, and division. The calculator also supports **modulus (`%`) operation**, a **Delete (`DEL`) function**, and an **All Clear (`AC`) function** for better usability.  

## Key Features  

✅ **Basic Arithmetic Operations**  
- Supports **Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`)**.  

✅ **Modulus Calculation (`%`)**  
- The `%` button performs the **modulus operation** (remainder of division).  
- Example:  
  - `7 % 3 = 1` (because `7 ÷ 3` leaves a remainder of `1`).  
  - `10 % 4 = 2` (because `10 ÷ 4` leaves a remainder of `2`).  
- **Note:** This calculator does **not** perform percentage calculations like `50% = 0.5`.  

✅ **Delete (`DEL`) Button**  
- Removes the **last character** from the input field.  
- Useful for correcting mistakes without clearing everything.  

✅ **All Clear (`AC`) Button**  
- **Clears the entire input field** in one click.  

✅ **Real-Time Display Update**  
- Numbers and operations are displayed as they are entered.  
- Results are updated dynamically when "=" is pressed.  

## JavaScript Concepts Used  
This project utilizes the following **JavaScript concepts**:  

- **DOM Manipulation** → Selecting elements (`document.getElementById`, `document.querySelectorAll`), modifying values, and updating UI dynamically.  
- **Event Listeners** → Handling user input through **click events** (`button.addEventListener('click', function)`).  
- **String Manipulation** → Using **substring()** to handle delete operations.  
- **Array Methods** → Converting `NodeList` to an array using `Array.from()` and iterating through buttons using `forEach()`.  
- **Conditional Statements** → Checking button clicks (`if-else conditions`) to perform the correct action.  
- **Eval Function** → Evaluating mathematical expressions dynamically (`eval(string)`).  

## Technology Stack  
- **HTML** 
- **CSS** 
- **JavaScript**
  
## How to Use  
 
1. Enter numbers and mathematical operators using the on-screen buttons.  
2. Click "=" to get the result.  
3. Use **DEL** to remove the last input.  
4. Use **AC** to reset the calculator.  
5. Use `%` for **modulus operation**, not percentage calculation.
6.  
## Live Demo 🚀
https://muhammad-aresh-khan.github.io/html-css-js-calculator/

## Screenshots  
![image](https://github.com/user-attachments/assets/8ecd050d-b2a5-4250-9d05-98ca76cc8098)
![image](https://github.com/user-attachments/assets/fac7d93c-cf14-4e19-a924-2e5a25dfbb90)

 

## Future Enhancements  
🔹 Add a **percentage (%)** button separate from modulus.  
🔹 Implement **dark/light mode**.  
🔹 Improve UI with animations.  
🔹 Support advanced functions like square root and exponentiation.  
