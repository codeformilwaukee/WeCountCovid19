# How to contribute to the WeCountCOVID19.com survey

If you're interested in volunteering your time, contact BrianBarkley@codeformilwaukee.org

# Maintenance and publishing 

Below are the steps we will use in order to refresh analysis moving forward:

## Refreshing pre-existing analysis:

1. New analysis images need to be uploaded to the AWS www.wecountcovid19.com S3 bucket in the images folder
2. If the new analysis image is on the home page, the link to the new name of the image needs to be updated on line 166 of the index.html file
3. The new accompanying text to go on the homepage will be put on line 190 of the index.html file
4. After the changes are made to the index.html file, the old file needs to be deleted from the S3 bucket and then new file needs to be uploaded.  Ensure the name of the file is the same before saving any changes.
5. To update the survey responses graph, the same changes will need to be made by uploading the image to the images folder of the S3 bucket
    - The following changes will need to be made to the survey_responses_graph.html file:
        - The new image name will need to be updated in the src tag on line 83 of the file
        - The next analysis to accompany the image will need to be placed on line 84 within the v-card-text tags
        - The update file will need to be uploaded to the S3 bucket after the old file is deleted

## Publishing a new analysis

TBD
