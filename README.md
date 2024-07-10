## Weather Modelling with Quadratic Equations

This project demonstrates various approaches to model temperature changes over time using a quadratic equation. We explore different methods for defining the coefficients of the quadratic equation and visualize the results using matplotlib. The project includes several scripts, each illustrating a unique approach:

### 1. Using Hard-Coded Variables

This script models temperature changes using a fixed set of coefficients for the quadratic equation. The coefficients are hard-coded into the script, providing a simple and straightforward way to generate the temperature model. The plot displays temperature over time using these predefined values.

### 2. Using Keyboard Input Coefficients

In this script, users are prompted to input the coefficients for the quadratic equation through the keyboard. This allows for dynamic input and lets users experiment with different values. The resulting temperature model is plotted based on the user's input.

### 3. Using File Input Coefficients

This script reads the coefficients from a file. The file contains the values of the coefficients which are then used to calculate the temperature model. This method is useful for scenarios where the coefficients are stored externally and need to be accessed programmatically. The temperature over time is plotted using these file-based coefficients.

### 4. Using Single Set of Input Values

Here, a single set of coefficients is defined in a list within the script. These coefficients are then used to compute the temperature model. The plot showcases the temperature changes over time using this predefined set of values.

### 5. Using Multiple Sets of Input Values

This script handles multiple sets of coefficients. Each set is used to generate a separate temperature model, and all the models are plotted together. This approach is beneficial for comparing different scenarios or models simultaneously.

### 6. Using Multiple Sets of File Input Values

Similar to the previous script, this one reads multiple sets of coefficients from a file. Each set is used to compute a different temperature model, and all the models are plotted on the same graph. This method combines the flexibility of file input with the ability to handle multiple models.

### 7. Using a Combination of Hard-Coded and Keyboard Input Values

This script combines hard-coded coefficients for one temperature model with keyboard input coefficients for another. The two models are plotted together, allowing for direct comparison between a fixed set of values and user-defined inputs.

## Output and Usage

The output of each script is a plot that visualizes temperature changes over time based on the quadratic equation. These models can be used for various purposes, such as:

- Educational demonstrations of quadratic equations and their applications
- Simulating weather patterns or other time-dependent phenomena
- Comparing the impact of different coefficients on the model

Each script provides a unique way to define the coefficients, offering flexibility and versatility for different use cases.

## Requirements

- Python 3.x
- Matplotlib
- NumPy

## Running the Scripts

To run any of the scripts, simply execute the Python file in your terminal or IDE. For example, to run the script with hard-coded variables, use:

```bash
python script_name.py
```

Replace `script_name.py` with the actual name of the script you wish to run. Follow any prompts or instructions provided by the script, especially for those requiring keyboard input or file input.

## Conclusion

This project showcases different methods to model temperature changes using quadratic equations. Each script highlights a unique approach, offering a variety of ways to define and visualize the coefficients. Whether for educational purposes or practical applications, these models provide a clear and customizable way to explore the behavior of quadratic equations over time.
