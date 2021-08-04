# Counter App
A starter react app with an `<h1>` tag showing a count value which can be changed using two buttons **+** and **-**.




### How to create a react app?
`npm create-react-app <app-name>`  
`cd <app-name>`  
`npm start`

A sample react app is created in your directory. Now delete all the extra files from `/public` and `/src` folders keeping only the `index.html` and `index.js` files.  
Delete all the sample code in these two files and start writing code in these files.

###### For this project, I performed the following steps:  
* Created the sample react app using npm and deleted the extra files
* Linked a css file in index.html
* Created styling for the webpage and its elements: `<h1>` and `<button>`
* Created a components folder in `/src` and created a new file called `App.jsx`
* Imported the `<App />` component into `index.js`
* In App.jsx
  * Used the react hook **useState** to create a **count** variable along with the updating function **setCount**  
    `const [count, setCount] = useState(0);` 
  * Created two functions **increase()** and **decrease()** which get triggered on button click. Inside the functions 
    **setCount()** changes the value of the **count** variable
* Rendered the `<App />` component in `index.js` using ReactDOM, targetting a div with an id of **root** in the html file.  
  `ReactDOM.render(<App />, document.getElementById('root'));`  
  
  
> **Note:** node modules created by npm have not been added in the repository.
