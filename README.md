# Style-Transfer-Using-GAN
Problem statement: To build a Generative adversarial model(modified U-Net) which can generate artificial MRI images of different contrast levels from existing MRI scans.

Misdiagnosis in the medical field is a very serious issue but it’s also uncomfortably common to occur. One of the complicated tasks in medical imaging is to diagnose MRI(Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding. But to have access to different imaging is difficult and expensive. 

With the help of deep learning, I used style transfer to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image. In this project, I used CycleGAN to translate the style of one MRI image to another, which will help in a better understanding of the scanned image. Using GANs, I create T2 weighted images from T1 weighted MRI image and vice-versa.
