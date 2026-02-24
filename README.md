# Learning Probability Density Functions using GAN

## Objective
To learn the unknown probability density function of a transformed NO₂ concentration variable using a GAN.

## Dataset
India Air Quality Dataset (NO₂ concentration)

## Transformation
z = x + 3.0 sin(0.9x)

## GAN Architecture
- Generator: Fully connected neural network
- Discriminator: Binary classifier

## Training Details
- Noise ~ N(0,1)
- Binary Cross Entropy loss
- Adam optimizer

## PDF Estimation
Kernel Density Estimation on generator samples

## Observations
- Mode coverage
- Training stability
- Quality of generated distribution
