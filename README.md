# MVC - Neural Network Project / 25I-3047

## Description
This is an implementation of a Multi-Layer Perceptron network (MLP) from 
scratch using NumPy only, trained on the MNIST handwritten digit dataset.

## Architecture
784 (input) --> 128 (sigmoid) --> 64 (sigmoid) --> 10 (sigmoid output)

## How to Run
1. Install requirements:
   pip install numpy matplotlib jupyter
2. Open the notebook:
   jupyter notebook src/mvc_mlp_25I-3047.ipynb
3. Run all cells top to bottom (Kernel → Restart & Run All)
   MNIST downloads automatically on first run.

## Results
- Test accuracy: 95.54% 
- Epochs: 10
- Learning rate: 0.1
- Batch size: 32

## Repository Structure
- src/  -->  Jupyter notebook with all outputs
- data/ -->  MNIST dataset (mnist.npz)
- report/ -->  Compiled PDF report (Task 8)

## References
- https://www.iro.umontreal.ca/~vincentp/ift3395/lectures/backprop_old.pdf
- http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf
