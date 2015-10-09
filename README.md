# pure-css-rating
Simple rating on pure CSS, based on tilde (~)

# What is tilde?
Tilde (~) is sibling selector from CSS3, that selects all siblings elements running after current

# Example
```
<li>item</li>
<li class="current">item</li>
<li>item</li>
<li>item</li>
```
```
.current ~ li {
	font-weight: bold;
}
```
* item
* item
* **item**
* **item**
