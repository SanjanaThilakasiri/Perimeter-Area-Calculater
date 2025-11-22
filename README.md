# Shape Calculator (Java Swing)

[![Java](https://img.shields.io/badge/Java-17-blue)](https://www.java.com/)

## Project Overview
Shape Calculator is a Java Swing-based GUI application that allows users to calculate the **Perimeter** and **Area** of common geometric shapes. The application supports multiple shapes including **Square, Rectangle, Triangle, Circle, Semicircle, Parallelogram, and Rhombus**. It provides an easy-to-use interface with labeled input fields, output display, and clear functionality.

---

## Features
- **Shape Selection:** Choose from Square, Rectangle, Triangle, Circle, Semicircle, Parallelogram, or Rhombus.
- **Perimeter Calculation:** Calculate perimeter of selected shape based on user input.
- **Area Calculation:** Calculate area of selected shape based on user input.
- **Dynamic Inputs:** Input fields are enabled/disabled depending on selected shape.
- **Clear Functionality:** Reset all inputs and output with a single click.

---

## Supported Shapes and Input Requirements

| Shape        | Inputs Required                          | Perimeter Formula                     | Area Formula                               |
|-------------|------------------------------------------|--------------------------------------|-------------------------------------------|
| Square      | Side                                     | 4 × side                              | side × side                                |
| Rectangle   | Width, Length                             | 2 × (width + length)                  | width × length                             |
| Triangle    | Side1, Side2, Side3, Base, Height        | side1 + side2 + side3                 | (base × height) / 2 (or Heron's formula)  |
| Circle      | Radius                                    | 2 × π × radius                        | π × radius²                                |
| Semicircle  | Radius                                    | π × radius + 2 × radius               | (π × radius²) / 2                          |
| Parallelogram| Base, Side, Height                        | 2 × (base + side)                      | base × height                              |
| Rhombus     | Side, Diagonal1, Diagonal2               | 4 × side                               | (diagonal1 × diagonal2) / 2               |

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/shape-calculator.git
2. **Open in NetBeans or any Java IDE that supports Swing GUI.**

3. **Compile and run the Calculater.java file.**

## Usage

- Select a shape from the dropdown menu.

- Enter the required dimensions in the enabled input fields.

- Choose Perimeter or Area using the radio buttons.

- View the calculated result in the output field.

- Click Clear to reset inputs and output.

# Screenshots
<img width="292" height="493" alt="image" src="https://github.com/user-attachments/assets/e240a3cb-1991-4671-8c12-c86ddf6256ea" />
<img width="289" height="497" alt="image" src="https://github.com/user-attachments/assets/6910d0fe-0ce2-4da6-899d-614ef33bbce1" />



# Notes

- Ensure you enter numeric values in all required fields to avoid errors.

- Circle and semicircle calculations use Math.PI for precise results.

- Triangle area calculation uses base × height / 2; for all sides, Heron’s formula is recommended.

# Author

Sanjana Thilakasiri
