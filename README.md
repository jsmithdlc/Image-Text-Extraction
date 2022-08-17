# Image-Text-Extraction

Project for experimenting with text extraction from images. Developed using Python 3.8

## Download Models

Download EAST text detection model by running the following commands in the root of this project:

```bash
# Download model
wget https://www.dropbox.com/s/r2ingd0l3zt8hxs/frozen_east_text_detection.tar.gz-P models/

# Extract model
tar -xvzf models/frozen_east_text_detection.tar.gz -C models/

# Delete tar
rm models/frozen_east_text_detection.tar.gz
```

## References

East text detection code built upon [this implementation by Adrian Rosebrock](https://pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector/)