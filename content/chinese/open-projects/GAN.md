+++
date = "2020-05-22T14:45:00+02:00"
title = "用于图像恢复的 GAN inversion"
description=""
short_description = "Computer vision for a Intelligent Life and Biometrics for a Secure Life"
sort_position = 4
+++

# 项目介绍

As a kind of generative model, GAN can transform a random noise to a specific domain of image like face image, car image, cat image, etc. 
Its performance is quite remarkable such that it is hard for humans to distinguish between the pictures it generates and the real pictures, which makes people think that GAN has learned the physical rules behind the pictures it generates. We call what it learns as GAN prior. And the strategy used to make use of GAN prior is called GAN inversion. It is common to make use of prior information to do image restoration tasks.  But to use GAN prior for image restoration tasks remains challenging. We aim to study this problem and develop a corresponding algorithm.

We will explore the topic in the following directions:

- Reproduce and analyze current SOTA algorithms in exploring GAN prior;

- Explore combining GAN with other generative models(e.g., VAE, normalizing flow) to make use of GAN prior;

