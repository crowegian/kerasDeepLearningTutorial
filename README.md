# kerasDeepLearningTutorial
Just some of my work on using keras. Mostly so I can learn about implementing deep learning with Keras



Below is a list of projects I'm gonna look at which was snagged [from fchollet's github ](https://github.com/fchollet/keras-resources)


# Keras resources

This is a directory of tutorials and open-source code repositories for working with Keras, the Python deep learning library.

If you have a high-quality tutorial or project to add, please open a PR.

## Official starter resources

- [keras.io](http://keras.io/) - Keras documentation
- [Getting started with the Sequential model](http://keras.io/getting-started/sequential-model-guide/)
- [Getting started with the functional API](http://keras.io/getting-started/functional-api-guide/)
- [Keras FAQ](http://keras.io/getting-started/faq/)

## Tutorials

- [Quick start: the Iris dataset in Keras and scikit-learn](https://github.com/fastforwardlabs/keras-hello-world/blob/master/kerashelloworld.ipynb)
- [Using pre-trained word embeddings in a Keras model](http://blog.keras.io/using-pre-trained-word-embeddings-in-a-keras-model.html)
- [Building powerful image classification models using very little data](http://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html)
- [Building Autoencoders in Keras](http://blog.keras.io/building-autoencoders-in-keras.html)
- [A complete guide to using Keras as part of a TensorFlow workflow](http://blog.keras.io/keras-as-a-simplified-interface-to-tensorflow-tutorial.html)
- Introduction to Keras, from University of Waterloo: [video](https://www.youtube.com/watch?v=Tp3SaRbql4k) - [slides](https://uwaterloo.ca/data-science/sites/ca.data-science/files/uploads/files/keras_tutorial.pdf)
- Introduction to Deep Learning with Keras, from CERN: [video](http://cds.cern.ch/record/2157570?ln=en) - [slides](https://indico.cern.ch/event/506145/contributions/2132944/attachments/1258124/1858154/NNinKeras_MPaganini.pdf)
- [Installing Keras for deep learning](http://www.pyimagesearch.com/2016/07/18/installing-keras-for-deep-learning/)
- [Develop Your First Neural Network in Python With Keras Step-By-Step](http://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)
- [Understanding Stateful LSTM Recurrent Neural Networks in Python with Keras](http://machinelearningmastery.com/understanding-stateful-lstm-recurrent-neural-networks-python-keras/)
- [Time Series Prediction with LSTM Recurrent Neural Networks in Python with Keras](http://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/)
- [Keras video tutorials from Dan Van Boxel](https://www.youtube.com/playlist?list=PLFxrZqbLojdKuK7Lm6uamegEFGW2wki6P)
- [Keras Deep Learning Tutorial for Kaggle 2nd Annual Data Science Bowl](https://github.com/jocicmarko/kaggle-dsb2-keras/)
- [Collection of tutorials setting up DNNs with Keras](http://ml4a.github.io/guides/)

## Code examples

### Working with text

- [Reuters topic classification](https://github.com/fchollet/keras/blob/master/examples/reuters_mlp.py)
- [LSTM on the IMDB dataset (text sentiment classification)](https://github.com/fchollet/keras/blob/master/examples/imdb_lstm.py)
- [Bidirectional LSTM on the IMDB dataset](https://github.com/fchollet/keras/blob/master/examples/imdb_bidirectional_lstm.py)
- [1D CNN on the IMDB dataset](https://github.com/fchollet/keras/blob/master/examples/imdb_cnn.py)
- [1D CNN-LSTM on the IMDB dataset](https://github.com/fchollet/keras/blob/master/examples/imdb_cnn_lstm.py)
- [LSTM-based network on the bAbI dataset](https://github.com/fchollet/keras/blob/master/examples/babi_rnn.py)
- [Memory network on the bAbI dataset (reading comprehension question answering)](https://github.com/fchollet/keras/blob/master/examples/babi_memnn.py)
- [Sequence to sequence learning for performing additions of strings of digits](https://github.com/fchollet/keras/blob/master/examples/addition_rnn.py)
- [LSTM text generation](https://github.com/fchollet/keras/blob/master/examples/lstm_text_generation.py)
- [Using pre-trained word embeddings](https://github.com/fchollet/keras/blob/master/examples/pretrained_word_embeddings.py)
- [Monolingual and Multilingual Image Captioning](https://github.com/elliottd/GroundedTranslation)
- [FastText on the IMDB dataset](https://github.com/fchollet/keras/blob/master/examples/imdb_fasttext.py)
- [Structurally constrained recurrent nets text generation](https://github.com/nzw0301/keras-examples/blob/master/SCRNLM.ipynb)
- [Character-level convolutional neural nets for text classification](https://github.com/johnb30/py_crepe)
- [LSTM to predict gender of a name](https://github.com/divamgupta/lstm-gender-predictor)

### Working with images

- [Simple CNN on MNIST](https://github.com/fchollet/keras/blob/master/examples/mnist_cnn.py)
- [Simple CNN on CIFAR10 with data augmentation](https://github.com/fchollet/keras/blob/master/examples/cifar10_cnn.py)
- [Inception v3](https://github.com/fchollet/keras/blob/master/examples/inception_v3.py)
- [VGG 16 (with pre-trained weights)](https://gist.github.com/baraldilorenzo/07d7802847aaad0a35d3)
- [VGG 19 (with pre-trained weights)](https://gist.github.com/baraldilorenzo/8d096f48a1be4a2d660d)
- ResNet 50 (with pre-trained weights): [1](https://github.com/fchollet/keras/pull/3266/files) - [2](https://github.com/raghakot/keras-resnet)
- [FractalNet](https://github.com/snf/keras-fractalnet)
- [AlexNet, VGG 16, VGG 19, and class heatmap visualization](https://github.com/heuritech/convnets-keras)
- [Visual-Semantic Embedding](https://github.com/awentzonline/keras-visual-semantic-embedding)
- Variational Autoencoder: [with deconvolutions](https://github.com/fchollet/keras/blob/master/examples/variational_autoencoder_deconv.py) - [with upsampling](https://github.com/fchollet/keras/blob/master/examples/variational_autoencoder.py)
- [Visual question answering](https://github.com/avisingh599/visual-qa)
- [Deep Networks with Stochastic Depth](https://github.com/dblN/stochastic_depth_keras)
- [Smile detection with a CNN](https://github.com/kylemcdonald/SmileCNN)
- [VGG-CAM](https://github.com/tdeboissiere/VGG16CAM-keras)
- [t-SNE of image CNN fc7 activations](https://github.com/ml4a/ml4a-guides/blob/master/notebooks/tsne-images.ipynb)
- [VGG16 Deconvolution network](https://github.com/tdeboissiere/DeepLearningImplementations/tree/master/DeconvNet)
- Wide Residual Networks (with pre-trained weights): [1](https://github.com/asmith26/wide_resnets_keras) - [2](https://github.com/titu1994/Wide-Residual-Networks)
- [Ultrasound nerve segmentation](https://github.com/jocicmarko/ultrasound-nerve-segmentation)
- [DeepMask object segmentation](https://github.com/abbypa/NNProject_DeepMask)
- [Densely Connected Convolutional Networks](https://github.com/tdeboissiere/DeepLearningImplementations/tree/master/DenseNet)

### Creative visual applications

- [Real-time style transfer](https://github.com/awentzonline/keras-rtst)
- Style transfer: [1](https://github.com/fchollet/keras/blob/master/examples/neural_style_transfer.py) - [2](https://github.com/titu1994/Neural-Style-Transfer)
- [Image analogies](https://github.com/awentzonline/image-analogies): Generate image analogies using neural matching and blending.
- [Visualizing the filters learned by a CNN](https://github.com/fchollet/keras/blob/master/examples/conv_filter_visualization.py)
- [Deep dreams](https://github.com/fchollet/keras/blob/master/examples/deep_dream.py)
- GAN / DCGAN: [1](https://github.com/phreeza/keras-GAN) - [2](https://github.com/jacobgil/keras-dcgan) - [3](https://github.com/osh/KerasGAN)

### Reinforcement learning

- [DQN](https://github.com/sherjilozair/dqn)
- [FlappyBird DQN](https://github.com/yanpanlau/Keras-FlappyBird)
- [async-RL](https://github.com/coreylynch/async-rl): Tensorflow + Keras + OpenAI Gym implementation of 1-step Q Learning from "Asynchronous Methods for Deep Reinforcement Learning"
- [keras-rl](https://github.com/matthiasplappert/keras-rl): A library for state-of-the-art reinforcement learning. Integrates with OpenAI Gym and implements DQN, double DQN, Continuous DQN, and DDPG.

### Miscallenous architecture blueprints

- [Stateful LSTM](https://github.com/fchollet/keras/blob/master/examples/stateful_lstm.py)
- [Siamese network](https://github.com/fchollet/keras/blob/master/examples/mnist_siamese_graph.py)
- [Pretraining on a different dataset](https://github.com/fchollet/keras/blob/master/examples/mnist_transfer_cnn.py)
- [Neural programmer-interpreter](https://github.com/mokemokechicken/keras_npi)

## Third-party libraries

- [Elephas](https://github.com/maxpumperla/elephas): Distributed Deep Learning with Keras & Spark
- [Hyperas](https://github.com/maxpumperla/hyperas): Hyperparameter optimization
- [Hera](https://github.com/jakebian/hera): in-browser metrics dashboard for Keras models
- [Kerlym](https://github.com/osh/kerlym): reinforcement learning with Keras and OpenAI Gym
- [Qlearning4K](https://github.com/farizrahman4u/qlearning4k): reinforcement learning add-on for Keras
- [seq2seq](https://github.com/farizrahman4u/seq2seq): Sequence to Sequence Learning with Keras
- [Seya](https://github.com/EderSantana/seya): Keras extras
- [Keras Language Modeling](https://github.com/codekansas/keras-language-modeling): Language modeling tools for Keras
- [Recurrent Shop](https://github.com/datalogai/recurrentshop): Framework for building complex recurrent neural networks with Keras
- [Keras.js](https://github.com/transcranial/keras-js): Run trained Keras models in the browser, with GPU support

## Projects built with Keras

- [RocAlphaGo](https://github.com/Rochester-NRT/RocAlphaGo): An independent, student-led replication of DeepMind's 2016 Nature publication, "Mastering the game of Go with deep neural networks and tree search"
- [DeepJazz](https://github.com/jisungk/deepjazz): Deep learning driven jazz generation using Keras
- [dataset-sts](https://github.com/brmson/dataset-sts): Semantic Text Similarity Dataset Hub
- [snli-entailment](https://github.com/shyamupa/snli-entailment): Independent implementation of attention model for textual entailment from the paper ["Reasoning about Entailment with Neural Attention"](http://arxiv.org/abs/1509.06664).
- [Headline generator](https://github.com/udibr/headlines): independent implementation of [Generating News Headlines with Recurrent Neural Networks](http://arxiv.org/abs/1512.01712)
