# Assignment-Flexbox-Fundamentals-
JTC-Assignment: Flexbox Fundamentals 

## Ask ChatGPT:

Can you generate Flexbox code for a navbar and explain each property?

---

## Example: Flexbox Navbar

```html
<nav class="navbar">
  <div class="logo">Logo</div>
  <ul class="nav-links">
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

```css
.navbar {
  display: flex;                /* Enables Flexbox layout */
  justify-content: space-between; /* Spaces out children (logo and links) */
  align-items: center;            /* Vertically centers items */
  padding: 1rem 2rem;             /* Adds space inside navbar */
  background: #222;               /* Navbar background color */
  color: #fff;                    /* Text color */
}

.nav-links {
  display: flex;                  /* Makes nav links a flex container */
  gap: 1.5rem;                    /* Adds space between links */
  list-style: none;               /* Removes default list styling */
  margin: 0;                      /* Removes default margin */
  padding: 0;                     /* Removes default padding */
}

.nav-links a {
  color: #fff;                    /* Link text color */
  text-decoration: none;          /* Removes underline */
  font-weight: 500;               /* Makes text a bit bolder */
}
```

### Explanation of Flexbox Properties

- `display: flex;`  
  Turns the container into a flexbox, enabling flex properties for its children.

- `justify-content: space-between;`  
  Distributes space between children, pushing the first to the left and the last to the right.

- `align-items: center;`  
  Vertically centers the children within the navbar.

- `gap: 1.5rem;`  
  Adds consistent spacing between flex items (links).

- `flex-direction` (not shown, defaults to `row`):  
  Controls the direction of the flex items (row or column).

# Result:

Implemented all suggested changes and commented out old code used when following the Odin Project


