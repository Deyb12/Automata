# Turing Machine Simulator (Automata Project)

A **web-based Turing Machine simulator** that allows users to create, edit, visualize, and simulate automata.
The tool displays animated **state diagrams and tape execution**, making it easier to understand and study automata theory concepts.

---

## 🚀 Features

* **Interactive Simulator**

  * Step-by-step execution
  * Run / Pause machine execution
  * Reset simulation anytime
* **Code Editor**

  * YAML-based machine specification
  * Built-in syntax validation & error highlighting
  * Load and revert diagram from code
* **Visualization**

  * Dynamic state diagram visualization
  * Animated tape simulation
  * Position saving and restoring
* **Document Management**

  * Save, duplicate, rename, and delete automata documents
  * Import/export machines (via GitHub Gist or file upload)
  * Shareable links for collaboration

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Bootstrap, custom styling)
* **JavaScript Libraries:**

  * [D3.js](https://d3js.org/) – for state diagram visualization
  * [Ace Editor](https://ace.c9.io/) – for YAML editor
  * [Lodash](https://lodash.com/), Bluebird, js-yaml
  * Clipboard.js – for export/copy
* **Build Tools:** Webpack, ESLint
* **Language:** JavaScript (ES6)

---

## 📂 Project Structure

```
Automata-Simulator/
├── index.html          # Main interface
├── package.json        # Project metadata & dependencies
├── webpack.config.js   # Build configuration
├── src/                # Source JavaScript modules
│   ├── TMDocument.js
│   ├── TMSimulator.js
│   ├── TMDocumentController.js
│   ├── TMViz.js
│   ├── parser.js
│   └── ...
├── build/              # Bundled output (auto-generated)
├── css/                # Stylesheets
├── vendor/             # External libraries
├── LICENSE             # BSD-3-Clause License
└── update-gh-pages.sh  # Deployment script
```

---

## ⚙️ Installation & Setup

1. **Clone repository**

   ```bash
   git clone <repo-url>
   cd Automata-Simulator
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run locally**

   ```bash
   npm start
   ```

   Then open in browser:

   ```
   http://localhost:8080
   ```

4. **Build for production**

   ```bash
   npm run prod
   ```

---


## 📜 License

This project uses the **BSD 3-Clause License**.
Refer to the [LICENSE](LICENSE) file for full details.
