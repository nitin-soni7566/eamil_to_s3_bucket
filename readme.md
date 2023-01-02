# Project overview

## This project can upload you csv files email to aws s3 bucket 

- You have  to set config.py 

### In config.py file you have set these vlaues 

   - AWS_ACCESS_KEY_ID = 'xxxxxxxxxxxxxxxxxxx'   
   - AWS_SECRET_ACCESS_KEY ='xxxxxxxxxxxxxxxxx'
   - KEY = "tmp"
   - BUCKET_NAME = "your-bucket-name"  
   - region_name ='eu-west-1'

### If you want to read your file from outlook.com then you have to change 

   - MAIL_READ_HOST = 'outlook.office365.com'



## Your can create moudle of this project using setup.py

# to create module you have to run commad 
- python setup.py sdist bdist_wheel


# we have to function to for read email file name and export email attact file into s3

- read_email_files()
- file_upload_to_s3()