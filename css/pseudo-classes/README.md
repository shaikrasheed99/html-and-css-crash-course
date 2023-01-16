# CSS Pseudo Classes

Pseudo Class is used to give special state to the elements. 

Pseudo Classes are divided into two types. 
1. `Dynamic` - based on the behavior of user
2. `structural` - based on the parent-child relationship

## Dynamic

* Changes the color of link when we hover on it.
    ```css
    a:hover {
    color: #FF00FF;
    }
    ```
* Changes the color of link when we focus on it. 
```css
a:focus {
  color: #FF0000;
}
```

* Changes the color of link when we have already visited it. 
```css
a:visited {
  color: #00FF00;
}
```

* Change the color of active link. 
```css
a:active {
  color: #0000FF;
}
```

* Change the color of link only if it is valid. 
```css
a:valid {
  color: #0000FF;
}
```

## Structural

* Changes the text color of first child of p type. 
```css
div p:first-child {
  color: #FF00FF;
}
```

* Changes the text color of last child of p type. 
```css
div p:last-child {
  color: #FF00FF;
}
```

* Changes the text color of first child of only p type. 
```css
div p:first-of-type {
  color: #FF00FF;
}
```

* Changes the text color of last child of only p type. 
```css
div p:last-of-type {
  color: #FF00FF;
}
```

* Changes the text color of 2nd child of p type. 
```css
div p:nth-child(2) {
  color: #FF00FF;
}
```

* Changes the text color of even child of p type. 
```css
div p:nth-child(even) {
  color: #FF00FF;
}
```

* Changes the text color of odd child of p type. 
```css
div p:nth-child(odd) {
  color: #FF00FF;
}
```

* Changes the text color of 2nd child of only p type. 
```css
div p:nth-of-type(2) {
  color: #FF00FF;
}
```