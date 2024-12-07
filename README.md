# Sorting Visualizer

Sorting Visualizer is an interactive tool designed to help you visualize and understand various sorting algorithms in action. This project provides real-time graphical representation of sorting processes, making it an excellent learning resource for students and developers interested in algorithms.

## Features

- **Supported Algorithms**:
  - Selection Sort
  - Insertion Sort
  - Bubble Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
- Real-time visualization of the sorting process.
- Ability to generate randomized lists.
- Intuitive keyboard controls to interact with the visualizer.
- Developed using **SDL2**, a cross-platform library for graphics rendering.

## Demo

![Sorting Visualizer Demo](#) <!-- Add a GIF or screenshot here -->

## Prerequisites

Ensure the following are installed on your system:

- [SDL2 Library](https://www.libsdl.org/) (Simple DirectMedia Layer)
- C++ compiler (e.g., g++, clang++)
- Make (optional, for automation)

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/sorting-visualizer.git
   cd sorting-visualizer
   ```

2. **Install SDL2**:
   - For Debian-based systems:
     ```bash
     sudo apt-get install libsdl2-dev
     ```
   - For macOS using Homebrew:
     ```bash
     brew install sdl2
     ```
   - For Windows: Download and set up SDL2 from [SDL's official website](https://www.libsdl.org/).

3. **Build the Project**:
   ```bash
   g++ -o sorting_visualizer sorting_visualizer.cpp -lSDL2
   ```

4. **Run the Program**:
   ```bash
   ./sorting_visualizer
   ```

## Controls

| Key      | Action                                      |
|----------|---------------------------------------------|
| `0`      | Generate a new randomized list             |
| `1`      | Start Selection Sort                       |
| `2`      | Start Insertion Sort                       |
| `3`      | Start Bubble Sort                          |
| `4`      | Start Merge Sort                           |
| `5`      | Start Quick Sort                           |
| `6`      | Start Heap Sort                            |
| `q`      | Exit the Sorting Visualizer                |

## How It Works

1. **Randomized List**: The program generates a random list of values to be sorted.
2. **Visualization**: As each algorithm progresses, changes to the list are displayed graphically using colored bars.
   - Green: Currently being sorted
   - Purple: Comparison
   - Gray: Unsorted
   - Light green: Sorted portion
3. **Interactive Controls**: Use the keyboard to switch algorithms or exit.




## Contributing

Contributions are welcome! If you have ideas to enhance this project or find any issues, feel free to create a pull request or report them in the Issues section.





