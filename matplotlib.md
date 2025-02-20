### Matplotlib:
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. It's highly customizable and versatile, allowing you to create a wide range of plots, from simple line charts to complex multi-dimensional visualizations.

**Key Features:**
- Wide range of plot types: line, bar, scatter, histogram, pie, etc.
- Highly customizable with a detailed control over every aspect of the plot
- Integration with NumPy, Pandas, and other scientific libraries
- Supports multiple output formats (PNG, PDF, SVG, etc.)

**Example Code:**
```python
import matplotlib.pyplot as plt

# Sample data
x = [1, 2, 3, 4, 5]
y = [2, 3, 5, 7, 11]

# Create a simple line plot
plt.plot(x, y)
plt.title('Sample Line Plot')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
