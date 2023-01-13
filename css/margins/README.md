# CSS Margins

CSS Margins are used to create outside space around the elements. 

We can specify margin for each side with the help of below properties. 
* `margin-top`
* `margin-right`
* `margin-bottom`
* `margin-left`

We have multiple shorthands to define margins. 

1. `margin` can have four values.

    ```css
    margin: 1px 2px 3px 4px;
    ```

    * `top` has 1px of margin
    * `right` has 2px of margin
    * `bottom` has 3px of margin
    * `left` has 4px of margin

2. `margin` can have three values.

    ```css
    margin: 1px 2px 3px;
    ```

    * `top` has 1px of margin
    * `right` & `left` has 2px of margin
    * `bottom` has 3px of margin

3. `margin` can have two values. 

    ```css
    margin: 1px 2px;
    ```

    * `top` & `bottom` has 1px of margin
    * `right` & `left` has 2px of margin

4. `margin` can have only one value. 

    ```css
    margin: 1px;
    ```

    * `top` & `bottom` & `right` & `left` has 1px of margin

`auto` value of margin can be used to center elements.

```css
margin-left: auto;
margin-right: auto;
```