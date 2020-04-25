## Tools

**AWS Cloud9**

[Cloud9](https://docs.aws.amazon.com/cloud9/latest/user-guide/welcome.html) is an browser based IDE for working with Sage Maker. If you already have an AWS account just to [here](https://console.aws.amazon.com/cloud9/)

User: SageMakerOnAWS
url: [console](https://302082288812.signin.aws.amazon.com/console)

pwd: old: f]8dT|GmsT|v
pwd: CharTin2!sag

Get code for the course
```
curl http://us-west-2-tcdev.s3.amazonaws.com/courses/AWS-100-MLS/v1.0.0/exercises/ex-driver.zip -o ex-driver.zip
unzip ex-driver.zip

cd ~/environment/ex-driver
pip-3.6 install -r requirements.txt --user
```
Play the game to generate the CSV file.
```
(sage_course) mac@rise: environment$ ls -ltr ex-driver
total 184
-rw-r--r--  1 rise  staff      6 Oct 14  2018 requirements.txt
-rw-r--r--  1 rise  staff   3499 Nov  6  2018 inference.py
-rw-r--r--  1 rise  staff   2692 Nov  6  2018 training.py
```
Create run file `run.sh` to encapsulate the run command
```
run.sh
```
Run the program via the run script. Keep the car on the road
and it will generate a .csv file
```
training.csv
```

create an S3 bucket. Named it `sf-edx-sagemaker` 