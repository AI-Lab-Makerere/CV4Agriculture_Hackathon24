# Making Submissions
Submissions will be made to a web portal by uploaded a CSV file with the predictions on the test set.  
Before you upload your result, please take note of the following.
1. A submitted file must be strictly CSV. None CSV files will not be rejected on upload.
2. The submitted file must be named according to the team name. For example, if the team is called **TeamApex**, the file must be named as `TeamApex.csv`. Files named with incorrect team names will be rejected.
   The system has been designed to only accept registered team names.
   NOTE: If you try to upload and the name is rejected yet it was submitted, you can <a href="mailto:tusubirafrancisjeremy@gmail.com">Send an email</a> to support and this will be rectified within 24 hours.
3. You must submit the correct file to the correct link. There are 2 distinct links for each task i.e. Maize Classification and Cocoa Detection.

## Maize Classification Submission
The CSV file for the maize classifcation task must be formated as hown in the picture below.
<img src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/maize_submission.png"/>
The file contains 6 columns, the filename and the classes for the classfication task:
 - **filename** - This is the name of the image file in the test set. The order of the filenames in the CSV does not matter.
 - **healthy**  - The predicted Probability/Confidence of the sample belonging to the `healthy` class.
 - **mlb**  - The predicted Probability/Confidence of the sample belonging to `mlb` class.
 - **mln**  - The predicted Probability/Confidence of the sample belonging to the `mln` class.
 - **msv**  - The predicted Probability/Confidence of the sample belonging to the `msv` class.
 - **faw**  - The predicted Probability/Confidence of the sample belonging to the `faw` class.

[SUMISION LINK FOR MAIZE CLASSIFICTAION](http://104.154.155.23/eval/maize_class/)  


## Cocoa Detection Submission
The submission CSV file for cocoa dtection must be formatted as shown below.
<img src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/cocoa_submission.png"/>
The CSV file has 7 columns;
- **Image id** - This is the filename of the image in the [test dataset](https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/guides/Datasets.md)
- **Class** - The predicted class of the object. This must be one of the classes defined [here](https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/guides/Datasets.md).
- **Confidence** - The predicted probability of a detected object belonging to the predicted class.
- **xmin, ymin, xmax, ymax** - The `normalized` coordinates for the predicted object's bounding box.

[SUMISION LINK FOR COCOA DETECTION](http://104.154.155.23/eval/cocoa_det/)  

# THE SUBMISSION PLATFORM
The results for noth Maize Classfication and Cocoa Detection will be submitted on a web platform.  
The platform will enable a user to upload a CSV file and if the file passes the validation checks, the result be will be displayed to the user and also put on the ranked leaderbord for each 
respective challenge.

### [Maize Classfication Submission](http://104.154.155.23/eval/maize_class/)
The [webpage](http://104.154.155.23/eval/maize_class/) will display both the leaderboard and aslo serve as a results upload page.   
To upload a file, click the choose file window shown in the image below and this will open a filebrowser for you to select the file.  
Files that pass the validation tests will be processed and the results will be updated on the leaderboard after a few seconds. You will also see a notification with the score attained for that submission.
The leaderboard will be updated and your team will be ranked based on the score attained.  
To view all results from the submissions made by a team, click on the team name on the leaderboard table and this will show all results attained by the team for each submission.

<img src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/maize_class_process.gif"/>

### [Cocoa Detection Submission](http://104.154.155.23/eval/cocoa_det/)
This is currently disabled to enable update of the backend.


