# Cloud-Removal-In-Satellite-Images-Using-GAN

I had worked on this project under the guidance of Chintan Maniyar (a Researcher at ISRO) on removing the clouds from satellite images using Generative Adversarial Networks.

## Summary
Cloud cover in the earth's atmosphere is a major issue in temporal optical satellite image processing. Clouds, thick or thin, cover the earth features in a satellite image and hide important information. The objective of this project is to develop a deep learning based automated pipeline to remove cloud cover from optical satellite imagery. Conditional GANs architecture is used to learn the mapping of the cloudy satellite image to it's cloud-free counterpart. A novel augmented and computationally efficient training approach is suggested.


## GAN
We had used pix-2-pix GANS for the same.
pix-2-pix GAN model is used for learning the mapping of the cloudy image to it's cloud-free counterpart. It follows a supervised conditional vector based training approach. The model is trained on the cloudy and cloud-free image pairs which are dated two days apart. pix-2-pix model follows a pixel to pixel image restoration approach and generates a new pixel cloud-free for every cloudy pixel.