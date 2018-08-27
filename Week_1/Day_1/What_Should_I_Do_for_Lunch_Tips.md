### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript

function whatToDoForLunch(hungry, availableTime) {
  if (hungry === true && availableTime < 20) {
    console.log("Pick something up and eat it in the lab.")
  } else if (hungry === true && availableTime >= 20 && availableTime <= 30) {
    console.log("Find somewhere close by to eat.")
  } else if (hungry === true && availableTime > 30) {
    console.log("We’re in a bootcamp.")
  } else if (hungry === false) {
    console.log("Get back to work.")
  } else {
    console.log("I don’t know what to do!");
  }
}

```

