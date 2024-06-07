### Book Recommendation System Project

#### Overview
This project involves building a book recommendation system using machine learning techniques. The system takes a book title as input and returns a list of 10 similar books. The project leverages web scraping, data preprocessing, and machine learning algorithms to achieve this goal.
The dashboard can be accessed on this link:  http://oci.jmcloudpro.com:8052/

#### Key Components

1. **Data Collection**:
   - **Web Scraping**: Data was collected from the Goodreads website, specifically from the "Best Books Ever" list. The BeautifulSoup library was used to scrape book details such as title, author, rating, genre, and description.
   - **Data Storage**: The scraped data was stored in a Pandas DataFrame and saved as a CSV file for further processing.

2. **Data Preprocessing**:
   - **Tokenization and Vectorization**: The CountVectorizer class from Scikit-learn was used to tokenize and vectorize the text data, converting it into a format suitable for machine learning algorithms.
   - **Feature Engineering**: A new column named "features" was created by combining the title, author, genre, and description of each book.

3. **Similarity Calculation**:
   - **Cosine Similarity**: The cosine_similarity function from Scikit-learn was used to compute the similarity between books based on their vectorized features. This similarity matrix is the core of the recommendation system.

4. **Recommendation Generation**:
   - **Function Definition**: A function was defined to take a book title as input and return a list of 10 similar books based on the cosine similarity scores.
   - **Example Recommendations**: For instance, given the book "The Hunger Games," the system recommended books like "Divergent," "My Sister's Keeper," and "Harry Potter and the Order of the Phoenix."

5. **Visualization and Analysis**:
   - **Average Rating by Genre**: A bar chart was created to visualize the average rating of books by genre.
   - **Rating vs. Number of Books per Genre**: A scatter plot was used to show the relationship between the number of books in each genre and their average ratings.
   - **Rating Distribution**: A histogram was plotted to show the distribution of book ratings.

6. **Dashboard Creation**:
   - **Plotly Dash**: A dashboard was created using Plotly Dash to provide an interactive interface for exploring the book data and generating recommendations. The dashboard includes features like genre selection, rating distribution charts, and a recommendation system interface.

#### Technologies Used
- **Programming Language**: Python
- **Libraries**: BeautifulSoup, Requests, Pandas, Matplotlib, Scikit-learn, Plotly Dash
- **Tools**: Jupyter Notebook
