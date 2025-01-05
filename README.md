# Moon Dataset Classification with Gaussian Mixture Models (GMMs)

This repository contains a project to perform non-linear classification on the `moonDataset.csv` using **Gaussian Mixture Models (GMMs)**. The dataset includes features derived from a 2D "moons" structure, with an additional vertical displacement to introduce 3D complexity.

---

## Project Overview

The project involves:
1. **Dataset Exploration and Visualization**: Understanding the 3D structure and data distribution.
2. **Classification using GMMs**: Implementing Gaussian Mixture Models to classify data points into binary classes.
3. **Performance Analysis**: Evaluating the effectiveness of GMMs in handling non-linear decision boundaries.

---

## Dataset Description

The `moonDataset.csv` contains 200 data points across four columns:
- `X1`: Feature derived from the 2D moons structure.
- `X2`: Another feature from the moons structure.
- `X3`: Introduces vertical displacement, creating a 3D effect.
- `Label`: Binary class (0 or 1).

---

## Installation and Setup

### Prerequisites
- Python 3.8 or later
- Required Python libraries: `numpy`, `matplotlib`, `seaborn`, `pandas`, `sklearn`

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/moon-classification-gmm.git
   cd moon-classification-gmm
