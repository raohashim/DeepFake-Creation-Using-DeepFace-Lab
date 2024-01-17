# DeepFake-Creation-Using-DeepFace-Lab

## DeepFake Creation Using DeepFace-Lab

DeepFaceLab is a powerful tool that provides realistic face-swapping results. It's flexible and efficient, making it easy to use and perfect for all your deepfake needs. Just follow the instructions here to create your face swap videos.
Training via NVIDIA or AMD GPUs.
To install and use DeepFaceLab, please follow the steps below:
1. Installation: Download and install the compatible version of DeepFaceLab from the following link: https://mega.nz/folder/Po0nGQrA#dbbttiNWojCt8jzD4xYaPw.

2. Data uploading: Upload the source video (data_src) and the target video (data_dst) that will be replaced with the source video in the workspace folder.

3. Pre-processing: Extract images from the source video (data_src) and the target video (data_dst) using the "extract images" scripts. Then, use the "extract faces S3FD best GPU" scripts to extract faces from both videos and save them in separate folders (data_src and data_dst).

4. Training: Train your model using the training scripts, and choose the settings that best suit your needs from the "modelname_summary.txt" files in each model folder.

5. Conversion: Use the convert script to swap faces between the source and target videos in each frame. You can also use several productivity tools if needed.

6. Result: Convert your final video to the lossless MP4 format for a high-quality face swap deepfake video.

## Training via Google Colaboratory Pro
The process of using Google Colaboratory to create fakes is quite similar to using the CLI of DeepFaceLab. However, Google Colaboratory offers more GPU power, which speeds up the process. Users can train fakes for free by visiting https://github.com/chervonij/DFL-Colab.

Here are the steps to follow:
1. Pre-processing: Follow the first three steps mentioned above for pre-processing. Then, create a workspace.zip file containing all pre-processed data and upload it to Google Drive.

2. Installation: Clone DeepFaceLab in the Google Colaboratory environment and import the workspace.zip file from Google Drive.

3. Training: Train your model in the Google Colaboratory environment using SAEHD and Quick96 configuration. Be sure to adjust the settings as mentioned in the modelname_summary.txt files in each model folder.

4. Conversion: Use the merge script to swap (source to destination) faces.

5. Result: Finally, use the result video mode to concatenate the frames and obtain the face swap deepfake.
