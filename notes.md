> NOTE: This has been suspended for the remainder of the summer

# general plan:

1. figure out what map is needed
2. figure out if analysis needs to be done on the map
3. build the map in arcgis online
4. have website grab the map from arcgis online using [this](https://developers.arcgis.com/javascript/latest/tutorials/display-a-web-map/) guide

# things to remember:

This needs to be a very automatic process that can be repeated on arbitrary cities (assuming the data is available).
Avoid re-inventing the wheel.

# Deploying with github actions references:

[info about proper organization of secrets](https://stackoverflow.com/questions/65957197/difference-between-githubs-environment-and-repository-secrets)
[s3-deploy-action](https://github.com/marketplace/actions/s3-deploy)


# architecture

vue/vuetify
arcgis online
aws


# TODO

-[x] setup the repo
-[ ] get arcgis api key
-[ ] enable dist workflow