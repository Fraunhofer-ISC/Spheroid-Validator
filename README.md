Spheroid Validator (ResNet-50)

Binary image classifier that labels 3D tumor spheroids as valid or invalid.
Includes a simple, robust inference script for batch prediction over a Test/ folder.

Features

ResNet-50 backbone with a custom classification head.

Consistent preprocessing (resize, normalization).

Batch inference over a folder of images.

CSV output with predicted class and confidence.

Flexible class naming:

Auto-detects classes from Dataset/train/<class_name>/...

Or pass class names via --classes "invalid,valid"
