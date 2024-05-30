

# Book Recommendation System

This project aims to build a model that takes a book title as input and returns a list of 10 similar books.

## Table of Contents
- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## About the Project

The Book Recommendation System leverages machine learning to suggest books similar to a given title. It uses content-based recommendation techniques, specifically cosine similarity, to quantify the similarity between books based on their descriptions and other metadata.

### Key Features
- **Content-Based Recommendations**: Uses cosine similarity to find books similar to the input title.
- **Scikit-learn Integration**: Utilizes Scikit-learn's `CountVectorizer` and `cosine_similarity` functions.
- **User-Friendly**: Simple input-output model for ease of use.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/jmdtanalyst/book_recommendation.git
    cd book-recommendation-system
    ```

2. **Install required packages**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Prepare the data**:
    - Ensure you have a CSV file named `books.csv` in the root directory with the following columns: `url`, `title`, `author`, `rating`, `genre`, `description`, and keywords.

## Usage

To use the Book Recommendation System, follow these steps:

1. **Run the script**:
    ```sh
    python recommend.py
    ```

2. **Input a book title**:
    - When prompted, enter the title of a book.
    - The system will return a list of 10 similar books.

### Example

```sh
Enter a book title: The Great Gatsby
Recommended books:
1. This Side of Paradise by F. Scott Fitzgerald
2. Tender is the Night by F. Scott Fitzgerald
...
```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork the Project**:
    ```sh
    git clone https://github.com/jmdtanalyst/book-recommendation-system.git
    ```

2. **Create your Feature Branch**:
    ```sh
    git checkout -b feature/AmazingFeature
    ```

3. **Commit your Changes**:
    ```sh
    git commit -m 'Add some AmazingFeature'
    ```

4. **Push to the Branch**:
    ```sh
    git push origin feature/AmazingFeature
    ```

5. **Open a Pull Request**

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Jose Mario Costa  [@Portifolio](https://jmcloudpro.com)

Project Link: [https://www.jmcloudpro.com/book_recommendation](https://www.jmcloudpro.com/book_recommendation)

## Acknowledgements

- [Scikit-learn](https://scikit-learn.org/)
- [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/)
- [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)
- [CountVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html)

