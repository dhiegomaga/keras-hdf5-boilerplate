# Brands Example

## Dataset

An image dataset should be put inside _Dataset/_, following the hierarchy:

```text

dataset/
    class_a/
        a-1.jpg
        a-2.jpg
        ...
    class_b/
        b-1.jpg
        b-2.jpg
    ...

```

## Scripts

`DataPrep.ipynb`: Grabs images from _Dataset/_ and creates single **hdf5** file with the train and test features and labels.
`BatchTraining.ipynb`: Defines the image generator to train the data on, as well as the keras network architecture.
