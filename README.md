# Project: Engineering Website

This project is a simple web page built with **HTML5** and **CSS3**, demonstrating some of the most important layout and styling concepts in modern web development.  

---

## HTML Structure  

- **`<header>`** → Defines the top section of the page, containing the navigation bar.  
- **`<nav>`** → Holds the site’s navigation links.  
- **`<main>`** → Represents the central content of the page.  
- **`<section>`** → Groups related content (e.g., articles, images).  
- **`<article>`** → Represents an independent block of content such as text with a title.  
- **`<figure>`** and **`<img>`** → Used to display and semantically group an image.  
- **`<footer>`** → Contains the bottom information of the page.  

This structure follows **semantic HTML**, improving both accessibility and SEO.  

---

## CSS Concepts  

### 1. **Box Model**  
Every HTML element is treated as a box with:  
- **content** → the text or image inside  
- **padding** → space between content and border  
- **border** → the element’s edge  
- **margin** → space outside the element  

Example from the project:  
```css
#titles article {
    max-width: 350px;
    padding: 10px;
    box-shadow: 1px 1px 1px 1px black;
}
```

---

### 2. **Display Property**  
Controls how elements behave on the page:  
- **`display: block`** → element takes full width (e.g., links styled as buttons).  
- **`display: flex`** → activates **Flexbox**, allowing powerful alignment and spacing.  

Example:  
```css
header nav {
    display: flex;
    flex-direction: row;
    align-items: center;
}
```

---

### 3. **Flexbox**  
Flexbox makes it easier to align and distribute space among elements in a container.  
- **`flex-direction: row`** → items placed side by side.  
- **`justify-content: space-around`** → items spread evenly with space around them.  
- **`align-items: center`** → vertically centers the elements.  

Example:  
```css
#titles {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}
```

---

### 4. **Hover Effect**  
Changes the style of an element when the user moves the mouse over it.  

Example:  
```css
main section article a:hover {
    background-color: #1daf7e;
    cursor: pointer;
}
```

This gives feedback to the user, making buttons feel interactive.  

---

### 5. **Position**  
Determines how elements are placed on the page.  

Example:  
```css
main section figure img {
    position: relative;
}
```

Here, `relative` allows the image to be shifted relative to its normal position.  

---

## Key Takeaways  
- **Semantic HTML** improves structure and accessibility.  
- **Box Model** is the foundation of spacing and sizing.  
- **Flexbox** provides powerful layout alignment and distribution.  
- **Display** defines how elements behave (block, flex, inline, etc.).  
- **Hover** adds interactivity to the UI.  
- **Position** helps fine-tune element placement.  
