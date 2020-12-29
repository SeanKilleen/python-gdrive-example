# Steps

## Enable Drive API

- Visit <https://developers.google.com/drive/api/v3/quickstart/python>
- Click `Enable Drive API`
- Follow the steps (I chose `Desktop Application` from the app type list)
- Download the resulting credentials.json (don't commit to source control if you're using source control. I've git-ignored the file in this repo.)

## Get the basics set up

- Create a folder where this stuff will live
- Install python 3.x
- Install libs referenced from the drive quickstart: `pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib`

## From here

- Modify the scopes you'll need
- Once you've got the auth flow, call the rest of your code.
