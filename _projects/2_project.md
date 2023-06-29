---
layout: page
title: FaceRec
description: A machine learning program that was capable of recognizing facial features.
img:
importance: 1
category: work
---

For my final project for my machine learning class, I decided to make an application that could recognize facial features. I had been reading some papers about using ML to recognize objects within pictures, and wondered if an ML program would be capable of recognizing facial features. As it turns out, it can.

The program was mainly written using Pytorch in Jupyter Notebook, and took me about a month to complete. It could recognize facial features with somewhat decent accuracy, but more interestingly, it seemed to be very good at consistantly giving the same features for the same people. Even if the program got some features wrong, it would always give the same features for the same people, regardless of lighting, angle, clothing, or other factors.

The program was trained on CelebA, a large database containing pictures of celebrities, each picture with its own label.

You can check out the project <a href="https://github.com/Toasterdoodle/facerec">here</a>.