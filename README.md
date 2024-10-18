# Pixel-Hack: The Art of Pixelized Repurposing

**Pixel-Hack** is a fun project that transforms discarded second-hand chopsticks into a vibrant pixelated sculpture using advanced image processing and custom algorithms. This project merges sustainability with creative technology, offering a unique approach to recycling through art.

## Project Overview

This project began with the goal of turning waste into art by repurposing chopsticks. Using color quantization techniques, we reduced a digital image to six distinct colors. We then implemented a **circle packing algorithm** to efficiently place over 5,200 chopstick pieces, each acting as a "pixel" in the final sculpture. Custom algorithms calculated the exact number of pieces needed for each color, ensuring minimal waste and precise execution.

## Features

- **Recycled Materials**: Over 5,200 second-hand chopsticks were collected, cleaned, and repurposed.
- **Color Quantization**: Reduced the original image to six colors for efficient material usage.
- **Custom Algorithms**: Implemented to calculate and pack chopsticks into a cohesive pixelated structure.
- **Sustainability**: This project emphasizes sustainable art by upcycling waste materials.
  
## Tech Stack

- **Python**: For image processing and custom algorithm development.
- **Circle Packing Algorithm**: For optimal arrangement of chopsticks.
- **Physical Assembly**: Using recycled chopsticks as pixels in the final artwork.

## How to Run

1. Clone this repository:
   ```
   git clone https://github.com/username/algosticks
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the image processing and layout generation:
   ```
   python algosticks.py
   ```