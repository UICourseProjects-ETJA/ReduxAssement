## Redux assessment 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
The starter code was cloned from [Doggiegram](https://github.com/Thinkful-Ed/starter-redux-assessment).

# short-answer question
Describe the biggest challenge you faced when implementing the Favorite Like/Toggle logic and explain the approach you used to solve it.
  > The biggest challenge for implementing the Like/toggle logic was remembering the syntax for conditional renderig. Looking through previous lessions and othe assignments I had completed helped me figure out what I was missing

# Post Submission Reflection
1. Explain how you designed and implemented the Redux store for this project. What state did you choose to centralize, and why?
   > In this project, my redux store contained Photo, Store and Search state. I chose to centrlize the state for these three objects as it
   made the data that each object represented easily accessible to each other across components while minimizing the risk of confusion/bugs.
   furthermore, centralizing the state made debugging any issue that came up easier to fix.

3. Explain one key technical decision you made during your implementation. Why did you choose this approach over other possible solutions?
   > When retrieving the imageUrl and caption from the suggestion selector, I chose to initialize the variables on the same line (ie: const{imageUrl, caption} = useSelector(selectSuggestion)) verses using individual lines. Though a small design choice, initializing variables on the same line reduces code complexity and increases code readability, which can greatly help with understanding code flow and debugging
   
4. AI use disclosure
   > no ai tools (ChatGPT, Copilot, Claude, DeepSeek, Gemini, etc.) were used in the completion of this assesment 

## Available scripts

In the project directory, you can run the following commands:

### `npm install`

Installs the project dependencies, including Redux packages such as @reduxjs/toolkit and react-redux.

### `npm run dev`

Runs the React app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

Runs an Express API at `http://localhost:3004` that exposes a single endpoint, `GET /api/suggestion`, which returns a dog suggestion at random.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Runs the test suites.



