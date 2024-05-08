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
The webpage will display both the leaderboard and aslo serve as a results upload page.   
To upload a file, click the choose file window shown in the image below and this will open a filebrowser for you to select the file.  
Files that pass the validation tests will be processed and the results will be updated on the leaderboard after a few seconds.

<img src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/maize_submission_portal.png"/>
