# ATLAS AutoEncoder

## Evaluation Exercise
> This my submission for the Evaluation Exercise.
main.ipyb is the notebook which contains the code for normalising the data, training the model and plotting the results.

## Introduction
> An autoencoder is a neural network that learns to copy its input to its output. It has an internal (hidden) layer that describes a code used to represent the input, and it is constituted by two main parts: an encoder that maps the input into the code, and a decoder that maps the code to a reconstruction of the input.

![AutoEncoderImage](https://www.compthree.com/images/blog/ae/ae.png)

## Code

### Extract_Output
> We iterate over `input.csv` and check if the given event has jets. If jets are present, they are extracted and put into `extracted_output.csv`

### Main 
> It consists of three parts
> * Importing data and normalising it.
> * Create and train model on data.
> * Plot the Results