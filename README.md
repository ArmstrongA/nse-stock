

## Create React App

This project was created using 'create-react-app'.

To run the project type : yarn start
This will work when you have node installed on your computer

## React Router 4

Declarative routing was implemented with React Router 4. HashRouter was used for compatibility with GitHub pages.

## Animations

Crossfades between pages and component transitions were created with CSS and the help of TransitionsGroup and CSSTransitions from react-transitions-group.

## Sass & BEM

I used SCSS and followed BEM (Block Element Modifier) methodology to write the styles for the components that make up this application.

## Axios

Axios was used to make AJAX calls. The Search function on the Stock Quote pages makes use of axios's CancelToken feature.
By caching the searches and using cancel tokens I was able to greatly reduce the number of API calls.

## World Trading Data

The data for this application comes World Trading Data. Sign up for a free account [here](https://www.worldtradingdata.com/).

## Highcharts

Data visualizations use Highcharts - Highstock and the official React Wrapper.
