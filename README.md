<div align="center">
  <h1 align="center">RESUMEX</h1>
  <p align="center">
    <strong>A modern, web-based resume builder to craft your ATS-optimized professional resume in real-time.</strong>
  </p>
  
  [![Website](https://img.shields.io/badge/Demo-Live_Website-success?style=flat-square&logo=google-chrome)](https://tanmaygoel15.github.io/RESUMEX/)
  [![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?style=flat-square&logo=github)](https://github.com/TanmayGoel15/RESUMEX)
</div>

---

## 🚀 Live Demo
Experience the power of real-time resume building right in your browser. 
👉 **[Click here to open RESUMEX Live](https://tanmaygoel15.github.io/RESUMEX/)**

---

## ✨ Features
* ⚡ **Real-time resume preview:** Instantly see changes to your resume as you type. No waiting, no refreshing.
* 🤖 **ATS score analyzer:** Get immediate feedback on your resume's Applicant Tracking System compatibility.
* 🧱 **Dynamic form builder:** Add, remove, and manage sections like Experience and Education dynamically.
* 🖱️ **Drag-and-drop reordering:** Seamlessly reorganize your work history and education by dragging sections.
* 📄 **PDF export functionality:** Generate pixel-perfect, high-quality PDF documents with a single click.
* 🌗 **Dark/Light mode UI:** Toggle between a sleek dark theme and a clean light theme for optimal viewing comfort.

---

## 💻 Tech Stack
This project is built using foundational web technologies without the overhead of heavy frameworks:
* <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML"> **HTML5** for semantic document structuring.
* <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS"> **CSS3** for flexible layouts, fluid animations, and robust dynamic variables for theming.
* <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS"> **Vanilla JavaScript (ES6+)** for state management, DOM rendering, and logic handling.

---

## 📁 Project Structure
```text
├── index.html          # Main application entry point containing the UI structure
├── css/
│   ├── style.css       # Core styles, CSS variables, dark/light theme definitions
│   └── print.css       # Specialized styles for perfect PDF rendering
├── js/
│   ├── app.js          # Core logic, dynamic form engine, UI interactions
│   ├── render.js       # Real-time DOM manipulation updates
│   ├── ats.js          # Algorithm processing ATS keyword scoring
│   └── store.js        # Browser local storage state persistence
└── assets/             # Images, icons, and graphical assets
```

---

## 🛠️ Installation & Setup
To run this project locally on your machine, follow these simple steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TanmayGoel15/RESUMEX.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd RESUMEX
   ```

3. **Open the application:**
   Since this is a client-side Vanilla web application, you do not need complex build tools. Simply open `index.html` in your favorite modern browser:
   * **Windows/Linux**: Double-click `index.html`
   * **macOS**: `open index.html`
   
   *(Optional)* For the best development experience, run it via a local server extension like **Live Server** in VS Code.

---

## 💡 Usage
1. **Enter Personal Details**: Fill out your contact information in the left sidebar.
2. **Add Sections**: Click "Add Experience" or "Add Education" to populate the dynamic form.
3. **Reorder Items**: Use the drag handle next to entries to reorder them logically.
4. **Evaluate ATS**: Click the "ATS Score" button in the header at any time to receive intelligent feedback.
5. **Download**: Once satisfied, click the "Download PDF" button to export your finished resume.

---



## 👥 Team Members

Contributions were divided to ensure focus and high-quality deliverables:

* 👨‍💻 **[Tanmay Goel](https://github.com/TanmayGoel15)** 
  * Lead on the **Rendering Engine**, **ATS Algorithm**, and overall **UI Design**.
* 👨‍💻 **Ayush Bhatt** 
  * Lead on **Core Logic**, **State Management**, and the **Dynamic Form System**.

---

## 🔮 Future Improvements
* [ ] 🎨 **More resume templates:** Add a repository of distinct visual templates to choose from.
* [ ] ☁️ **Backend integration:** Implement a database to sync user resumes across different devices natively.
* [ ] 🔐 **User authentication:** Allow users to log in, securely save multiple drafts, and manage profile versions.

---

## 📜 License
This project is actively maintained. Please ensure credit is given properly.

---
*If you find this project helpful, please consider leaving a ⭐ on the [repository](https://github.com/TanmayGoel15/RESUMEX)!*
