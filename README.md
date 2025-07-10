# 📝 Project Plan & Meeting Agenda App

**Project Plan & Meeting Agenda App** is a modern, interactive web application for planning, tracking, and visualizing project tasks and meeting agendas. It provides a visually appealing, card-based interface for managing tasks, priorities, statuses, and custom notes, with advanced customization and export features.

---

## 📂 Getting Started

- **Main Page:**  
  Open [`newitem.html`](./newitem.html) in your browser to use the application.  
  No installation or backend required—everything runs in the browser.

---

## ✨ Features

- **Card-Based Task Management:**  
  Add agenda items as cards, each with a title, description, priority, status, and a customizable extra note field.

- **Customizable Extra Notes:**  
  Each card features an extra input field for additional notes, with configurable text color, font size, and bold styling.  
  Global controls at the top allow you to instantly update these styles for all cards.

- **Priority & Status Controls:**  
  - Set task priority (High, Medium, Low) with color-coded buttons.
  - Set task status (Empty, To be done, In progress, Done).
  - When status is set to **Done**, the card becomes semi-transparent, the colored frame disappears, and only the "Done" status button remains fully visible.

- **Colorful Visuals:**  
  Each card is assigned a unique color (excluding red) for its border and number badge, cycling through a palette of 10 distinct colors.

- **Date & Title Editing:**  
  Edit the agenda title and date directly at the top of the page.

- **Responsive Design:**  
  The layout adapts for both desktop and mobile screens.

- **Export as PNG:**  
  Download the entire agenda (excluding the top settings bar) as a PNG image with a single click.

---

## 🖱️ How to Use

1. **Set Agenda Title & Date:**  
   Edit the title and date fields at the top.

2. **Customize Extra Notes:**  
   Use the controls at the top to set the text color, font size, and boldness for all extra note fields.

3. **Add New Items:**  
   Click the green "+" button to add a new agenda/task card.

4. **Edit Card Content:**  
   - Click on the title or description to edit.
   - Use the extra input field for additional notes.

5. **Set Priority & Status:**  
   - Click the priority buttons to set importance.
   - Click the status buttons to track progress.  
     When "Done" is selected, the card fades and the colored frame disappears.

6. **Export Agenda:**  
   Click the "Download PNG" button to save your agenda as an image (the top settings bar is excluded).

---

## 🛠️ Tech Stack

- **HTML5 & CSS3:**  
  Modern, responsive layout and styling.

- **Vanilla JavaScript:**  
  All interactivity and logic handled client-side.

- **[html2canvas](https://html2canvas.hertzen.com/):**  
  Used for exporting the agenda as a PNG image.

---

## 📁 File Structure

- [`newitem.html`](./newitem.html) — Main application file (open in browser)
- [`README.md`](./README.md) — This documentation

---

## 💡 Customization & Extensibility

- Easily modify the color palette or add more card features by editing `newitem.html`.
- The app is self-contained and can be embedded or extended for more advanced project planning needs.

---

## 🚀 License

This project is open source and free to use for personal and commercial purposes.

---
