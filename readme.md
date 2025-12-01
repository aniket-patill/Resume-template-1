# HTML Resume Template (A4 & Mobile Optimized)

This project is a high-fidelity HTML/CSS replication of a resume document. It is designed to look exactly like a traditional document on desktop, adapt seamlessly to mobile devices, and print perfectly to PDF in A4 format.

## 📄 Project Overview

The goal of this project was to convert a static image of a resume into a semantic, responsive, and editable HTML file. It uses standard web technologies to ensure compatibility across all modern browsers while maintaining strict formatting requirements for printing.

## ✨ Key Features

### 1. 🖨️ A4 Print Optimization
- **Strict Dimensions:** The layout is locked to **210mm x 297mm** (standard A4) using CSS `@page` rules.
- **Print-Ready:** When you press `Ctrl + P` (or Command + P), margins are automatically removed, and the background graphics (section headers) are forced to render using `-webkit-print-color-adjust`.
- **Page Break Control:** CSS rules prevent awkward page breaks inside tables or list items.

### 2. 📱 Fully Responsive (Mobile Friendly)
- **Fluid Layout:** On screens smaller than 768px (mobile), the rigid A4 width is removed, and the content flows naturally to fit the device width.
- **Scrollable Tables:** The education table includes a horizontal scroll wrapper (`.table-responsive`) to prevent breaking the layout on small phone screens.
- **Adjusted Spacing:** Padding and font sizes are tweaked for readability on smaller displays.

### 3. 🖥️ Desktop "Paper" Simulation
- When viewed on a desktop browser, the resume appears as a sheet of paper floating on a gray desk background, complete with a drop shadow for visual depth.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** Flexbox for layout, Media Queries for responsiveness, and Print CSS for PDF generation.
* **Vanilla JS:** (Optional) Included for basic console logging; no external frameworks or libraries are required.

## 🚀 How to Use

### Viewing the Resume
1.  Download the `index.html` file.
2.  Open it in any web browser (Chrome, Edge, Firefox, Safari).

### Saving as PDF
To convert this HTML file back into a PDF document:
1.  Open the file in your browser.
2.  Press **Ctrl + P** (Windows) or **Command + P** (Mac) to open the print dialog.
3.  **Destination:** Select "Save as PDF".
4.  **Margins:** Set to "None" or "Default" (the code handles the spacing).
5.  **Options:** Ensure **"Background graphics"** is CHECKED (this is crucial for the blue headers to appear).
6.  Click **Save**.

## 📂 Customization

Since this is a single-file solution, all content and styling are located within `index.html`.

* **To Edit Content:** Search for the text you want to change (e.g., "CAREER OBJECTIVE") and replace it inside the HTML tags.
* **To Change Colors:** Look for the `.section-header` class in the `<style>` block and change the `background-color` hex code (currently `#366092`).
* **To Change Fonts:** Update the `font-family` in the `body` selector.

## 📝 License

Free to use and modify for personal or commercial purposes.