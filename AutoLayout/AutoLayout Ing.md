Translate to English: AutoLayout

When we create a View in a certain screen size, when emulating on other devices, we will see that our elements will be out of order, and this is because smartphones have different screen sizes.
AutoLayout is precisely to avoid this problem. By building a screen in a specific size, we can maintain proportionality in different screen sizes. It works using Constraints, which are "rules" that help maintain the proportionality of the elements.
- In the lower right corner, still in the development area, is where we define the Constraints of the element. After selecting the desired element, the first item from left to right, updates the element to the original location where it will be arranged, and the second item we can define Alignment Constraints, which serve to 'fix' an element vertically or horizontally.
- The Constraints only appear for the selected Elements, and each form of Constraints are the opposite of the position they define.
- To delete a Constraint, select it with the mouse (wait for it to appear clearer and then click) and press BackSpace, which works as the delete button.
- The third item from left to right in the lower right area of ​​the development environment, it is where we can create our Constraints. When selecting an element, we open the environment to create Constraints and, when selecting the line of the desired Constraint, it will turn red and then we can add the value and add it to the element.
- In the development environment, it is not recommended to use the entire device screen, we have an upper and lower margin to start developing, this margin is called 'Safe Area', which is where the device displays time, internet connection, battery and etc...
- By clicking on an element and clicking on a Constraint, in the properties area on the right, we can change its values.
- If we do not use Constraints, the View document will warn that it is missing to place Constraints on the specific element, and will present an error.
- Lines - If the Element has a very large text, you can change its property from lines to show more text, and a very important point is that if you put the number of lines as '0', the software itself will make arrangements to define how many lines are needed to show all text.
- To copy an element, we can use both command(cntrl) + C and command(cntrl) + V or hold down the optional(Alt) button click on the element and drag.

Tips: During simulator use do not close it to return to development minimize and press pause button next to build button on left.
Another tip is to use shortcut: Command + R to start emulation.

We can conclude that in order to keep an element in a certain position we can mix both size constraints as well as alignment constraints making it easier to build our view.
