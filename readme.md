<!-- to build docker image -->

docker build -t app2-image .

<!-- to convert docker image into tar -->

docker save -o app2-image.tar app2-image

<!-- to run in pc -->

docker run -p 8082:8082 app2-image
