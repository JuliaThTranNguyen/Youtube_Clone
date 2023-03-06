# :bulb: Welcome to my Youtube Clone Application :movie_camera:

--------------------------------------------------
![PIC1](https://assets.materialup.com/uploads/6f722931-d27d-437f-875b-587cf196334a/preview.png)
## Requirements:
* Typescript
* Redux Toolkits
* Tailwind 
* Youtube API

## Description :
This is a Clone version of the original Youtube App.

## Set up for coding process:
### NodeJS & npm installation:
[NOdejs documentation](https://nodejs.org/en/download/package-manager/)

[NPM document](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

[Extra document](https://kinsta.com/blog/how-to-install-node-js/)


### React App Installation 

![PIC2](https://i.ytimg.com/vi/nvhwG0Yk1AM/maxresdefault.jpg)

[Extra document](https://beta.reactjs.org/learn/installation)

How to create a typescript application with create-react-app

```
npx create-react-app youtube-clone . --template typescript
```

How to run the app

```
npm start
```

### Heroku set up:

![PIC3](https://s3.stackabuse.com/media/articles/how-to-deploy-a-react-app-to-heroku-1.png)

* 1. Set up Heroku account
* 2. Get to know Heorku with Node
[Links](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
* 3. Install heroku CLI
[Links](https://devcenter.heroku.com/articles/getting-started-with-nodejs)

### Publishing the final product:
* Push up the source code to a Github repository
* Login to heroku through a terminal.

```
heroku login
```


* Navigate to your terminal & run this command:
Run this at first:

```
npm install
npm run build

```


Then wait for it to create a "/build" directory. Continue with:

```
heroku create <name-of-your-choice>
git init
git add .
git commit -m "Initial commit"
git push heroku <the - same - branch - deployed - on - github>

```
<i>Notes: if you already created a .git then you can skip "git init" part. Or you can remove the .git directory & do it over again. </i>


Running the app through Heroku

```
heroku open
```

Debugging the App on Heroku:

```
heroku logs --tail
```

--------------------------------------------------
## :heart:Thank you for your time :heart: