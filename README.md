## Project Summary

### Project Title: **UniFR RE Project D**

This project is powered by [Aurelia/New](https://github.com/aurelia/new).

---

### Repository
Find the project repository on GitHub:  https://github.com/Nicola-s84/-UNIFR_RE_PROJECT_D.git[UNIFR_RE_PROJECT_D Repository]

---

### Prerequisites
Ensure you have the following tools installed:
- **[Node.js](https://nodejs.org/)** (Version 14 or higher recommended)
- **[npm](https://www.npmjs.com/)**

---

### Installation Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Nicola-s84/-UNIFR_RE_PROJECT_D.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd UNIFR_RE_PROJECT_D
     ```

3. **Install Dependencies**
   ```bash
   npm install
   ```

4. **Run the Development Server**
   ```bash
   npm start
   ```
   Open your browser and visit: **[http://localhost:9000](http://localhost:9000)**

---

### Key Features
- **Login Functionality**: Users can log in using only one email formats with one passwort E-Mail:(Nicola.schaerer@unifr.ch) & PW:(123).
- **dashboard**: Home page with messages and links to the other pages.
- **Exams**:you can see when your next exams are
- **Courses**:timetable of a business informatics specialist 
- **Grades**:you can see the test results with detailed information.
- **Logout**: Securely log out at any time.

---
### Project Structure

- **`src/`**: Main application code.
   - **`views/`**: UI Components and Pages:
      - `login/`: Login form and components.
      - `dashboard/`: User dashboard with notifications.
      - `courses/`: Course overview like a timetable.
      - `grade/`: Grades.
      - `exams/`: next exams.
   - **`styles/`**: SCSS files for individual views.

- **`main.ts`**: Application entry point; initializes Aurelia and routing configuration.
- **`my-app.ts`**: Root component; defines routes for the application.
- **`my-app.html`**: Template for the root component; includes `<au-viewport>`.
- **`resource.d.ts`**: Type declarations for importing SCSS, CSS, and HTML.
- **`package.json`**: Project dependencies and scripts.

---

### Scripts
- **Start Development Server**: `npm start`
- **Install Dependencies**: `npm install`
- **Build Project**: `npm run build`

---
### Technologies Used
- **Aurelia 2**: Frontend Framework
- **SCSS**: Styling
- **Node.js & npm**: Package Management and Development Server

---

### Development Workflow
Follow the steps outlined above to clone, set up, and run the project. Contribute by adding or improving features based on the project requirements.#   - U N I F R _ R E _ P R O J E C T _ D  
 