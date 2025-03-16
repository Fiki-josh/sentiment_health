# Sentiment Analysis on Healthcare Reviews in Abuja

This project aims to perform sentiment analysis on healthcare-related reviews collected from Google Maps. The reviews are stored in multiple JSON files, which will be merged into a single dataset for analysis.
This project uses Transformer Pipeline Model from Hugging Face

## Project Structure

- **data/**: Contains the JSON files with healthcare reviews.
  - `dataset_google-maps-reviews-1.json` to `dataset_google-maps-reviews-46.json`: Each file contains reviews with fields such as title, stars, name, text, neighborhood, location, categoryName, city, and publishAt.

- **notebooks/**: Contains Jupyter notebooks for documentation and experimentation.
  - `book.ipynb`: A notebook for running experiments related to sentiment analysis.

- **requirements.txt**: Lists the dependencies required for the project, such as pandas and libraries for sentiment analysis.

## Setup Instructions

1. Clone the repository to your local machine.
2. Navigate to the project directory.
### Running notebook in Vscode
3. Create a virtual environment:
    ```
    py -m venv venv
    ```
4. Install the required dependencies using:
   ```
   pip install -r requirements.txt
   ```

for further instructions, check <a href = "https://code.visualstudio.com/docs/datascience/jupyter-notebooks" target = "_blank_" > Jupyter Notebooks in Vscode</a>

## Usage

- Follow `notebook/book.ipynb` it contains a step by step process for this project.

## Visualization on the Analysed Data

1. Overall Sentiment Distribution - Bar Chart
![alt text](images/image.png)
This chart shows the distribution of positive and negative sentiments across all reviews. It provides an overview of the general sentiment polarity in the dataset.

2. Overall Sentiment Distribution - Pie Chart
![alt text](images/image1.png)
This pie chart visualizes the proportion of positive and negative sentiments in the dataset. It gives a quick glance at the sentiment breakdown.

3. Sentiment over Time - Line Chart
![alt text](images/image2.png)
This line chart tracks the changes in positive and negative sentiments over different time periods. It helps identify trends in sentiment over time.

4. Sentiment over Time - Bar Chart
![alt text](images/image3.png)
This bar chart shows the count of positive and negative sentiments for each time period. It provides a clear comparison of sentiment distribution over time.

5. Distribution of Sentiment for Each Star Rating - Bar Chart
![alt text](images/image4.png)
This bar chart shows the count of positive and negative sentiments over the rating, given to each review. It provides a clear comparison of the sentiment analysed and the rating given to a review.

6. Sentiment Distribution across Categories - Bar Chart
![alt text](images/image5.png)
This bar chart visualizes the count of positive and negative sentiments for each category. It highlights how sentiment varies across different categories.

7. Sentiment Distribution across Categories - Line Chart
![alt text](images/image6.png)
This line chart shows the count of positive and negative sentiments for each category. It provides a trend view of sentiment distribution across categories.

8. Sentiment Distribution across Neighborhoods - Bar Chart
![alt text](images/image7.png)
This bar chart visualizes the count of positive and negative sentiments for each neighborhood. It highlights how sentiment varies across different neighborhoods.

9. Sentiment Distribution across Neighborhoods - Line Chart
![alt text](images/image9.png)
This line chart shows the count of positive and negative sentiments for each neighborhoods. It provides a trend view of sentiment distribution across neighborhoods.

## Exported File
For further analysis, a copy of the cleaned dataset have been exported and can be viewed under:
```
file/cleaned_data.csv
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.