## Implementation of Semantic Segmentation for comparison of model architectures like Unet, DeeplabV3+ and PSPNet.
1. UNet:
UNet is a convolutional neural network (CNN) architecture designed primarily for biomedical image segmentation. It has a symmetrical encoder-decoder structure with skip connections that allow feature maps from the encoder to be concatenated with the corresponding decoder layers. This helps preserve spatial information and improve segmentation accuracy, especially in cases where fine details are important. UNet is widely used in medical imaging tasks due to its ability to perform pixel-wise segmentation effectively even with a limited dataset.

2. DeepLabV3:
DeepLabV3 is a semantic segmentation model developed by Google. It introduces several innovations like atrous (dilated) convolutions, which help in capturing multi-scale contextual information without losing resolution. The architecture also uses an Atrous Spatial Pyramid Pooling (ASPP) module that applies multiple atrous convolutions with different dilation rates to extract features at various scales. DeepLabV3 improves segmentation accuracy in complex environments and is often used in applications like autonomous driving and satellite imagery.

3. PSPNet (Pyramid Scene Parsing Network):
PSPNet is a semantic segmentation architecture known for its ability to capture global context. It uses a pyramid pooling module that fuses information from different regions of the image at multiple scales, enabling better understanding of both small and large objects in a scene. The pyramid pooling effectively gathers context from the global image while preserving local details, making PSPNet particularly suited for large-scale scene parsing tasks such as urban street segmentation and landscape analysis.
