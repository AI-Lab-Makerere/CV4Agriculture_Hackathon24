# Competition Datasets
There are 2 main datasets for this competion:  
## [Maize Classfication Dataset](https://storage.googleapis.com/air-lab-hackathon/Maize/classification/Classification_maize.zip)
  1. This dataset represents 4 maize leaf disease classes
     i.e. MSV, FAW, MLN MLB and 1 class for HEALTHY images. The dataset is split into three sets:
     - Train with **26063** images.
     - Validation with **7445** images.
     - Test with **3729** images.

  3. The dataset can also be downloaded in 1 part 18GB or as 10 multiple parts of approximately 2GB each.
     
     - [Single download link](https://storage.googleapis.com/air-lab-hackathon/Maize/classification/Classification_maize.zip)
     - Multiple parts.
       - [Part 1](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part01.rar)
       - [Part 2](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part02.rar)
       - [Part 3](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part03.rar)
       - [Part 4](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part04.rar)
       - [Part 5](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part05.rar)
       - [Part 6](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part06.rar)
       - [Part 7](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part07.rar)
       - [Part 8](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part08.rar)
       - [Part 9](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part09.rar)
       - [Part 10](https://storage.googleapis.com/air-lab-hackathon/Maize/classification_parts/Classification_maize.part10.rar)
      
     <img src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/maize.png">

  4. The labels for the dataset have been put in two CSV files, `train.csv` and `validation.csv`.
     The CSV contains 6 columns;
     
     - **filename** - The name of the image in either the train or validation folder.
     - **Healthy, MLB, MLN, MSV, FAW** - The labels for the class to which the image belongs. For each row, the column with `1` is the true label for the image while the rest of the columns will have a value of `0`.

     <p style="text-align: center;">Image shows a sample of the labels in a CSV file</p>
     <img height="400" align="center"  src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/maize_csv_label.png"/>

     **NOTE**
     You can use your own configuration with the train and validation sets during the model training.

     

## [Cocoa Detection Dataset](https://storage.googleapis.com/air-lab-hackathon/Cocoa/cocoa_new.zip)
  1. The dataset contains objects in cocoa trees under 4 classes Spoilt, Immature, Mature_Unripe and Ripped. It has been split into 3 subsets.
     
     - Train with **4550** images.
     - Validation with **1262** images.
     - Test with **318** images.
    
  2. The dataset can be downloaded as a single zip file of ~370MB from [here](https://storage.googleapis.com/air-lab-hackathon/Cocoa/cocoa_new.zip).

     <img src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/cocoa_annotated.png" />

  3. The dataset has 2 types of labels.
     The first type is PASCAL VOC XML files for every image with the label information (see picture below) and these are found in the respective train and validation folders alongside the images.
     The second type of label is a CSV file named `labelmap.csv` that is found in the train and validation folders. A row in the CSV represents an object in the image and has 10 columns;

     - **Image id** - The filename of the image in the respective folder. Note that this is repeated for images with multiple objetcs
     - **Actual Label** - The class label of the objects of interest in the image.
     - **xmin, ymin, xmax, ymax** - The bounding box cordinates of the objects in the image.
     - **xmin_norm, ymin_norm, xmax_norm, ymax_norm** - The normalized bounding box coordinates of the objects in the image.
    
  <p style="text-align: center;">Image shows a sample PASCAL VOC annoation in XML format</p>  
  <img height="400" src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/cocoa_xml_label.png"/>

  <p style="text-align: center;">Image shows a sample of the labels in a CSV file for Cocoa</p>  
  <img height="400" src="https://github.com/AI-Lab-Makerere/CV4Agriculture_Hackathon24/blob/main/resources/images/cocoa_csv_label.png"/>

  **NOTE**
  You can use your own configuration with the train and validation sets during the model training.
  
