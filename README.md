Got it 👍
Let me break down what your **Kabaddi Scorecard HTML code** does and explain the key parts.

---

## 📌 What this code is about

It creates a **web page** that displays a **Kabaddi match scorecard** in a clean and styled table format.
It uses **HTML** for structure and **CSS** for styling.

---

## 🔎 Code Explanation

### 1. **Basic Structure**

```html
<!DOCTYPE html>
<html>
<head>
  <title>Kabaddi Scorecard</title>
  <style> ... </style>
</head>
<body> ... </body>
</html>
```

* `<!DOCTYPE html>` → Tells the browser this is an HTML5 document.
* `<html>...</html>` → Wraps the entire page.
* `<head>...</head>` → Contains metadata (title, styles).
* `<body>...</body>` → Contains what the user actually sees.

---

### 2. **Page Title**

```html
<title>Kabaddi Scorecard</title>
```

This sets the page title shown in the browser tab.

---

### 3. **CSS Styling (inside `<style>...</style>`)**

* **Body Styling**

  ```css
  body {
    font-family: Arial, sans-serif;
    margin: 20px;
    background-color: #f0f8ff;
  }
  ```

  ➝ Makes the text use Arial, adds spacing around, and sets a light-blue background.

* **Heading**

  ```css
  h1 {
    text-align: center;
    color: #2f4f4f;
  }
  ```

  ➝ Centers the title and gives it a dark gray-green color.

* **Table Design**

  ```css
  table {
    width: 60%;
    margin: 0 auto;
    border-collapse: collapse;
    box-shadow: 0 0 10px #aaa;
  }
  ```

  ➝ Table is centered, 60% wide, borders merged, and has a shadow effect.

* **Cells (th & td)**

  ```css
  th, td {
    padding: 12px;
    border: 1px solid #ddd;
    text-align: center;
  }
  th {
    background-color: #4682b4;
    color: white;
  }
  ```

  ➝ Each cell has padding, a border, and text centered.
  ➝ Header row (`th`) has a blue background with white text.

* **Row Coloring**

  ```css
  tr:nth-child(even) {
    background-color: #e6f2ff;
  }
  ```

  ➝ Makes every even row have a light blue background for readability.

---

### 4. **Main Content**

```html
<h1>Kabaddi Match Scorecard</h1>
```

➝ A heading at the top.

```html
<table>
  <thead>
    <tr>
      <th>Team</th>
      <th>Score</th>
      <th>Raid Points</th>
      <th>Defense Points</th>
      <th>Fouls</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Team A</td>
      <td>45</td>
      <td>28</td>
      <td>17</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Team B</td>
      <td>38</td>
      <td>24</td>
      <td>14</td>
      <td>5</td>
    </tr>
  </tbody>
</table>
```

* `<thead>` → Defines table headers (column names).
* `<tbody>` → Holds the actual team data.
* Two rows for **Team A** and **Team B** with their scores.

---

## 🎯 Output

When opened in a browser, this code shows:

* A **title** "Kabaddi Match Scorecard".
* A **styled table** with two teams’ scores (score, raid points, defense points, fouls).
* Alternating row colors, center-aligned text, and a professional look.

---

✅ In short:
This code builds a **simple, professional Kabaddi scorecard webpage** using HTML tables and CSS styling.

---

Do you also want me to add **JavaScript logic** so that the code **automatically highlights the winning team** instead of you manually deciding?
