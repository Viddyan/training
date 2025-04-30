# **Day 1 – Layout Doesn’t Exist! How Can We Design It?**

---

## **1. Main Project (PBL Context): Building a Real-Time Weather App**

**Project Vision:**  
By the end of this multi-day training, learners will build a **fully functional weather app** that:
- Fetches live weather data based on city name
- Displays data with a clean, responsive UI
- Supports dynamic updates and user interactions
- Integrates APIs, handles errors, and deploys live

> **Today’s Focus:** Laying the UI foundation of the Weather App using HTML, CSS, and minimal JavaScript to simulate structure and responsiveness.

---

## **2. Today’s Problem Statement (PSBL)**

### **Standard Problem Statement:**
> You’ve been assigned to build a weather app, but the design team hasn’t provided a layout. How will users search for a city and view the weather without a proper interface?

### **Rewritten as User Stories:**
-  *As a user, I want to search for a city name so that I can check the weather of that location.*
-  *As a user, I want to see a structured and visually organized weather panel so that I can understand the forecast easily.*
-  *As a developer, I want to build a modular, responsive layout that can later integrate live data from weather APIs.*

---

## **3. Learning Objectives**

By the end of this session, learners will be able to:
- Understand the importance of layout design before adding logic or APIs.
- Create a **responsive and modular layout** using **HTML and CSS**.
- Build a **search bar, weather card UI**, and placeholder sections for future data.
- Use **Flexbox** and **Grid** for structure and alignment.
- Prepare the project for dynamic data integration in future sessions.

---

## **4. Scenario-Based Framing**

> Imagine you're a junior front-end developer at a startup. Your team needs to pitch a working prototype to stakeholders by tomorrow. There’s **no time to wait for designers**—you must design a clean, user-friendly UI from scratch that **simulates the weather app experience**, even if no real data exists yet.

You need to:
- Build a search input field for city names.
- Design a weather display panel with mock information.
- Ensure it looks good on both desktop and mobile.

---

## **5. Mini Visual Roadmap (Descriptive)**

```text
[Start]
   ↓
Set up base project folder (HTML, CSS, JS)
   ↓
Design header with app name and search input
   ↓
Create a weather card with city name, temperature, description
   ↓
Use Flexbox/Grid for layout and responsiveness
   ↓
Test on different screen sizes
   ↓
[End]
```

---

## **6. Conceptual Explanation (Notes + Code Walkthroughs)**

### 🔹 HTML Essentials
- `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
- Semantic tags: `<header>`, `<main>`, `<section>`, `<footer>`
- Input fields and buttons: `<input type="text">`, `<button>`

### 🔹 CSS Concepts
- Selectors, Properties, Class/ID usage
- Layout with **Flexbox**
- Mobile responsiveness: `@media` queries
- Placeholder styling: background color, font size, padding

### 🔹 Structure Planning

```html
<!-- Layout Design Plan -->
<header>
  <h1>Weather App</h1>
  <input type="text" placeholder="Enter city name" />
  <button>Search</button>
</header>

<main>
  <section class="weather-card">
    <h2>City Name</h2>
    <p>Temperature: --°C</p>
    <p>Description: Clear sky</p>
  </section>
</main>
```

### 🔹 Sample CSS Snippet

```css
body {
  font-family: Arial, sans-serif;
  background: #e0f7fa;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}

header {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

input {
  padding: 10px;
  margin: 10px;
  width: 200px;
}

.weather-card {
  background: #ffffff;
  padding: 20px;
  margin-top: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
```

---

## **7. Hands-On Implementation (Code + Integration in Project)**

### 🔸 Folder Structure:
```
/weather-app
  ├── index.html
  ├── style.css
  └── script.js (empty for now)
```

### 🔸 `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Weather App</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🌦️ Weather Now</h1>
    <input type="text" id="cityInput" placeholder="Enter city name">
    <button id="searchBtn">Search</button>
  </header>

  <main>
    <section class="weather-card">
      <h2>City: --</h2>
      <p>Temperature: --°C</p>
      <p>Description: --</p>
    </section>
  </main>
</body>
</html>
```

### 🔸 `style.css`
```css
body {
  background: #dff9fb;
  font-family: 'Segoe UI', sans-serif;
  text-align: center;
}

header {
  padding: 20px;
  background-color: #74b9ff;
  color: white;
}

input, button {
  padding: 10px;
  margin: 5px;
  font-size: 1rem;
}

.weather-card {
  background: white;
  margin: 30px auto;
  padding: 20px;
  width: 300px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  border-radius: 12px;
}
```

---

## **8. Output-Based Assessment (with GitHub Push)**

### ✅ Task 1:
Modify the layout to include:
- A background image
- A loading spinner placeholder while searching (even if non-functional)

### ✅ Task 2:
Push the current version to GitHub.
- Add a README describing your layout logic
- Commit message: `"Initial layout with static weather UI"`

---

## **9. Interview Preparation (5 Output-Based Qs)**

### **Q1:**
```html
<input type="text" value="Delhi" placeholder="Enter city" />
```
What will be shown in the input field by default?

- a) `Enter city`
- b) `Delhi`
- c) `Nothing`
- d) `undefined`

✅ **Answer:** b) `Delhi`

---

### **Q2:**
What is the purpose of `box-shadow` in CSS?

- a) Adds border
- b) Creates 3D depth
- c) Changes font style
- d) Hides element

✅ **Answer:** b) Creates 3D depth

---

### **Q3:**
```css
.weather-card {
  width: 100%;
  max-width: 400px;
  margin: auto;
}
```
What will be the width of `.weather-card` on a 600px screen?

- a) 100px  
- b) 600px  
- c) 400px  
- d) 300px

✅ **Answer:** c) 400px

---

### **Q4:**
What will this layout display?
```css
input, button {
  display: block;
  margin: auto;
}
```

- a) Aligns center vertically
- b) Aligns center horizontally
- c) Makes it red
- d) Hides the input

✅ **Answer:** b) Aligns center horizontally

---

### **Q5:**
If an HTML file doesn’t include `<meta charset="UTF-8">`, what may happen?

- a) Site will be blank
- b) Input won't work
- c) Some special characters might not display properly
- d) Nothing

✅ **Answer:** c) Some special characters might not display properly

---

## **10. Connection to the Next Problem Statement**

> **Next Up:** Now that we have a static and beautiful UI, we need to **fetch real-time weather data**. But where is that data coming from?

📌 **Next Session:**
**Problem:** Where’s the Weather Data Coming From?  
You will learn:
- How to find and use **open weather APIs**
- How to fetch data using **JavaScript’s `fetch()`**
- How to **integrate** data dynamically into the layout

---
