EC ENGR 219: Project 2 README
Please import all notebook parts in Google Colab to run. Required data files that need to be installed are provided below. Required code dependencies are installed at the top of each notebook.

Part 1: Review Length & Game Clustering (part1.ipynb)
Required Data: main.csv (Steam reviews dataset). Place it in the project root.

Part 2: Deep Learning, Image Clustering & Held-Out Profiling (part2.ipynb)
Required Data:
Steam Data: Needs both main.csv and heldout.csv. Set the path in STEAM_DATA_DIR environment variable.
Flower Photos: Auto-downloads flower_photos.tgz if missing. VGG-16 features are cached to flowers_features_and_labels.npz on the first run.

Part 3: Pokemon & CLIP (part3.ipynb)
Required Data:
Pokemon Images Data: Kaggle Pokemon Image Dataset. Extract to ./images/ (one subfolder per Pokemon) so that the file path matches as shown in code.
Pokemon.csv Metadata: Download Pokemon.csv from lgreski/pokemonData. Save to the project root.
