# Skin Cancer Diagnostic Using Deep Learning

## Inspiration
Having studied AI theory in the news and in research papers, I thought BostonHacks was a great opportunity to advance my skills in the application of machine learning. As I contemplated what algorithm to use, I figured transfer learning fitted well in the limited time of one day. After listening to the sponsors' talks, I came up with the idea to apply deep learning to healthcare. My first idea was to create an app that could diagnose any skin disease by taking a picture. But after surfing through datasets of diseases, I realized that there were not enough images to do so. Then, I came across melanoma, a skin cancer that can become deadly if not diagnosed early enough. Realizing this, I couldn't back down from the challenge.
## What it does
Diagnosing melanoma is hard to do when only given a look at the mole, so usually, a biopsy is required. This model can help reduce the time needed to detect melanoma. The machine learning algorithm takes in input images of moles and then classifies whether or not a malignant form of melanoma exists. After training the model, it can be used to detect if a mole has developed, or may develop, into melanoma. It does this at a best of 82% accuracy.
## How I built it
I used the machine learning library, PyTorch, to develop a deep neural network on a Linux virtual machine. Because images have high dimensionality, it is extremely power and time consuming to train a deep neural net solely on such. So I used transfer-learning, which is a method of using a model pre-trained on millions of images, and then applying a smaller neural network to the output of that model. This speeds up the process and allocates more time to develop more specific differentiation.
## Challenges I ran into
I tried installing Pytorch on windows, however, the unofficial build caused many problems and broke other dependencies. So I sacrificed the benefit of GPU acceleration to build a more stable application on a slower virtual machine.
## Accomplishments that I'm proud of
I am proud that I have gotten my first real-world application of machine learning working. I had previously struggled a lot with deep learning libraries because of their rapidly changing architecture.
## What I learned
I strengthened my knowledge in Python throughout my development in machine learning. And boosted my confidence to apply machine learning to a broader spectrum of things.
## What's next?
It could definitely gain more accuracy by training on a larger dataset and improve by adding the identification of more skin conditions. It would be great to build an app that automatically identifies the diseases with only a picture. It could also suggest ways to prevent, mitigate, or reach help about a specific skin condition.

## Resources
http://pytorch.org/

https://isic-archive.com/

http://isdis.net/isic-project/