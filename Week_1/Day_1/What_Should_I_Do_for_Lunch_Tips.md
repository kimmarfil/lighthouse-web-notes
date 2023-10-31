### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```Javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    console.log("You're not hungry, get back to work.");
  } else if (availableTime < 20) {
    console.log("You're hungry and have less than 20 minutes, pick up a snack or grab something you have ready at home.");
  } else if (availableTime <= 30) {
    console.log("You're hungry and have between 20 and 30 minutes, take a break and cook a tasty meal.");
  } else {
    console.log("You're hungry but have more than 30 minutes, reconsider as you're in an intense program.");
  }
};
```