# Ploting in Python
This project is done using collab and deals with histograms and heatmaps using a large dataset 

## Creating Histogram and Heatmap using Matplotlib and Seaborn

We'll learn how to create a histogram and heatmap using the Matplotlib and Seaborn libraries in Python. We'll use sample data to demonstrate the process.

### Getting Started

#### Installation
Make sure you have the following libraries installed:
- Matplotlib
- Seaborn
- Pandas (for data manipulation, if necessary)
- Numpy (for numerical operations, if necessary)

You can install these libraries using pip:
```bash
pip install matplotlib seaborn pandas numpy
```
#### Examples

##### Create a histogram using Matplotlib:

```python
import matplotlib.pyplot as plt
import seaborn as sns

# Sample data
data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Create histogram
plt.hist(data, bins=5, color='skyblue', edgecolor='black')
plt.xlabel('Value')
plt.ylabel('Frequency')
plt.title('Histogram')
plt.show()

```

##### Create a heatmap using Seaborn:

```python
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np

# Sample data
data = np.random.rand(10, 10)

# Create heatmap
sns.heatmap(data, cmap='YlGnBu')
plt.title('Heatmap')
plt.show()

```
