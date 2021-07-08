Open Images V4: VGG16 FC2 Feature Vectors
=========================================

This repostiory contains the VGG16-FC2 feature vector data for
[OpenImagesV4](https://storage.googleapis.com/openimages/web/download_v4.html),
to be used with the
[primo-similarity-search](https://github.com/uwmisl/primo-similarity-search)
repository among others.

Should you wish to downoad millions of images from FLICKR, run the scripts found in the directory, "01_datasets". Note that you might want to change the paths where these images are stored and can find the places to do so by globally searching for the phrase "For future users". This script takes several days to run.

If you only want the feature vectors for the downloaded images, YOU DO NOT HAVE TO RUN ANY CODE. Simply download this repository and extract the following directories:

- `extended_targets/features` (this holds ~9 million feature vectors)
- `targets/features`          (this holds ~1.6 million feature vectors)
- `train/features`            
- `validation/features`       (this holds ~40 thousand feature vectors)

Details can be found in the Bee et al. Nature Communications 2021 paper.

## A visualization of the workflow
You are currently in the "primo-openimages" repository. Our intent is that most users will feel free to take the feature vectors and use them in their own work. Here, we show how the feature vectors are taken and used in another MISL repository.

<img src="https://github.com/uwmisl/primo-openimages/blob/master/githubcodeoverview.png" width="300" height="400">
