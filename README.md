# cloud-native-workshop-v2m3-guides
Forked from:
https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m2-guides

Run it with docker:

docker run -it --rm -p 8080:8080 -v $(pwd):/app-data -e CONTENT_URL_PREFIX="file:///app-data" -e WORKSHOPS_URLS="file:///app-data/_cloud-native-workshop-module2.yml" -e LOG_TO_STDOUT=true               quay.io/osevg/workshopper:edge