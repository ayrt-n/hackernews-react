# Hackernew Clone using GraphQL

## Overview

Implementation of a Hackernews clone frontend using React with Apollo Client and a GraphQL backend from https://www.howtographql.com/react-apollo/0-introduction/. Features displaying list of top or new links (with pagination), searching list of links, handling user authentication, allowing authenticatd users to create ne links and upvote links, as well as real time updates for upvotes or new links (using GraphQL subscriptions).

Having gained some exposure to working with REST APIs from the frontend, I have wanted to start digging into and learning about GraphQL, given increased popularity and growing community. This marks one of the first of many future GraphQL projects!

## Installation

To install and test locally yourself:

1. Clone this repo
2. Navigate to the main directory of the cloned repo
3. Install the required packages by running

```
$ npm install
```
4. Start the app by running (this should also open up a browser and naviagte to http://localhost:3000

```
$ npm start
```
5. In another terminal window, navigate to the server folder located at ./hackernews-react/server/
6. Start the backend server by running

```
$ yarn dev
```

You should now be able to see and interact with everything in the browser at http://localhost:3000.
