## React Redux Exercise

On Day 12, you made a grocery list using React. In this exercise you will create the same application using redux for state management.

### Specifications:

- Create an input box and a button. User should be able to add grocery items and click the `add` button to add it to the list displaying the item.

- Create a button to clear the whole list.

- Clicking on a grocery item should change its color to red. Clicking again should change it back to black. Red means the item has been purchased.

- There should be a `x` button beside each item. Clicking on it should delete the item from the list.

- There should be an `edit` button next to each item. Clicking on it should replace this item with an input box. The input box should have the name of this item. You should be able to change the value and click on `save` button next to the input box. In edit mode, `x` and `add` buttons are not visible for this item

- On refresh the state of the list should persist.

### Folder Structure:

    - src
      
      - components/
        - ReusableComponent1/
          - ReusableComponent1.js
          - index.js
      
      - config/
        - redux.js

      - redux/
        - actions.js
        - reducers.js
        - constants.js
      
      - screens/
        - Screen1
          - Screen1Container.js
          - Screen1.js
          - index.js

      - styles/
        - App.css
        - Screen1.css
      
      - App.js



### Debugging

[Redux extension for Chrome](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en) is highly recommended for debugging

It looks like this: 

![alt Extension image](./readme/extension.png)

And it will help you a lot to debug and understand what's going with your code.

## Redux

![alt Redux image](./readme/redux.png)

Source https://www.reddit.com/r/webdev/comments/4r1947/i_am_working_on_a_reactredux_video_tutorial/
