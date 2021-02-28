# quiktransport
 
Setting up heroku

Add the following as Buildpacks

    https://github.com/timanovsky/subdir-heroku-buildpack
    heroku/nodejs

Add the following Config Vars

    PROJECT_PATH server
    ORIGIN_URL https://quiktransport.co.uk
    API_KEY "SEND GRID API KEY"
    TO_EMAIL "EMAIL TO SEND TO"
    FROM_EMAIL quiktransportrecovery@outlook.com
