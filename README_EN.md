## 🌐 [English Version of README](README_EN.md)

# Organo

Organo is an application developed in React that allows the creation and organization of employee cards in different teams.

## 🔨 Project Features

- Add employees to specific teams.
- Display teams with custom colors.
- Responsive and user-friendly interface.

### Visual Example of the Project

![chrome-capture-2024-12-21](https://github.com/user-attachments/assets/91d47dad-689f-4278-a736-3252c64265ae)

## ✔️ Technologies Used

- **React** for creating components and state management.
- **CSS** for custom styling.
- **HTML** for basic structure.
- **JavaScript (ES6+)** for logic and functionality.

## 📁 Project Structure

- **public/**
    - favicon.ico: Site icon.
    - index.html: Main HTML file.
    - manifest.json: App metadata for browsers and PWA.
    - robots.txt: File for crawler directions.
    - **images/**
        - banner.png: Main site banner.
        - logo192.png: High-resolution logo.
        - logo512.png: Larger logo for devices.

- **src/**
    - App.js: Main component integrating others.
    - index.js: Entry point of the project.
    - **components/**
        - **Banner/**: Component for the main banner.
        - **Button/**: Reusable button component.
        - **TextField/**: Text input field component.
        - **Employee/**: Component displaying an employee's information.
        - **Form/**: Form to add new employees.
        - **DropdownList/**: Component for option selection.
        - **Footer/**: Site footer.
        - **Team/**: Component organizing the employee cards.

## 🛠️ Open and Run the Project

To run the project locally, follow these steps:

1. **Make sure Node.js is installed**:
    - [Node.js](https://nodejs.org/) is required to run the project. You can check if it's already installed by running:

```bash
node -v
```

- If it's not installed, download and install the recommended version.

2. **Clone the Repository**:
    - Copy the repository URL and run the following command in your terminal:

```bash
git clone <REPOSITORY_URL>
```

3. **Install Dependencies**:
    - Navigate to the project folder and run:

```bash
npm install
```

4. **Start the Development Server**:
    - To run the project, use the command:

```bash
npm start
```

- The project will be available at [http://localhost:3000](http://localhost:3000).

## 🌐 Deploy

To deploy the project, follow these steps:

1. **Build the project for production**:

```bash
npm run build
```

2. **Host the generated files**:
    - The files will be generated in the `build/` folder. You can host them on services like [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/).

3. **Configure the server**:
    - Ensure the server is configured to serve the `index.html` file for all routes.
```

