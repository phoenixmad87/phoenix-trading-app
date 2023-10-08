# phoenix-trading-app
Trading App with React
Create an React App using Visual Studio code :
Open Terminal in VSCode
Go to the folder where you want to run the project or create a new GITHUB repo and pull the repo to your local and open the folder in VSCode.
Execute the command
npx create-react-app my-project
cd my-project

React app will get created along with packages required for App development like React and React-DOM
**NOTE:** DO NOT BE WORRIED about NPX and NPM commands , these are package managers .

**Install Tailwind CSS**
Inside your project setup Tailwind by using NPM
npm install -D tailwindcss
npx tailwindcss init

tailwind.config.js will get created where you will add the below to add tailwind CSS to your project

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

Create ./src/index.css and add below
@tailwind base;
@tailwind components;
@tailwind utilities;

In terminal now run your project using below command 
npm run start

In order to check if Tailwind CSS and React app is working as expected add below code in App.js

export default function App() {
  return (
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
  )
}
 You should see a page like below in order .
  ![image](https://github.com/phoenixmad87/phoenix-trading-app/assets/72702312/2734257c-2455-4d1a-8c9c-5c1725057b1e)

**Note:**
You can view the package.json for the respective modules that have been installed as part of npx command and the versions of the packages installed


