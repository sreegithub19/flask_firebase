# flask_firebase
- Reference: https://medium.com/firebase-developers/hosting-flask-servers-on-firebase-from-scratch-c97cfb204579

Steps to deploy and run:

- Create firebase project
- Install gcloud
    - Windows path (C:\Users\Padmaja\AppData\Local\Google\Cloud SDK)

- Switch into project directory in terminal and type : "gcloud init"
- After you have initialized everything, open a terminal to the server directory and run the following command:
"gcloud builds submit --tag gcr.io/<project-id>/flask-fire"
,i.e. gcloud builds submit --tag gcr.io/flask-firebase-33ba9/flask-fire
