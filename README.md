## train.py
Change line_58: opt.dataroot = "PATH"

## checkpoints/experiment_name/opt.txt
I have changed line_06: opt.dataroot = "PATH"

## test.py
I have changed line_10: from util.metrics import SSIM

## How to use combine_A_and_B.py
1. The name of blur_folder rename to A, sharp_folder rename to B. Both create "train" inside
2. create AB

├───blurred_sharp

│ ├───A

│ │ └───train

│ ├───AB

│ ├───B

│ │ └───train

└───helper functions

