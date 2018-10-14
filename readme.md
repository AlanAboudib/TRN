# TRN
PyTorch authors implementation of the Temporal Relational Network trained on Jester.

## PyTorch version

0.2

## dataset

Before you can use this trained TRN, you need to download the Jester dataset from
<a href = "https://20bn.com/datasets/jester/v1">here</a>.

Once the the dataset is downloaded, put it in a folder called 'jester' inside the repository root folder.

## run the validation test

Here is the command you need to run in order to get the accuracy on the validation set:

    python test_models.py jester RGB model/TRN_jester_RGB_BNInception_TRNmultiscale_segment8_best.pth.tar --arch BNInception --crop_fusion_type TRNmultiscale --test_segments 8
    
