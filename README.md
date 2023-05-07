# Malaria
Classifying blood cells with malaria

This is a project using Tensorflow dataset(tfds) Malaria and using transfer learning from EfficientNet and Pytorch to train it.

This code is mainly programmed in Pytorch and it is quite a hassel to use a tensorflow dataset and make it into a customized image dataset in torch. Currently all the components are all working but even after using the GPU, I estimate that it will take around 5000 minutes (in enumerate 1 batch takes around 4 minutes and there are 1730 batches + there is a train and test loader) which will definitely forcely shut down my google colab so it is not doable.
