#  React JS Project - Youtube (Entertainment)

## What is the use of this Repo

This Project is a Simple ReactJS Project which demonstrates the following
1. Creating a Component in React
2. Making HTTP calls
3. Communicating between parent and child component
4. Using Bootstrap along with React
5. Using Basic Routing in React

The project Template can be used to build bigger projects

## Live Application URL

### 
This URL has the application deployed in

## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g create-react-app
```
## Live Application URL



Click on the link to see the application

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**

## Application design

#### Components

1. **App** Component : This Component is entry point of react appliation and main container componet which is rendered in index.html and also contains routing for this app.
      https://reactrouter.com/en/main/start/tutorial

3. **MainContainer** Component : This Component Displays the details of all videos and list in two seperate components  VideoContainer and buttonlist

4. **VideoContainer** Component : This component uses following react concepts to handle data 
                      1. Props handling -- https://legacy.reactjs.org/docs/components-and-props.html 
                      2. List display -- creation of key  https://legacy.reactjs.org/docs/lists-and-keys.html 
                      3. React hooks : useEffect https://legacy.reactjs.org/docs/hooks-effect.html 
                      4. Api call

6. **ButtonList** Component : This component contains all categories for youtube videos .
7. **CommentsContainer** Component : This component demonstrates how we can use power of recursion to have infinite comments for user .

#### HTTP client

Fetch data apis are  used to make HTTP Calls

#### URL

The application has just one url /customerlist which ties to *Customers* Component

## Resources

**create-react-app** : The following link has all the commands that can be used with create-react-app
https://github.com/facebook/create-react-app

**ReactJS** : Refer to https://reactjs.org/ to understand the concepts of ReactJS

**React Bootstrap** : Refer to https://react-bootstrap.github.io/getting-started/introduction/ to understand how to use React Bootstrap
