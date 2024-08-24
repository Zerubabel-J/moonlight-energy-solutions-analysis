# MoonLight Energy Solutions - Solar Data Analysis

## Project Overview

MoonLight Energy Solutions aims to improve operational efficiency and sustainability through solar investments. This project involves analyzing solar radiation measurement data to identify key trends and provide strategic recommendations for solar installation.

## Getting Started

### Prerequisites

- Python 3.x
- `pip` for dependency management
- Virtual environment setup (optional but recommended)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/moonlight-energy-solutions-analysis.git
   cd moonlight-energy-solutions-analysis
   ```

2. **Set up the virtual environment**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebook/Google Colab**:
   If you're using Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   If you're using Google Colab, open your notebook directly from Google Drive or GitHub.

## Project Details

### Data

The dataset used in this analysis includes measurements of solar radiation, temperature, wind speed, humidity, and more. These measurements help identify patterns and high-potential regions for solar installations.

### Analysis Workflow

1. **Exploratory Data Analysis (EDA)**:

   - Time series analysis of GHI, DNI, and DHI.
   - Correlation analysis between environmental factors.
   - Impact of sensor cleaning on measurements.

2. **Statistical Analysis**:
   - Summary statistics, Z-score analysis, and distribution visualization.
   - Outlier detection and handling.

### Key Insights

- Observations regarding solar radiation trends across different months.
- Recommendations for high-potential solar installation sites based on the data.

## Contributing

Contributions are welcome! Please open an issue or a pull request for any suggestions or improvements.

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-branch
   ```
3. **Make your changes and commit**:
   ```bash
   git commit -m "Add feature"
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature-branch
   ```
5. **Create a pull request**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
