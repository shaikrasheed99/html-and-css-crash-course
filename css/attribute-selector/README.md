# CSS Attribute Selector

Attribute Selector is used to select the element which has attributes. 

Square brackets [] are used to select the elements. `[]`

* `div[class]` - selects all the `div` elements which has `class`
* `div[id]` - selects all the `div` elements which has `id` 
* `div[class="something"]` - selects all the `div` elements whose class value is `something`
* `a[href^="https"]` - selects all the `a` elements whose href value begins with `https`
* `a[href$=".com"]` - selects all the `a` elements whose href value ends with `.com`
* `a[href*="google"]` - selects all the `a` elements whose href value contains the substring `google`
* `a[href|="github"]` - selects all the `a` elements whose href value starting with `github`
* `a[href~="youtube"]` - selects all the `a` elements whose href value contains the word `youtube`

```css
a[href*="anyword"] {
    color: pink;
}
```