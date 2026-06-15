# 🌡️ Temperature Converter
## Oasis Infobyte Web Development Internship — Task 1

---

## 🎯 Objective
To build a fully functional Temperature Converter web application
using HTML, CSS, and JavaScript that converts temperature values
between Celsius, Fahrenheit, and Kelvin instantly.The user will input a temperature in either Fahrenheit or Celsius and press a "convert" button. The converted temperature will then be displayed with the correct unit.
The UI should include four main elements:
Input field for the user to type in their temperature - don't forget to validate that the input is a number!
Dropdown menu or radio button for the user to choose if they are inputting in Celsius or Fahrenheit
"Convert" button to trigger the temperature conversion.
Display area for the final converted temperature and unit.
For an extra challenge: You can add in a third conversion option to convert from and to Kelvin as well.

---

## 📁 Files in This Project

| File                      | Purpose                              |
|---------------------------|--------------------------------------|
| temperature-converter.html| Complete app — HTML, CSS, JS in one file |
| README.md                 | Basic document of the task1           |

---

## 🛠️ Tools Used
- HTML5
- CSS3 (CSS Variables, Grid, Flexbox)
- JavaScript (Vanilla)
- VS Code
- Live Server
- GitHub + GitHub Pages

---

## 📋 Steps Performed
1. Created the project structure with a single HTML file
2. Designed the layout using CSS Flexbox and Grid
3. Used CSS custom properties (variables) for consistent theming
4. Built the input field to accept any temperature value
5. Created three unit selector buttons (°C, °F, K) with
   active highlight on selection
6. Wrote JavaScript conversion logic:
   - Celsius  → Fahrenheit and Kelvin
   - Fahrenheit → Celsius and Kelvin
   - Kelvin   → Celsius and Fahrenheit
7. Added input validation — shows error for empty or invalid input
8. Displayed all three converted results in a result grid
9. Added Enter key support for quick conversion

---

## 🔢 Conversion Formulas Used

| From        | To          | Formula                        |
|-------------|-------------|--------------------------------|
| Celsius     | Fahrenheit  | (C × 9/5) + 32                 |
| Celsius     | Kelvin      | C + 273.15                     |
| Fahrenheit  | Celsius     | (F − 32) × 5/9                 |
| Fahrenheit  | Kelvin      | (F − 32) × 5/9 + 273.15        |
| Kelvin      | Celsius     | K − 273.15                     |
| Kelvin      | Fahrenheit  | (K − 273.15) × 9/5 + 32        |

---

## ✨ Features
- Convert between Celsius, Fahrenheit, and Kelvin
- Active button highlight shows selected input unit
- All three results displayed at once in a grid
- Input validation with error message for invalid input
- Enter key support for fast conversion
- Results rounded to 2 decimal places
- Clean green-themed responsive UI
- CSS variables for easy theme customization

---

## 🎨 Design Highlights

| Property        | Value                              |
|-----------------|------------------------------------|
| Background      | Light green — #f0fdf4              |
| Accent Color    | Green — #16a34a                    |
| Font            | Segoe UI / System UI               |
| Border Radius   | 8px – 12px (rounded cards)         |
| Result Grid     | CSS auto-fit grid (responsive)     |
| Active State    | Highlighted green button           |

---

## 🚀 How to Run

**Option 1 — Open directly:**
Double click `temperature-converter.html` to open in browser

**Option 2 — Live Server in VS Code:**
Right click the file → Open with Live Server

---

## 🧠 JavaScript Concepts Used

| Concept              | Where It Is Used                              |
|----------------------|-----------------------------------------------|
| `querySelectorAll`   | Selects all unit buttons                      |
| `addEventListener`   | Click on buttons, Enter key on input          |
| `forEach`            | Loops through all buttons to remove active    |
| `classList`          | Adds/removes active and show classes          |
| `dataset`            | Reads data-unit value from clicked button     |
| `parseFloat`         | Converts input string to decimal number       |
| `isNaN`              | Validates that input is a real number         |
| `toFixed(2)`         | Rounds result to 2 decimal places             |
| `Array.map + join`   | Builds result grid HTML dynamically           |
| CSS Variables        | --bg, --accent, --text for consistent theming |


---

## ✅ Outcome
A clean and fully functional temperature converter was built
successfully using HTML, CSS, and JavaScript. The app converts
between all three major temperature units instantly with proper
validation, result display, and keyboard support.

---

## 👤 Author
**Nikhil Shivhare**
Oasis Infobyte — Web Development Internship — Task 1
