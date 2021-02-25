# sheldonize

Do you know Sheldon from the Big Bang theory?

Great, now do you remember him knocking on Penny's door?

If not, check <https://www.youtube.com/watch?v=jrzUsHNGZHc>

## Description

Let us write a function called *sheldonize*.

Parameters:
- n: a positive number
- name: a string with a name

Here is the header of the function
```javascript
    function sheldonize(n, name) {
        // your code here
    }
```

### Functionality

- Returns an Array/List instance of *n* length
- In each element, per index:
  + writes **Knock** index times, joined by commas
  + Append the **name**

### Example

Sample call, in javascript:

```javascript
    sheldonize(3, "Penny");
```

Should return

```json
    [
        "Knock Penny",
        "Knock, Knock Penny",
        "Knock, Knock, Knock Penny"
    ]
```