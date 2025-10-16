# Vector Projection Visualizer

## 🎯 Project Goal

This project implements the fundamental mathematical concept of **2D vector projection** ($\text{proj}_{\mathbf{b}}(\mathbf{a})$) using NumPy and provides a visual proof using Matplotlib. The goal is to rigorously demonstrate the geometric relationship between the input vector ($\mathbf{a}$), the target vector ($\mathbf{b}$), and the resulting projected vector.

## ✨ Features

-   **`vector_projection(a, b)`:** Robust function for calculating the projection, including essential zero-vector error checking.
-   **Visualization:** Generates a plot (`outputs/projection_plot.png`) showing all vectors and the **orthogonal residual line**, visually confirming the projection's correctness.

## 🛠️ Setup and Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/LukeWardle/vector-projection-tool.git](https://github.com/LukeWardle/vector-projection-tool.git)
    cd vector-projection-tool
    ```

2.  **Create and Activate Virtual Environment:**
    ```bash
    # Create the environment
    python -m venv venv
    # Activate the environment (Windows/PowerShell)
    .\venv\Scripts\Activate.ps1
    ```

3.  **Install Dependencies:**
    This project requires `numpy` and `matplotlib`.
    ```bash
    pip install numpy matplotlib
    ```

## 🚀 Usage

Execute the main script to run the calculation and generate the plot:

```bash
python src/projection_visualizer.py
