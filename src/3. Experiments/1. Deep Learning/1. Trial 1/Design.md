# **Experiment Plan: Applying Different Architectures to Placenta Ultrasound Images Datasets**

## **Datasets for Analysis**
- **C3 all planes**: At least one of three conditions (CIR, preeclampsia, birth weight percentile <3) is present.
- **LBW all planes**: Focus on birth weight percentile <3 only.
- **CIR all planes**: Focus on CIR only.
- **PRE all planes**: Focus on preeclampsia only.

## **Experimental Approach**
We will apply different neural network architectures to the datasets in their original form to assess the effectiveness of each model and to get a baseline.

## **Neural Network Architectures**
- **Basic Architectures**:
  - Basic ANN: A simple artificial neural network as a baseline.
- **VGG16 Variants**:
  - VGG16, initializing with ImageNet weights, but all weights are updated.
  - VGG16, with transfer learning (ImageNet weights are frozen).
- **ResNet50 Variants**:
  - ResNet50, initializing with ImageNet weights, but all weights are updated.
  - ResNet50, with transfer learning (ImageNet weights are frozen).
- **MobileNet Variants**:
  - MobileNet, initializing with ImageNet weights, but all weights are updated.
  - MobileNet, with transfer learning (ImageNet weights are frozen).
- **ResNet18 Variants**:
  - ResNet18, initializing with ImageNet weights, but all weights are updated.
  - ResNet18, with transfer learning (ImageNet weights are frozen).

## **Conclusion**
This experiment aims to systematically compare the performance of various neural network architectures on the same image dataset. By employing both basic and advanced models, with and without transfer learning, we aim to identify the most effective approaches for image analysis in this context.
