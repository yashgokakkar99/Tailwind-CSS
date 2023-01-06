# Tailwind-CSS
Learning Tailwind CSS 
#Setting up vscode for a project in which tailwindcss is used
#Step1:
npm init -y // This initializes the directory as a NodeJs project
#Step2:
npm install -D tailwindcss postcss autoprefixer vite // installs required packages
#Step3:
npx tailwindcss init -p
#Step4:
Create a CSS file "input.css", add it yo your html and edit it with this content:
@tailwind base;
@tailwind componenets;
@tailwind utilities;
#Step5:
In your tailwind.config.js file replace content:[], with content:["*"].
#Step6:
Add "start":"vite" to your scripts in package.json
#Step7:
Run npm run start command to start a dev server
