# profile-apps

## Deploying your application to App Engine
When you deploy your application files, your website will be uploaded to App Engine. To deploy your app, run the following command from within the root directory of your application where the app.yaml file is located:

```
gcloud app deploy
```

### Optional flags:
- Include the --project flag to specify an alternate Google Cloud console project ID to what you initialized as the default in the gcloud CLI. Example: --project [YOUR_PROJECT_ID]
- Include the -v flag to specify a version ID, otherwise one is generated for you. Example: -v [YOUR_VERSION_ID]

To learn more about deploying your app from the command line, see [Deploying your application](https://cloud.google.com/appengine/docs/standard/testing-and-deploying-your-app#deploying_your_application).

## Viewing your application
To launch your browser and view the app at https://PROJECT_ID.REGION_ID.r.appspot.com, run the following command:

```
gcloud app browse
```
