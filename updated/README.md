# CNN Implementation

Three CNN image-classification projects built in college (TensorFlow/Keras).

| Project | Notebook | Dataset folder (Google Drive) |
|---|---|---|
| Dog vs Cat | `DOG_CAT/DogCatClassificationCode.ipynb` | `DOG_CAT/data` |
| Handwritten Digits | `HANDWRITEEN_DIGITS/HandwrittenDigitsClassificationCode.ipynb` | `HANDWRITEEN_DIGITS/dataset` |
| Zoo Animals | `ZOO_ANIMALS/ZooAnimalsClassificationCode.ipynb` | `ZOO_ANIMALS/zoo Animals/animals` |

Datasets are not stored in this repo. They are on Google Drive:
https://drive.google.com/drive/folders/1MSXIN7wu7wHj7Thl_FI-7KqbiopW6_4C

## Run in Google Colab
1. Open the notebook in Colab (File > Open notebook > GitHub).
2. Make sure the Drive folder `My Drive/CNN Implementation/` is in your Drive (copy it if it is shared with you).
3. Run the first cell; it mounts Drive and sets `BASE_DIR` automatically.

## Run locally
1. Clone the repo and `pip install -r requirements.txt`.
2. Download the dataset folder from Drive and place it next to the notebook (e.g. `DOG_CAT/data/`).
3. Start Jupyter from inside that project folder so `BASE_DIR` resolves correctly.
