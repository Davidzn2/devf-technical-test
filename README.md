# Technical Test: News with React and Hooks

Dear candidate,

We are sending you a technical test to evaluate your skills with React and Hooks. The objective of the test is to build a news application that shows news from different categories obtained from an external API.

For this test, it is required that you use React to build the user interface and Hooks to handle state and make API requests. The API to be used is https://newsapi.org/ which allows to obtain news from different sources and categories.

The `APIRequest` component should be responsible for making a `GET` request to the API with a specific category and updating the state with the returned news. In the user interface, a list of news categories will be shown and when one is selected, the state will be updated and the corresponding news obtained from the API will be shown.

## Instructions

1. Create a new React project using `create-react-app`
2. Install the `axios` library to handle HTTP requests
3. Create a new component in your project called `APIRequest`
4. In the `APIRequest` component, import `useState` and `useEffect` from React to handle state and make an API request
5. In the component, set an initial state to save the information returned by the API.
6. Use `useEffect` to make a `GET` request to the desired API when the component mounts. Use `axios.get(url)` to make the request and update the state with the returned information.
7. Use the information from the state to display the data in the user interface.
8. Push your code to a new Github repository and send us the link.
9. Make sure your code is well-documented and easy to understand.
10. It is necessary to obtain an access key from the newsapi.org API to be able to make the requests.
11. The project is configured to ask for the key in the file `src/api/index.js`

If you have any questions or need to clarify something, don't hesitate to ask. We are looking forward to seeing your solution.

Good luck!
