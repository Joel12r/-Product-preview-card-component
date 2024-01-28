![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

# Product Preview Card Component

This is a simple product preview card component built using HTML, CSS, and Bootstrap. It displays a product image along with its description and pricing, providing users with a brief overview of the product.

## Usage

To use this product preview card component, follow these steps:

1. Clone or download this repository.
2. Open the `index.html` file in your preferred web browser.

## Preview

![Product Preview Card](./preview.png)

## Technologies Used

- HTML
- CSS
- Bootstrap 5.3.2

## Structure

The main structure of the HTML file (`index.html`) is as follows:

- `head`: Contains meta tags, viewport settings, and links to external stylesheets and favicon.
- `body`: Contains the main content of the product preview card.
  - `main`: Contains the product preview card within a container.
    - `div.container`: Bootstrap container to center the content.
      - `div.row`: Bootstrap row to organize content horizontally.
        - `div.card`: Bootstrap card component to display the product preview.
          - `div.row`: Nested row to split the card into two columns.
            - `div.col-lg-6.col-md-12.p-0`: Column for the product image.
            - `div.col-lg-6.col-md-12.perfume-description`: Column for the product description and pricing.
              - Various HTML elements for product details like title, description, and pricing.
              - Add to Cart button.
  - `footer`: Contains attribution information about the challenge and coder.

## Credits

This project is based on a challenge provided by [Frontend Mentor](https://www.frontendmentor.io?ref=challenge). The code was coded by [Joseph Ekali Moyenda](#).

Feel free to customize and enhance the code as per your project requirements. If you have any questions or suggestions, feel free to contact me. Enjoy coding!