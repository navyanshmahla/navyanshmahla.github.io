---
order: 3
---

Welcome to by projects section. Here I talk about the projects that I've done in the past. I'm not mentioning every project, just the ones which are worth showing up on this list. For some you'll find the GitHub link and for some you won't!

## [Super Image Resolution Network](https://github.com/navyanshmahla/super-image-resolution-network)

Probably the project which had the most steep learning curve of all. This project was basically an assignment of internship that I never did because I got a better offer from Marsh McLennan. That's an interesting story in itself! 

But the aim of the project was to develop and train a Super Image Resolution Network using GANs. I had the time of five days to do it and too when the endsemester examinations were going on!

I used two different approaches to do this project. One was using the Autoencoders and the other was using SRGANs. The SRGAN approach was basically a **research paper** implementation of [this paper](https://arxiv.org/pdf/1609.04802.pdf). I trained the network on EC2 instance running on Nvidia Tesla T4 16GB GPU which fell short in memory :P
I could have made it work in 16GBs by reducing the batch size and manipulating the architecture according to my needs, but since I was implementing a research paper I wanted to keep the things exactly the same as mentioned in the paper. 

## [Road Accident Prevention System](https://github.com/navyanshmahla/RAP-Road-Accident-Prevention)

This was one of my first Deep learning projects that I did in the summers of my first year as a part of Seasons of Code (SoC) organised by WnCC. The project aimed to build a road accident prevention system which looks out for the drowsiness in the eyes of the person and classifies whether he should drive or not.

The project was accomplished using a simple **Convolutional Neural Network** (CNN) of 4 layers. The system worked well in bright day-light but struggled when there was lens glare at night with the people using spectacles. This was mainly because of lack of light and poor cameras. It could have been easily solved with a larger dataset incorporating night photographs of eyes.

