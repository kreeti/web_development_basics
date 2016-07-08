# React Advanced

1. Given this dom and functionality, implement its equivalent in React.
    ```html
        <div id="root">
            <input type="text" id="filter"/>
            <ul className="users">
                <li>Amaan</li>
                <li>Awal</li>
                <li>John</li>
                <li>Jane</li>
            </ul>
        </div>
    ```
    when someone types in the text field, filter the users by the name.

2. Given three anchor tags in react:
    ```html
        <a data-page="home">Home</a>
        <a data-page="about">About</a>
        <a data-page="contact">Contact</a>
    ```

    and three components `Home`, `About` and `Contact`. Render `Home` Component when clicked on anchor tag with data page attribute `home`, same for `About` and `Contact`.

3. What is the utility of the history object in javascript? What does pushState method of the history object do ?


4. show an example of a single page app, that has three pages/components `Home`, `Contact` and `About`. Use react-router for the example.

5. What does the `Link` method do ?

6. Give an example where `onEnter` method is used

7. What is the advantage of using a `flux` architecture ?

8. Without using react, use redux to make a counter which increments the value by 1 every second and renders it in the browser.

9. what is the utility of `combineReducers` and `dispatch` method ?

10. What is babel ?

11. Write a gulp or webpack or brunch script to transpile all your javascript codes in `src/` directory and put them in `dist` directory.

12. Also try to put all your js files in one file from the above step.

13. What is a .map file ? What would happen if there were no map files for all of your minified code?

14. Use redux and react and react-router to make a todo app.
    where redux has two stores, `todos` and `currentTodo`, `todos` is an array of objects, containing `text`, `time`, `completed` and `id`,
    and `currentTodo` returns the `id` of the todo being viewed. `id`s are assigned as todos.length + 1.
    The UI will have an interface to `create` a todo, display a list of todos at the bottom. 
    Clicking on a todo opens the todo in a separate page and also provides an options to delete a todo from list.
    One can sort the todos by completed or time. By default the todos should be sorted by oldest uncompleted first.

    Also use the necessary build tools and es6 syntax where possible.