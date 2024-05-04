# vision_Informed_Mamba
Vision-Informed Mamba (VIM): A Position-Aware Model for Healthcare Dataset Classification


# Architecture

Patch Embedding (PatchEmbed2D)

Converts an image into a sequence of flattened, non-overlapping patches. This is a common preprocessing step in vision transformers where the input image is split into multiple patches, and each patch is treated as a token or an input element for the transformer.

Selective Scan Module (SS2D)

Purpose: Implements a specialized attention mechanism that selectively processes information based on Utilizing a series of linear transformations and a convolutional layer to process the input data. It is also a technique that can reduce computational complexity and improve performance by focusing on relevant parts of the data.
It also  Handles data transformations that respects the temporal or spatial relationships inherent in the data.
    
Convolutional Blocks 

Composed of three convolutional layers where the first 2 have a kernel size of 3x3 and the last one has a kernel size of 1x1. Each 3x3 convolution is followed by batch normalization and a ReLU activation, that to extract and refine features from the input.
    
    