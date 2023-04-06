# tensorflow-dev-cert

##Setting Up Environment

Following article - [https://www.mrdbourke.com/get-your-computer-ready-for-machine-learning-using-anaconda-miniconda-and-conda/]

- Setup Pyenv (Using Python 3.10.8)
- Download Miniconda - https://docs.conda.io/en/latest/miniconda.html?ref=mrdbourke.com
- Set up Conda environment - `conda create --prefix ./env pandas numpy matplotlib scikit-learn`
- Activate Conda environment - `conda activate /Users/jasneetsingh/git/tensorflow-dev-cert/env`
 
## Section 2 - Deep Learning and Tensorflow Fundamentals

- What is deep learning? Video
- What are neural networks?
- What is DL already being used for?
 - Translation
 - NLP
- What is and why use Tensorflow?
- What is a Tensor?
- Creating Tensors with Tensorflow
- tf.Variable() Vs tf.Constant() + tf1[0].assign()
- Random tensors 
	- tf.random.uniform(shape=(3,2)) Vs tf.random.normal(shape=(3,2))
	- tf.random.Generator.from_seed(42) // set seed for reproducibility 
 - Shuffling order of tensors
	-  tf.random.shuffle(unshuffled).set_seed()
	- Global (tf.random.set_seed()) Vs Operation level seeds
