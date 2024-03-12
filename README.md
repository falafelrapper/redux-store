# Fullstack Development Challenge 22

## Table of Contents

- [Welcome](#welcome-to-the-twenty-second-challenge-of-the-ucla-bootcamp)
- [User Story](#user-story)
- [Accceptance Criteria](#acceptance-criteria)
- [Completed Challenge](#the-completed-challenge)
- [Credits](#credits)

## Welcome to the twenty second Challenge of the UCLA Bootcamp!

In this challenge we were supposed to refactor an E-Commerce website, and have it use Redux and Stripe. You should be able to use the website the same way as before, but now with Redux and Stripe implemented. To start, we should follow our user story on what we want to solve:

## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## The Completed Challenge

After completing the challenge, we should now have the same functioning site that is through Render, but now it is refactored to use Redux and Stripe. You can view all here [here](https://redux-store-jd4m.onrender.com)!

## Credits
This refactor was completed by Zachary Roy