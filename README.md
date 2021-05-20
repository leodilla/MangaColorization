# MangaColorization
Colorize blank-and-white mange with the network of chromaGan and nerual style transfer.

## ChromaGAN
test the network with `ChromaGan.ipynb`, put the pretrained model into the path `MODEl/testmodel.h5`

train the network with `chromagan_train.py`, with the imagenet data and the JoJo manga dataset.

## Neural Transfer Style
put the output image of the chromaGan into the `content_path` of the `Neural_Style_Transfer.ipynb` and designate the colorized style image in `sytle_path`
run the network and get the final colorization

## outputs
Some sample test image and the outputs
