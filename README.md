# Deeplens-draft
DeepLens Sign to Voice Recipe
#Importing the model
Click the link to get the model file.
```bash
s3://deeplens-asl-classification-super/output/asl-classification-super-job-5/output/model.tar.gz

```



Create the inference function
The Lambda function folder contains of all the script need for the project.

Play sound through a Deeplens
Connect the deeplens through a mirco hdmi cable and login into the device.
Start the terminal and copy paste the code 
```bash
sudo apt-get update
sudo apt-get install tesseract-ocr
sudo apt-get install python-gi
sudo pip install playsound
sudo systemctl restart greengrassd.service --no-block
```
 
