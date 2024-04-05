# Data Extraction:
Fetche HTML content from any given URL, allowing flexibility to use URLs from sources like Wikipedia or any other web page containing relevant text data. <br \>
Using Python libraries like requests and BeautifulSoup, the script extracts text from HTML elements such as paragraphs or headings etc.

# Processing Steps:
1. Cleaning Data: Eliminates any symbols or characters that are not relevant to the text content.
2. Normalization: Converts all text to lowercase to ensure uniformity for subsequent processing steps.
3. Tokenization: Splits the text into individual words or tokens, facilitating further analysis.
4. Lemmatization or Stemming: Reduces words to their base or root form to standardize variations of the same word. Users can choose between lemmatization or stemming based on their preference or requirements.
5. Stop Words Removal: Filters out common words such as "is," "and," "the," etc., which do not add significant meaning to the text.
6. Unique Word Extraction:
After processing, we get all unique words present in the text data. This ensures that only distinct words are considered for analysis, providing valuable insights into the vocabulary used in the text.
