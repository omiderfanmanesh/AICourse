# AI Course Project

## Setting Up the Virtual Environment

### Using `virtualenv`

1. **Create a virtual environment**:
   Open a terminal and run the following command to create a virtual environment named `AI-Course`:

   ```bash
   python3 -m venv AI-Course
   ```

2. **Activate the virtual environment**:
   Run the following command to activate the virtual environment:

   ```bash
   source AI-Course/bin/activate
   ```

3. **Install the required packages**:
   With the virtual environment activated, run the following command to install the packages from `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

### Using `conda`

1. **Create a conda environment**:
   Open a terminal and run the following command to create a conda environment named `AI-Course`:

   ```bash
   conda create --name AI-Course python=3.8
   ```

2. **Activate the conda environment**:
   Run the following command to activate the conda environment:

   ```bash
   conda activate AI-Course
   ```

3. **Install the required packages**:
   With the conda environment activated, run the following command to install the packages from `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

## Additional Information

- Ensure you have `virtualenv` or `conda` installed on your system.
- The `requirements.txt` file contains all the necessary packages for this project.
- To deactivate the virtual environment, run `deactivate` for `virtualenv` or `conda deactivate` for `conda`.
