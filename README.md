## Hello there,
My name is Yusuf Mustahan and I am a software engenineer with years of  experience in both frontend and backend programming. I will potray myself as a frontend and backend balanced programmer, showing that I am very verstaile with working on any programming stack for the organization. As been earlier instructed to declare the stack of interest which I would love to 




work on and this has made me choose backend stack of the organization where I will be able show my expertise by managing the organizations data flow and write amazing logics.
<hr />

## The Application's information
This is an advanced weather forecast application which has the implementaton of a fullstack skills by having both login and signup for existing and new users. The application is mobile responsive and interactive as it displays location searched region on an integrated map with the wether information of the region, the appliction displays the weather information of a random city on login while also displaying the weather information of the searched region when users makes their search. The application implements <b>Json web tokens(JWT)</b> to generate user's <b>access token and refresh tokens</b>. The backend was built using Node JS, <b>Express JS</b> and using a public <b>api</b> which can be found at [https://openweathermap.org](https://openweathermap.org/) for a given region weather forecast information, while the frontend relies on the use of the great <b>React JS</b> and <b>MongoDB</b> as database respectively.

#### The Application's demo can be found at [https://advanced-wether-app.netlify.app](https://advanced-wether-app.netlify.app/)

<!-- ### Application Github Links -->
<!-- #### Note the full repository can be found here.
<b>Frontend repository :</b>

[https://github.com/Yumustyology/yumustyung_advanced_wether_frontend](https://github.com/Yumustyology/yumustyung_advanced_wether_frontend)

<br />

<b>Backend repository :</b> 

[https://github.com/Yumustyology/yumustyung_advanced_wether_backend](https://github.com/Yumustyology/yumustyung_advanced_wether_backend)


<hr /> -->
<!-- # Getting Started with Advanced weather forecast application
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). -->

# Instructions to run the application
## Available Backend Scripts

###  `npm install`
This script is essential to be ran first on clone or download of the repository which will downlad all needed dependencies for the application to run perfectly.

###  `npm install --force`
The `npm install` script can be ran with the `--force` flag when there is conflict with the dependencies installaton on the local server. 

###  `npm start`

This runs the backend in the development mode and opens it on port [http://localhost:5000](http://localhost:5000) 

### Backend enviroment Variables
In the application backend directory, create a .env file and store the following enviroment variables.
<li>REFRESH_TOKEN_SECRET</li>
<li>ACCESS_TOKEN_SECRET</li>
<li>DB_CONNECT_URI</li>
<br />
<b>REFRESH_TOKEN_SECRET</b> and <b>ACCESS_TOKEN_SECRET</b> can have random texts stored in them, as they are used to create access and refresh tokens which will be used later for validating user login. <b>DB_CONNECT_URI</b> gets the link of the <b>MonogoDB</b> database stored in it.
<br /> 

Navigate to the project directory on your terminal and run this script, this spin up the backend application on your local browser with [http://localhost:5000](http://localhost:5000) 



## Available Frontend Scripts

In the frontend project directory, you can run:

###  `npm install`
This script is essential to be ran first on clone or download of the repository which will downlad all needed dependencies for the application to run perfectly.

###  `npm install --force`
The `npm install` script can be ran with the `--force` flag when there is conflict with the dependencies installaton on the local server. 

### Frontend enviroment Variables
In the application frontend directory, create a .env file and store the following enviroment variables.
<li>REACT_APP_ID</li>
The <b>REACT_APP_ID</b> is used to hold the openweathermap api key which is used in getting informations of a serched region on the application, this is deemed secrete and was added in the env file so as not to get pushed to the public repository, you can get an api key once you've registered on the 

[https://openweathermap.org](https://openweathermap.org/) website.

<br />

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.


### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
