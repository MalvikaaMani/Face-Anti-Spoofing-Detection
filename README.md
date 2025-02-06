# Face-Anti-Spoofing-Detection
<h1> Description</h1>
Face presentation attack detection is critical for ensuring the robustness of 
biometric systems. This project explores the training and evaluation of two state
of-the-art deep learning models, EfficientNetB7 and ResNet50, for detecting 
presentation attacks using the SynthASpoof dataset.
<br>  The dataset includes bonafide images and various synthetic attack images. 
<br>  Both models were fine-tuned on this dataset, and their performances were compared in terms of 
accuracy, loss, and confusion matrix metrics. 
<br> The dataset is systematically divided into training (70%), validation (20%), and testing (10%) 
subsets.
<h2> Description of the Dataset </h2>
The SynthASpoof dataset was curated specifically for research in face presentation 
attack detection. It addresses the need for a diverse dataset that includes both bona fide 
and synthetic attack images to simulate real-world attack scenarios.
<br> Classes and Categories: 
<br> 1. BonaFide: Genuine face images without any tampering or attacks. 
<br> 2. Samsung_ReplayAttack: Synthetic images replayed using a Samsung device, 
simulating digital screen replay attacks. 
<br> 3. Webcam_ReplayAttack: Synthetic images replayed using a webcam, simulating 
basic attack scenarios. 
<h3> Technologies Used</h3>
 1. Python
<br> 2. IDE- VS Code
<h4> References </h4>
 1. https://github.com/meilfang/SynthASpoof
