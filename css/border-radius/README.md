# CSS Border Radius

CSS Border Radius property is used to create rounded of the elements. 

We can specify `border-radius` for each edge with the help of below properties. 
* `border-top-left-radius`
* `border-top-right-radius`
* `border-bottom-left-radius`
* `border-bottom-left-radius`

We have multiple shorthands to define `border-radius`. 

1. `border-radius` can have four values.

    ```css
    border-radius: 1px 2px 3px 4px;
    ```

    * `top-left` edge has 1px of border radius
    * `top-right` edge has 2px of border radius
    * `bottom-right` edge has 3px of border radius
    * `bottom-left` edge has 4px of border radius

2. `border-radius` can have three values.

    ```css
    border-radius: 1px 2px 3px;
    ```

    * `top-left` edge has 1px of border radius
    * `top-right` & `bottom-left` edges has 2px of border radius
    * `bottom-right` edge has 3px of border radius

3. `border-radius` can have two values. 

    ```css
    border-radius: 1px 2px;
    ```

    * `top-left` & `bottom-right` edges has 1px of border radius
    * `top-right` & `bottom-left` edges has 2px of border radius

4. `border-radius` can have only one value. 

    ```css
    border-radius: 1px;
    ```

    * `top-left` & `top-right` & `bottom-right` & `bottom-left` edge has 1px of border radius