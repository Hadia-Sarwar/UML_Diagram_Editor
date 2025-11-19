# UML Diagram Editor

A **JavaFX + TypeScript** based desktop tool for creating and editing UML Class Diagrams and Use Case Diagrams.  
This is our semester project developed as a team, focusing on providing a simple, flexible, and visually appealing diagram-editing experience.

---

## 🚀 Project Overview

The **UML Diagram Editor** allows users to visually design UML diagrams through an intuitive graphical interface.

It supports:
- Creating and styling **Class Diagrams**
- Building **Use Case Diagrams**
- Drag-and-drop interface for smooth editing
- Resize, move, update attributes and connections
- Clean layout and responsive UI elements
- Exporting and saving diagrams (if implemented in your project)

This tool is designed to help students and developers quickly prototype UML diagrams without using heavy paid tools.

---

## 👩‍💻 My Contribution (Hadia Sarwar)

I contributed majorly to:

### ✨ Frontend Development
- JavaFX UI design
- Visual layout and responsive components
- Styling, spacing, alignment, modern look
- 

### 🤝 Team Collaboration
- Helping combine UI + backend logic
- Ensuring consistent frontend structure and usability

---

## 📂 Project Structure

A typical structure (your repo may differ):

```
UML_Diagram_Editor/
│── src/
│   ├── main/
│   │   ├── java/          
│   │   ├── resources/    
│── diagrams/            
│── README.md
│── pom.xml or build.gradle
```

---

## ▶️ How to Run the Project

### 1. Install Requirements

Make sure you have:
- **Java 17 or higher**
- **JavaFX SDK**
- **Maven or Gradle** (depending on your build setup)
- Any IDE such as **IntelliJ**, **VS Code**, or **Eclipse**

### 2. Clone the Repository

```bash
git clone https://github.com/Hadia-Sarwar/UML_Diagram_Editor
cd UML_Diagram_Editor
```

### 3. Configure JavaFX

If running from an IDE:
- Go to **Project Settings → Libraries**
- Add **JavaFX SDK**
- Add VM arguments:
  ```
  --module-path "path/to/javafx/lib" --add-modules javafx.controls,javafx.fxml
  ```

### 4. Build and Run

**If using Maven:**
```bash
mvn clean install
mvn javafx:run
```

**If running directly from IDE:**
- Open the `Main` class
- Click **Run**

---

## 📘 Features Implemented

✔️ Class diagram elements  
✔️ Use-case diagram elements  
✔️ Line connectors  
✔️ Move/resize nodes  
✔️ Clean UI layout  
✔️ User-friendly canvas  
✔️ Responsive and polished frontend  

---

## 👥 Team Project

This project was created as a **collaborative semester project**.  
All team members worked on integrating UI, backend logic, and diagram functionalities.  
My focus was majorly on **UI, responsiveness, and frontend interactions**.

---

## 🌟 Future Enhancements

- Export diagram as **PNG/SVG**
- Auto-arrange diagram layout
- Real-time collaboration
- More UML diagram types

---

<p align="center">
  <i>Built with ❤️ as a semester project</i>
</p>
