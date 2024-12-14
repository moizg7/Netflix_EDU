# Netflix TV Shows & Movies Dataset EDA

This project performs Exploratory Data Analysis (EDA) on the Netflix TV Shows & Movies dataset using PySpark. The analysis explores various aspects of the dataset, including basic dataset information, content distribution, production trends, and rating analysis.

---

## Getting Started

### Prerequisites

Before running the analysis, ensure you have the following:

- **Docker**: For setting up a containerized environment.
- **PySpark**: To process and analyze the dataset.
- **Jupyter Notebook**: For interactive analysis and visualization.

### Setup

1. **Install Docker**:
   - Download and install Docker from [here](https://www.docker.com/).

2. **Pull the PySpark Docker Image**:
   - Open your terminal and run the following command to pull the PySpark Docker image:
     ```bash
     docker pull jupyter/pyspark-notebook
     ```

3. **Run the Docker Container**:
   - Start the container with the following command:
     ```bash
     docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
     ```
   - This will start a Jupyter Notebook server. Access it by navigating to `http://localhost:8888` in your web browser.

4. **Download the Dataset**:
   - Visit the [Netflix TV Shows & Movies Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).
   - Download the dataset and save it in your working directory as `netflix_titles.csv`.

5. **Run the Analysis**:
   - Open Jupyter Notebook by navigating to `http://localhost:8888`.
   - Copy and paste the provided Python code into a new notebook cell.
   - Execute the cells step by step to perform the analysis.

---

## Results

### 1. Basic Dataset Information
- **Schema**: Displays the structure and data types of the dataset.
- **Total Records**: The dataset contains `N` records (replace `N` with the actual count).


### 2. Top Directors with the Most Titles
The top directors with the highest number of titles in the dataset are:

### 3. Average Release Year by Content Type
The average release year for different types of content is as follows:

### 4. Distribution of Content by Duration Length
The analysis of content duration by type shows:

### 5. Countries with the Most Diverse Genres
Countries with the most diverse genres are:


### 6. Titles with the Longest Words
Titles with the longest words are:


### 7. Content Rating Analysis
The distribution of content ratings in the dataset is as follows:


## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.
