# Video_SuperResolution

The project proposes a new approach to enhance video super-resolution by integrating image super-resolution techniques with a temporal dimension. The first proposed method introduces a modified version of an SRCNN, which combines multiple neighboring motion-compensated frames using a new architecture. The second approach uses a signal-process technique to combine the frames, super-resolved by a pre-trained ESRGAN.  Moreover, the study proposes and experiments with different loss functions, including Feature Space Loss and Motion Aware Loss, and compares them to the traditional MSE. To train the networks, pre-trained SRCNN models are used to initialize the weights, and the proposed approach is evaluated on different scenes from the CDVL dataset. The evaluation is performed using objective metrics such as PSNR and SSIM. The proposed approach offers a promising solution for real-world video super-resolution applications.

### Code Files

VSR_Net_SRCNN_MSE: Modified SRCNN Network Structure

VSR_Net_SRCNN_VGGLoss: Modified SRCNN Network Structure with Feature Space (VGG) Loss

VSR_Net_SRCNN_MotionLoss: Modified SRCNN Network Structure with Motion-Aware Loss

Multi-Sensor_Image_Fusion: Combining Images via the Wavelet Transform 

Hypothesis_Testing: Hypothesis Testing Code

### Data Files

CV_Results.csv - PSNR and SSIM scores on the test videos (used for Hypothesis Testing)
