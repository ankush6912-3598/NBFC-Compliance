# Setup Instructions for NBFC-Compliance

## Prerequisites
1. **Node.js**: Ensure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).
2. **Git**: You should have Git installed. If not, download it from [git-scm.com](https://git-scm.com/).
3. **IDE**: Use any code editor like [Visual Studio Code](https://code.visualstudio.com/) for a better development experience.

## Step-by-Step Installation

### 1. Clone the Repository
Open your terminal/command prompt and run:
```bash
git clone https://github.com/ankush6912-3598/NBFC-Compliance.git
```

### 2. Navigate into the Project Directory
Change into the project directory:
```bash
cd NBFC-Compliance
```

### 3. Install Dependencies
Run the following command to install all the required dependencies:
```bash
npm install
```

### 4. Configure Environment Variables
Create a file named `.env` in the root directory and add your environment-specific variables. You can refer to `.env.example` for required variables.

### 5. Run the Development Server
Start the application by running:
```bash
npm start
```
This will start the development server and you can view the application at `http://localhost:3000`. 

### 6. Build the Project
To create a production build, run:
```bash
npm run build
```

## Local Development Setup with React and TypeScript
1. **Creating Components**: Use the `src/components` directory to create your React components. 
2. **State Management**: Manage state within components using React hooks or tools like Redux.
3. **Routing**: Use `react-router` for routing between different pages/views.
4. **Styling**: You can use CSS Modules, styled-components, or any CSS framework of your choice.
5. **Integrating Generative AI Model**: Make sure to import and utilize the AI model effectively in your components, processing data or user inputs as per your application requirements.

## Troubleshooting
- Ensure all dependencies are correctly installed.
- If you encounter errors while starting the server, check the console for error messages and resolve them accordingly.

Feel free to reach out to team members or check the project documentation for further assistance!