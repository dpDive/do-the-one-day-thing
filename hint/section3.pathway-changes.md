
### Beginning
The section of code should look like this at first:
```js
var sequence = {
  run: {
    walk: {
      run: "Nope"
    }
  },
  walk: {
    walk: "Nope"
  },
}
```

### Change1
The section of code should look like this after this change:
```js
var sequence = {
  run: {
    walk: {
      run: "Nope"
    }
  },
  walk: {
    walk: "Nope",
  },
  jump: {
    run: true
  },
}
```

### Change2
The section of code should look like this after this change:
```js
var sequence = {
  run: {
    walk: {
      run: "Nope"
    }
  },
  walk: {
    walk: "Nope",
  },
  jump: {
    walk: "Nope", //Hint: This line contains the difference
    run: true
  },
}
```

### Change3
The section of code should look like this after this change:
```js
var sequence = {
  run: {
    walk: {
      run: "Nope"
    }
  },
  walk: {
    walk: "Nope",
    run: {
      jump: true
    }
  },
  jump: {
    walk: "Nope", //Hint: This line contains the difference
    run: true
  },
}
```
