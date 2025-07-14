# Computer vision for image classification - zero-shot approach

This tutorial contains worked examples for using pre-trained computer vision models for zero-shot image classification and object detection. The examples are designed to be modular, and compatible with a range of models hosted on [HuggingFace](http://huggingface.co).

The examples here have been tested using Python 3.12.3 and 3.12.9 with the package versions listed in `requirements.txt`.

To test these examples locally:
1. Download and install [Python](https://www.python.org/downloads/).
2. Install the required packages. This is easiest from the command line or terminal using `pip install -r requirements.txt`.
3. Start a Jupyter server using the command `jupyter notebook`. This should automatically open in your browser, where you can navigate to the saved files.

To run these examples in the cloud:
1. Go to [Google Colab](https://colab.google/).
2. Upload the example notebooks.
3. (Optional) Switch to a GPU enabled runtime
4. (Optional) Mount your Google Drive folders so that image data can be mounted between sessions.
Google Colab will manage all of the package dependencies for you, but does involve moving the data to Google's servers.

Example datasets can be downloaded from [COCO](http://images.cocodataset.org/zips/val2017.zip). A small set of images taken by the author of this repository are included for testing purposes.