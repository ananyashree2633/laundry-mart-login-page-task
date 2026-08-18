# Laundry Services Hero Section

## About the Project

I created this Laundry Services Hero Section using HTML and CSS.

The page contains a navbar and a hero section. The navbar has
the logo, navigation links and the user's name. The hero section
contains a heading, description, button and a laundry-related image.

## What I Learned

While making this project, I learned how to use `display: inline-block`
to place different sections next to each other.

I also learned how viewport units work.

I used:

- `vw` for width and font sizes
- `vh` for height and spacing

I also learned that using too many viewport heights together can
make the page larger than the screen and cause scrolling.

## How I Built It

### Step 1 - Navbar

First, I created the navbar with the logo, navigation links and
user name.

I used `display: inline-block` instead of Flexbox because Flexbox
was not allowed in this task.

I tested the navbar in the browser before creating the hero section.

### Step 2 - Hero Section

After completing the navbar, I created two divs for the hero section.

The first div contains:

- Heading
- Description
- Book a Service Today button

The second div contains a laundry image.

I used `display: inline-block` to keep the two sections side by side.

### Step 3 - Viewport Units

I used `vh` and `vw` to make the section fit according to the
browser screen size.

I initially faced a small scrolling problem because the heights
and spacing added up to more than the screen height.

I fixed this by keeping the navbar at `12vh` and the hero section
at `88vh`.

## Technologies Used

- HTML
- CSS

## Important CSS Concepts

- display: inline-block
- vw
- vh
- padding
- margin
- box-sizing
- background-color
- border-radius
- hover effect

## Restrictions

I did not use:

- Flexbox
- Bootstrap

## Files

- index.html
- style.css
- README.md

## How to Run

Open `index.html` in a browser to view the project.

## Author

Ananya Shree