# Kurtosis Calculation and Comparison

This Python script calculates the kurtosis of generated probability density functions (PDFs) for uniform and Gaussian distributions. It compares the results obtained using a custom kurtosis function with those from Python's pre-made library function.

## Functionality

The script performs the following steps:

1. **Generate PDFs:**
   - Generates a uniform distribution and a Gaussian (normal) distribution.

2. **Calculate Kurtosis:**
   - Uses a custom `kur` function to calculate the kurtosis of the distributions.
   - Calculates the kurtosis using Python's built-in `kurtosis` function.

3. **Compare Results:**
   - Compares the kurtosis values obtained from the custom function and the pre-made library function.

4. **Analyzing Differences:**
   - Calculates the absolute difference between the kurtosis values obtained from the custom and library functions.
   - Determines if the kurtosis values are consistent and identical across both methods.

## Usage

1. **Run the Script:**
   - Execute the script in a jupyter environment.

2. **Review Results:**
   - Examine the kurtosis values printed to the console.
   - Assess whether the custom function and the pre-made library function yield identical results.

## License

This project is licensed under the MIT License.
