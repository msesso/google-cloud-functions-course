# Gooogle Cloud Functions Course

## Starting a project

To start a new project in Google Cloud, we can go to the [Firebase Console](https://console.firebase.google.com) or create it from [Google Cloud Platform Console](https://console.cloud.google.com).

## Install dependencies

```pip install -r requirements.txt```

##Deploying function
First, we have to set out project IF with the following command:
```
gcloud config set project [YOUR_PROJECT_ID]
```
Then we deploy our function with this command:
```
gcloud functions deploy [FUNCTION_NAME] --runtime python311 --trigger-http
```