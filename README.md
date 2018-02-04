# FinTechies-Com

##Command temporarily using to move site
```
cp -R -f ./../fintechies-com/ ./htdocs/
```

##Command to build docker container
```
docker build -t fintechieswebsite .
```

##Command using to run the docker container
```
docker run -p 4000:80 fintechieswebsite
```