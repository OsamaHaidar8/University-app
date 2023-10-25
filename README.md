# Docker assignment by: Osama D. Haidar


This application is only dedicated to displaying student data and also performing known operations on it (modify - delete - add).

## Students' App

The application documentation is published online at:

[https://github.com/OsamaHaidar8/university-app](https://github.com/OsamaHaidar8/university-app)


## Running Locally

If you wish to run the this application locally, you can use the following command after installing Docker Desktop:

```bash
docker run --name=std-app -d -p 8050:80 osamahai8ar/students-app:latest
```

Once it has started, you can open your browser to [http://localhost:8050](http://localhost:8050).
