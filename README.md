# Probability and Statistics Analysis Project

This project demonstrates the application of various statistical concepts, including binomial distribution, uniform distribution, normal distribution, standardization, and data visualization. The analysis is performed on two datasets: `debugging.csv` and `Stats.csv`. The project also includes comparisons of SAT and ACT scores to identify top-performing students.

---

## Features

### 1. **Binomial Distribution**
- Calculate probabilities for specific outcomes based on a given probability (`p`) and number of trials (`n`).
- Example calculations:
  - Probability of all visitors buying souvenirs.
  - Probability of at most 7 visitors buying souvenirs.

### 2. **Continuous Uniform Distribution**
- Analyze debugging time using a uniform distribution based on dataset values.
- Key metrics:
  - Probability of debugging taking less than 3 hours.
  - Probability of debugging taking more than 2 hours.
  - Median debugging time.

### 3. **Normal Distribution**
- Perform SAT score analysis with given mean (`mu`) and standard deviation (`sigma`).
- Insights:
  - Probability of scores below 800 or above 1300.
  - Calculate the 90th and 95th percentile scores.

### 4. **Standardization and Z-Scores**
- Compare SAT and ACT top scores using Z-scores to identify the relatively better performer.

### 5. **Data Visualization**
- Plot probability density functions for SAT and ACT scores.
- Highlight top scores with visual annotations.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HunarAgrawal/Inferential_Statistics.git
   cd Inferential_Statistics
   
2. Install required Python libraries:
   ```bash
   pip install pandas scipy matplotlib numpy

3. Place the required datasets (debugging.csv and Stats.csv) in the project directory.

---

## Usage

1. Run the script
   ```bash
   python analysis.py

2. View the results:
- Probabilities and statistical insights will be printed in the terminal.
- Visualizations will be displayed as plots.

---

## File Descriptions

- analysis.py : Main script containing all calculations and visualizations.
- debugging.csv : Dataset containing debugging times.
- Stats.csv : Dataset containing SAT scores.

---

## Dependencies

- Python 3.7 or higher
- Libraries: pandas, scipy, matplotlib, numpy

---

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository, make your changes, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author

Hunar Agrawal

---

## Acknowledgments
Special thanks to the resources and documentation of Python libraries like:

- Pandas
- SciPy
- Matplotlib
