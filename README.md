## Tracing Englacial Layers in Radargram via Semi-Supervised Method: A Preliminary Result
## Abstract
The melting of ice sheets significantly contributes to sea level rise, highlighting the crucial need to comprehend the structure of ice for climate benefits. The stratigraphy of ice sheets revealed through ice layer radargrams gives us a window into historical depth-age correlations and accumulation rates. Harnessing this knowledge is not only crucial for interpreting both past and present ice dynamics, especially concerning the Greenland ice sheet, but also for making informed decisions to mitigate the impacts of climate change.
Ice layer tracing is prevalently conducted using manual or semi-automatic approaches, requiring significant time and expertise.
This study aims to address the need for efficient and precise tracing methods in a two-step process. This is achieved by utilizing an unsupervised annotation method (i.e., ARESELP) to train deep learning models, thereby reducing the need for extensive and time-consuming manual annotations. We benchmarked the popular U-Net segmentation model and its variants such as U-Net with VGG19, U-Net with Attention mechanism, and U-Net with Inception. Additionally, various thresholding methods such as binary, Otsu, and CLAHE have been explored to achieve optimal enhancement for the true label annotation images. Our preliminary experiments indicate that the combination of attention U-Net with specific processing techniques yields the best performance in terms of the binary IoU metric.

## Paper
The paper has been accepted in the proceedings of AAAI 2023 Fall Symposium Series.

Jebeli, Atefeh, Tama, Bayu Adhi, Purushotham, Sanjay, and Janeja, Vandana “Tracing Englacial Layers in Radargram via Semi-supervised Method: A Preliminary Result” Association for the Advancement of Artificial Intelligence Fall Symposium, September 2023

## Citation
If you use any part of this code for academic work, research, or any other projects, please cite our paper.
