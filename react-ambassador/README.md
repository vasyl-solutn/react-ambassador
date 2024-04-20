docker build --build-arg REACT_APP_BASE_URL=http://34.110.220.226/api/ambassador -t gcr.io/zeta-structure-418319/react-ambasador:latest .

docker run -p 80:80 gcr.io/zeta-structure-418319/react-ambasador:latest
