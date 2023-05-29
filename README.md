# The appointment scheduler

This project is a very simple React application that allows you to view, add and delete some scheduled appointments (in this case, for pets at a vet's office).

## Some additional details

Right now, this React app loads data from a [JSON](./public/data.json) file. Each entry in the file represents an appointment. The application on start will display a list of all of these appointments. This list can be sorted and ordered, as well as searched through.

There is also a delete and add ability - HOWEVER, this will not actually modify the data in the JSON file. It instead will only modify the list in its current state (ie. upon page refresh or server restart, the list will default back to whatever is in the JSON file).

New ideas/issues are currently listed in a [Github Project](https://github.com/users/vpatel22/projects/1) and will be worked on eventually!

## Some background context

This project is heavily based off of the [React.js: Building an Interface](https://www.linkedin.com/learning-login/share?account=103733490&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Freact-js-building-an-interface-8551484%3Ftrk%3Dshare_ent_url%26shareId%3DCaFXy6axSzmkDK8h17VdGw%253D%253D) LinkedIn Learning course by Ray Villalobos. Feel free to take a look at the [Github Repo](https://github.com/LinkedInLearning/react-interface-2880067) for that project as well.

This project started with the base [Create React App](https://github.com/facebook/create-react-app) application and was heavily modified from that point. It also uses **Tailwind.css** for some custom styling.

## Differences between this and the LinkedIn project

Currently, there are no large differences in how this application looks and functions vs the one that exists for the course. Configuration-wise, the only big difference is that we did not have to use CRACO and the other custom packages for working with Tailwind and PostCSS.

## Running this application locally

Start by cloning the repo. Navigate into the project directory and run the following:

```
npm install
npm start
```

This will install the dependencies in the `package.json` file and then start the app in development mode at [http://localhost:3000](http://localhost:3000).
