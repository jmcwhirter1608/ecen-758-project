# ECEN-758 DBpedia Classification Project

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Place data files in `dbpedia_project/`:
   - `train.csv`
   - `test.csv`
   - `classes.txt`

   Retrieved from Extracting [Google Drive](https://drive.google.com/uc?export=download&id=0Bz8a_Dbh9QhbQ2Vic1kxMmZZQ1k)

3. Open `ECEN758_PROJECT.ipynb` and run all cells.

## Output

- **Model**: `dbpedia_project/model/`
- **Checkpoints**: `dbpedia_project/checkpoints/`
- **Baseline**: `dbpedia_project/tfidf_svm_baseline.pkl`

## Final Submission Setup


1. Final Submission located [here](https://drive.google.com/file/d/19A4Lw8Kx1AYeyC5mWP6AsUnp7jsIjv09/view?usp=drive_link) in addition to the zipped file in this repo.
   - Contains 2 Jupyter Notebooks for testing and execution
   - Contains the final DistilBERT model

2. Extract the Final Submission into your directory.
   - This can be uploaded into a Google Drive and used with Google Colab
   - It can also be run locally with jupyter notebook and a virtual python environment
   
   ```bash
   python -m venv .venv
   source .venv/bin/activate # macOS / Linux
   source .venv/Scripts/activate # Windows
   ```

   - Set the Jupyter Notebook python environment to the virtual directory in your IDE.


3. Open the Project main jupyter notebook for our collaborative effort or the Test jupyter notebook to see the target results.