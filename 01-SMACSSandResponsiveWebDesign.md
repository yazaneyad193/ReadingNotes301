# Responsive Web Design

* why we use responsive design? *
>Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive web design is focused around providing an intuitive and gratifying experience for everyone. Desktop computer and cell phone users alike all benefit from responsive websites.


### Flexible Layouts

- Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media.

1.  flexible layouts:

- is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width.

2. flexible grids:

- are built using relative length units, most commonly percentages or em units.

3. media queries:

- provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example. Being able to apply uniquely targeted styles opens up a world of opportunity and leverage to responsive web design.

### why Initializing Media Queries :

- Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called “text wrap”. Here is an example of that.

### What are floats used for?

- Floats are also helpful for layout in smaller instances. Take for example this little area of a web page. If we use float for our little avatar image, when that image changes size the text in the box will reflow to accommodate.

### Clearing the Float:

- Float’s sister property is clear. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. Again an illustration probably does more good than words do.

### The Great Collapse:

- One of the more bewildering things about working with floats is how they can affect the element that contains them (their “parent” element). If this parent element contained nothing but floated elements, the height of it would literally collapse to nothing. This isn’t always obvious if the parent doesn’t contain any visually noticeable background, but it is important to be aware of.


### Techniques for Clearing Floats:
1- The Empty Div Method

2- The Overflow Method

3- The Easy Clearing Method
