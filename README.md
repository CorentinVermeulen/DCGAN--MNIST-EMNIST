# DCGAN--MNIST-EMNIST

## STEP 1: GAN
Training of a generator and a discriminator for both MNIST and EMNIST data set. 
This way we are able to generate new data (digit or letter)

## STEP 2: GENERATE DESIRED OUTPUT
We trained a cnn to predict class of a given digit/letter. This was used to save latent vector producing a certain class. 
This way we are now able to generate the desired letter/digit by passing the corresponding latent vector to the generator. 

