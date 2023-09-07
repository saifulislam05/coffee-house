# Coffee House Ass-4 CSS

## Hosted Link
You can view the project live at [Coffee House](https://saifulislam05.github.io/coffee-house/)

## Project Description
The Coffee House project showcases a simple web page for a coffee house, designed using HTML and CSS. It features a navigation section, a coffee menu, and various coffee descriptions. This README.md provides an overview of the project's structure and highlights the CSS properties used for each section.

## HTML Structure

### Navigation Section (`<nav>`)
![image](https://github.com/saifulislam05/coffee-house/assets/73392705/4f4e9440-de70-4587-9858-513646118c9b)

- The navigation section includes a search input field with a sticky position.
- It has a background image with a cover effect and a shadow.

### Coffee Menu (`<section class="coffee_menu">`)
![image](https://github.com/saifulislam05/coffee-house/assets/73392705/b44375a2-70c8-42ac-874c-9dd4f2f7c794)

- The coffee menu section displays coffee items with images and names.
- Each coffee item has a circular image with a hover effect.

### Coffee Descriptions (`<section class="coffee_des">`)
![image](https://github.com/saifulislam05/coffee-house/assets/73392705/18bc1a38-5446-42e1-82a9-9a1c3d676859)
![image](https://github.com/saifulislam05/coffee-house/assets/73392705/9daf1608-f7b1-44ed-9c05-d5bd88754d22)

- The coffee descriptions section contains information about the coffee house.
- It has multiple paragraphs with a brown heading for Coffee List.

## CSS Styles and Properties

### Global Styles (`*`)
- Resets margin, padding, and box-sizing for all elements to create a consistent layout.

### Navigation Section (`nav`)
- `.nav`:
  - `width: 100%;`: Makes the navigation span the entire width.
  - `height: 300px;`: Sets the height of the navigation section.
  - `background`: Sets a background image for the navigation.
  - `position: sticky;`: Makes the navigation stick to the top while scrolling.
  
- `.nav input`:
  - `width: 70%;`: Sets the width of the search input.
  - `height: 60px;`: Defines the input's height.
  - `background`: Styles the input's background.
  - `color: #ffffff;`: Sets text color.
  - `border-radius: 10px;`: Adds rounded corners to the input.
  - `position: sticky;`: Makes the input stick to the top.
  
- `.nav input::placeholder`:
  - `color: #ffffff;`: Styles the placeholder text color.

### Coffee Menu (`.coffee_menu`)
- `.coffee_menu`:
  - `display: flex;`: Displays coffee items horizontally with space between them.
  - `align-items: center;`: Aligns items vertically in the center.
  - `justify-content: space-evenly;`: Distributes items evenly along the horizontal axis.

- `.coffee_menu .box`:
  - `display: flex;`: Arranges each coffee item in a column with centered content.
  - `flex-direction: column;`: Sets the flex direction to column.
  - `align-items: center;`: Centers items vertically.
  - `justify-content: center;`: Centers items horizontally.

- `.coffee_menu .box .image img`:
  - `width: 100%;`: Sets the image width to 100%.
  - `height: 100%;`: Sets the image height to 100%.
  - `border-radius: 50%;`: Creates a circular shape for the image.
  - `box-shadow: 0px 8px 8px black;`: Adds a shadow to the image.

- `.coffee_menu .box h4`:
  - `margin-block: 15px;`: Sets the margin around the heading.
  - `color: rgba(0, 0, 0, 0.8);`: Sets the heading color.

- `.coffee_menu .box .image img:hover`:
  - `height: 152px;`: Increases the image height on hover.
  - `width: 152px;`: Increases the image width on hover.
  - `box-shadow: 0px 18px 18px black;`: Adds a larger shadow on hover.

### Coffee Descriptions (`.coffee_des`)
- `.coffee_des`:
  - `width: 90%;`: Sets the width of the coffee descriptions.
  - `margin: auto;`: Centers the content horizontally.
  - `margin-block: 50px;`: Sets margin at the top and bottom.
  - `background-color: rgb(165, 42, 42, 0.3);`: Defines the background color with transparency.
  - `padding: 30px;`: Adds padding around the content.
  - `border-radius: 5px;`: Adds rounded corners to the container.
  - `box-shadow: 0px 0px 8px #a52a2a;`: Adds a shadow to the container.

- `.coffee_des h1`:
  - `color: #a52a2a;`: Sets the heading color.

- `.coffee_des p, .coffee_des ol`:
  - `line-height: 20px;`: Sets the line height.
  - `color: #a52a2a;`: Sets text color.

- `.coffee_des ol li`:
  - `padding: 5px;`: Adds padding to list items within the ordered list.
