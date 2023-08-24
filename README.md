# Text-Image Retrieval using CLIP

[[Paper]](https://arxiv.org/abs/2103.00020)

To use the text-image retrieval, run file: Zero-shot text-image retrieval using CLIP.ipynb

## Environment setup
```sh
$ conda install pytorch pytorch=1.7.1 torchvision cudatoolkit=11.1
$ pip install ftfy regex tqdm
$ pip install git+https://github.com/openai/CLIP.git
$ conda install matplotlib
$ pip install numpy
$ pip install scikit-image
```

## Example result
### User given text, retrive image from CIFAR100 dataset
![image](https://github.com/WensongVincent/CLIP_modified/assets/124071302/700d98f6-a738-45c4-bd80-e592bdc52fad)

### User given text, retrie image from sci-kit images
![image](https://github.com/WensongVincent/CLIP_modified/assets/124071302/3435d226-b4c8-48a2-99cd-07cb1e8d57c2)
