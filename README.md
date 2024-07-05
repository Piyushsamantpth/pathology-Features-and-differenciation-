# pathology-Features-and-differenciation-


# To Run the Notebook:

Make sure set_1 and set_2 are folders with images.
Ensure requirements.txt file.
Open code.ipynb in any jupyternotebook and run the fle

# Functions:


load_image_from_folder(folder_path): Loads images from a specified folder.

detect_sift_features(image, max_features=500): Detects SIFT features in an image and returns flattened descriptors.

extract_hog_features(image): Extracts HOG features from an image and returns a flattened feature vector.

extract_color_histogram(image, bins=(8, 8, 8)): Extracts a color histogram from an image and returns a flattened feature vector.

extract_features(images): Combines SIFT, HOG, and color histogram features for a list of images and returns a 2D numpy array of feature vectors.



