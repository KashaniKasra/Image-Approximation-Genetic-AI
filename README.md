
# Image Approximation Using Genetic Algorithms

This project utilizes **Genetic Algorithms (GA)** to approximate target images by evolving populations of shapes to resemble the original image. The process involves iterative improvements guided by fitness evaluations.

## Files Overview

### Notebook
- **AI_CA2_Notebook.ipynb**: Contains the implementation of the genetic algorithm for image approximation, including:
  - Initialization of the population with random shapes.
  - Fitness evaluation based on similarity to the target image.
  - Genetic operations: selection, crossover, and mutation.
  - Visualization of the approximation process.

### Instructions
- **Instruction.pdf**: Provides detailed guidelines for the project, including:
  - The problem statement and objectives.
  - Steps to implement the genetic algorithm.
  - Requirements and deliverables.

### Supporting Documents
- **README.md**: Overview of the project structure and contents (this file).
- **Report.pdf**: Contains detailed documentation, including:
  - Explanation of the genetic algorithm and its components.
  - Performance metrics and analysis.
  - Insights and conclusions.

### Additional Files
- **target_images.zip**: Contains the target images used for approximation.

## Usage

1. Open the notebook `AI_CA2_Notebook.ipynb` in Jupyter Notebook or a compatible IDE.
2. Extract the `target_images.zip` file and place the images in the appropriate directory.
3. Run the notebook step-by-step to observe the image approximation process.
4. Refer to `Instruction.pdf` for detailed problem requirements and deliverables.

## Requirements
- Python 3.x
- Libraries: `random`, `PIL`, `numpy`, `matplotlib`, `cv2`, `math`

## Key Features

- **Genetic Operations**:
  - **Selection**: Chooses the most fit individuals for reproduction.
  - **Crossover**: Combines features of parent individuals to create offspring.
  - **Mutation**: Introduces random changes for diversity.

- **Visualization**:
  - Real-time plotting of the approximation process to monitor improvements.

- **Scalable**:
  - Works with different target images and adjustable genetic parameters.

## Insights

The notebook demonstrates the power of genetic algorithms in solving complex optimization problems like image approximation. By iteratively evolving populations, the algorithm achieves a close resemblance to the target image.

For more details, refer to the **Instruction.pdf** and **Report.pdf**.
