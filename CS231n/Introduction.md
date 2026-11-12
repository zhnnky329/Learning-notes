# Introduction

CS231n mainly focuses on the intersection of **Computer Vision** and **Deep Learning**.

## The history of Vision research

**In 1959**, Hubel and Wiesel used electrodes to record the activity of neurons in cats' primary visual cortex.

- Each neuron has its own **receptive field**: it responds to visual stimuli in a particular region of space.
- **Simple cells** respond to edges with specific orientations; **complex cells** can respond to movement and show some translation invariance.
- The visual pathway is **hierarchical**: information is processed from simple features to more complex ones. This later inspired the design of CNNs.

**In 1963**, Larry Roberts completed one of the earliest PhD theses in computer vision. He studied how to recover 3D shapes by analyzing surfaces, edges, corners, and other features in images. This is considered an important starting point for computer vision.

**In 1966**, MIT launched the **Summer Vision Project**, attempting to build a vision system in one summer. The task turned out to be far more difficult than expected.

**In the 1970s**, **David Marr** proposed studying vision systematically through different stages of visual representation (later described in his book *Vision*, published in 1982):

$$
\text{Input Image} \to \text{Primal Sketch} \to 2\frac{1}{2}\text{-D Sketch} \to \text{3-D Model Representation}
$$

- **Primal Sketch**: extracts edges, lines, blobs, and other basic image structures.
- **2½-D Sketch**: represents visible surfaces, including local depth and surface orientation, from the viewer's perspective.
- **3-D Model Representation**: builds a more complete description of objects in 3D.

**In 1979**, **Recognition via Parts** used simpler components (e.g., generalized cylinders) and their spatial relationships to represent objects.

**In the 1980s**, digital image processing developed further. **Edge detection** became an important research topic, with the **Canny edge detector (1986)** as a representative method.

Then came an **AI winter**: enthusiasm and funding declined, but research in computer vision, robotics, and other subfields continued.

**In 1997**, **Recognition via Grouping** developed, represented by **Normalized Cuts**: grouping pixels or regions based on their similarities.

**In 1999**, David Lowe introduced **SIFT** (Scale-Invariant Feature Transform), which detects and describes local features for matching images, even under changes in scale and rotation. It became an important technique in **Recognition via Matching** in the 2000s.

**In 2001**, **Viola–Jones face detection** became one of the early successful applications of machine learning to computer vision.

**Around the early 21st century**, the spread of digital images and the Internet made larger visual datasets possible. Benchmarks such as **Caltech-101** and **PASCAL VOC** helped evaluate recognition and detection methods.

Meanwhile, **neural networks** were developing along another line:

- **1958–1969 — Perceptron**: an early trainable neural-network model. Its single-layer form cannot solve XOR, a limitation highlighted by Minsky and Papert.
- **1980 — Neocognitron**: a hierarchical visual model using ideas similar to convolution and pooling.
- **1986 — Backpropagation**: made it practical to compute gradients and train multilayer networks.
- **1998 — LeNet**: applied convolutional networks to handwritten digit recognition.
- **2000s — Deep Learning**: researchers explored deeper networks, but large datasets and computing resources were still limited.

**In 2009**, **ImageNet** provided a large-scale labeled image dataset (about 15 million images across 22,000 categories). The ImageNet classification challenge used a smaller subset of about 1.4 million images and 1,000 classes.

**In 2012**, **AlexNet** achieved a major improvement in the ImageNet competition, marking a turning point for deep learning in computer vision.

The modern AI revolution was driven by the combination of **neural-network algorithms + large datasets + GPU computing power**.

## CS231n overview

- **Deep Learning Basics**: image classification, linear classifiers, optimization, and neural networks.
- **Understanding the Visual World**: CNNs, detection, segmentation, video understanding, and related models.
- **Beyond Recognition**: self-supervised learning, generative models, vision-language models, 3D vision, and embodied intelligence.
- **Human-Centered AI**: applications and the potential benefits and risks of computer vision.

