# <Project-Name> **Weather Forecast using Time-series Predictive Modelling**

## **Overview**
### **Problem Statement**
- The primary problem this project addresses is the forecasting of different weather parameters for specific locations
- The ability to accurately predict these parameters is crucial for numerous applications, including energy management, agricultural planning, and public health advisories
### **Problem Objective**
- This project seeks to contribute towards that need by enhancing the precision of these predictions
- The goal is to use historical data to forecast future observations accurately, enabling effective planning and decision-making in response to weather-dependent challenges
### **Models Used**
- **Statistical Models**
  - ARIMA
  - ARIMAX
- **Machine Learning Models**
  - LSTM

## Prerequisites
Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [R](https://cran.r-project.org/mirrors.html) and [RStudio](https://www.rstudio.com/products/rstudio/download/#download) or have access to a server where R is installed.
- You have installed [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Visual Studio Code](https://code.visualstudio.com/download) if you wish to use Jupyter Notebook via a Conda environment.
- You have a `<Windows/Linux/Mac>` machine. (Specify if your software is OS-dependent)

## Installation

### R and RStudio
1. Download and install R from the [CRAN repository](https://cran.r-project.org/mirrors.html).
2. Download and install RStudio from the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download).

### Jupyter Notebook
There are several ways to install Jupyter. If you have installed Anaconda, it comes with Jupyter Notebook. Otherwise, you can install it via pip with R support as follows:

```bash
pip install notebook
```

To add R support to Jupyter, open an R console and install the necessary packages:

```r
install.packages('IRkernel')
IRkernel::installspec(user = FALSE)
```

## Running the Software

### RStudio
To run the experiments in RStudio:
1. Open RStudio.
2. Go to 'File' > 'Open Project...' and select the `<Project-Name>.Rproj` file from the project directory.
3. Open the R scripts or Markdown and run them within the RStudio environment.

### Jupyter Notebook
To run the experiments in a Jupyter Notebook:
1. Navigate to your project directory in the command line.
2. Launch Jupyter Notebook by running:

```bash
jupyter notebook
```

3. In the Jupyter interface, navigate to and open the `.ipynb` notebook files.
4. Run the cells in the notebook to perform the experiments.

## Project Structure
```
<Project-Name>/
│
├── data/                   # Directory for datasets used in experiments
├── notebooks/              # Jupyter notebooks
├── R/                      # R scripts
├── Report                  # Final project report
├── Presentation            # Final project slides
├── README.md               # The file you are currently reading
```

### **Note:** 
Modify the dataset input path in R, Notebook according to your local directory structure.

