# SinGAN
This is a reimplementation of SinGAN proposed by Tamar Rott Shaham in 2019 and it is written in Tensorflow 2.0.
This model is an unconditional generative adversarial network trained on a single natural image. After training, the model is able to capture the inner distribution of the training image. As a result, the model can generate realistic and highly diverse images. Also, the model can be applied to multiple image manipulation tasks including image harmonization, image editing, and paint to image translation.

The uploaded file is an notebook file. For all tasks, you need an training image under the same directory of this code. For paint to image translation you also need an injected image and for image editing/harmonization you need both injected image and masked injected image. And then you can simply run all the code block. See more details in the report.
