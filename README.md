# Mouse Hover Effect

This is a simple demonstration of a mouse hover effect using HTML and CSS.

## Getting Started

To use this mouse hover effect, follow these steps:

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.

## Usage

Simply hover your mouse over the element to see the effect in action.

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mouse Hover Effect</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Hover over me!</h1>
    </div>
</body>
</html>


/* styles.css */

.container {
    width: 200px;
    height: 100px;
    background-color: #3498db;
    color: #fff;
    text-align: center;
    line-height: 100px;
    font-size: 24px;
    transition: background-color 0.3s ease;
}

.container:hover {
    background-color: #2980b9;
}


In this example, hovering over the `<div>` element with the class `container` triggers a background color change using CSS transitions. You can customize the HTML and CSS according to your preferences and needs.


