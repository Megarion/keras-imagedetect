# Data collection
TODO: find out about the Google Images api
- Find images of certain plant species
- Filter out images (by hand, yes, because I couldn't find a way to discard images with watermarks, uneccessary text, etc.)
- Follow stages of modification to the input

Then the dataset (with 100 images for each plant species) is ready for training!
<br><br>

# Data format
## Training data follows this format:
```
([train_images], [train_labels]), ([test_images], [test_labels])
```
For images, they are individual pixel data stored in 2D arrays that ranges from 0->255 (grayscale)
<br><br>

# Stages of modification 
## (to the dataset)
- Convert data to an appropriate type
- Convert image data to individual pixels (instead of binary data)
- Do modifications on the image content (cropping, compressing...)
- Make final refinements to suit the data format

## (to the input)
- Convert image data to individual pixels (instead of binary data)
- Do modifications on the image content (cropping, compressing...)