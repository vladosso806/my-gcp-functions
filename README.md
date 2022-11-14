# my-gcp-functions
NodeJS App for GCP Cloud Functions deployed via GCP Cloud Build

![image](https://user-images.githubusercontent.com/84772222/201654038-28c1b14c-7163-47c7-9645-f519e52a8722.png)


In order to deploy via Cloud Build located in project MANAGEMENT to CloudFunction located in project STAGING,PROD you will need:

In project MANAGEMENT, get email of account for xxxxxxxx@cloudbuild.gserviceaccount.com

In project STAGING and PROD add this account as princial into IAM and add Roles:

IAM Role Name	IAM Role Permission
Cloud Functions Developer	roles/cloudfunctions.developer
Service Account User	roles/iam.serviceAccountUser
