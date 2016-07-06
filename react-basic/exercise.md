# React Basics

1. What do you understand by the virtual-dom ? How is it different from the actual html dom ?
2. How are JSX tags different from html tags ?
3. Why is this invalid:
    ```jsx
        render: funtion() {
            return (
                <div></div>
                <div></div>
            );
        }
    ```
    How would you rectify it ?

4. Write a component `Dashboard` that has two components `SearchBox` and `Users`.
   `Users` return a list of users having name and gender.
   `SeachBox` contains an input field.
5. In a React component, you have this input field, `<input type="text" ref="name"/>`, how would you get the name?
6. What is the difference between `state` and `props` ? When would you prefer using a `state` rather than a `prop`? Show with example.  
7. What are the component life cycles ? What is the use of `getInitialState`, `getDefaultProps` and `shouldComponentUpdate`?
8. What are propType validations ? show an example that checks wether a propType either an `object` or an `array`.
9. How is React events different from Javascript events ? What advantage does that provide over normal Events ?
10. Write a component called `FormContent`, that has an `input` field and a `span`. Add an event handler to the input, such that, whatever one types in the input appears in the span.
11. What is the advantage of using a `key` in a React component ?