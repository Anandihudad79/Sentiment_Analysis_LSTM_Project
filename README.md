# Sentiment Analysis of Movie Reviews using Deep Learning (LSTM)

## Project Structure

- `notebooks/` - Main Jupyter Notebook
- `data/` - Dataset folder (the IMDB dataset is downloaded automatically by Keras)
- `models/` - Saved trained model can be stored here
- `screenshots/` - Add screenshots of graphs, results and desktop application here
- `src/` - Optional Python source files
- `docs/` - Project report/PPT/document files
- `requirements.txt` - Required Python packages

## How to Run

1. Open the project folder in VS Code.
2. Select the correct Python 3.13 kernel.
3. Open:
   `notebooks/Sentiment_Analysis_LSTM_Desktop.ipynb`
4. Install packages from the VS Code Terminal:

   `python -m pip install -r requirements.txt`

5. Run notebook cells from top to bottom.
6. Run the final GUI cell to open the one-screen desktop application.

## Important

The IMDB dataset does not need to be manually placed in the `data` folder. TensorFlow/Keras downloads it automatically when `imdb.load_data()` is executed.
