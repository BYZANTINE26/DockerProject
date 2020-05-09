# DockerProject
This is the first docker project created by me in this project. I used haproxy server for load balancing by launching all servers linked to each other. Then I used docker-compose to initialise the whole multi-tiered infrastructure in one go. This is possible with the help of Vimal Daga sir and IIEC-RISE community.

![Docker Images](https://user-images.githubusercontent.com/62672863/81480560-21c3c480-9248-11ea-8563-df635070b271.png)

haproxy:v1 and httpd:2 are two custom docker images based on centos image , upon which i installed haproxy and httpd servers respectively.

![docker-compose up](https://user-images.githubusercontent.com/62672863/81480600-559eea00-9248-11ea-9432-0716caf38d47.png)

![Running Containers](https://user-images.githubusercontent.com/62672863/81480577-3738ee80-9248-11ea-88ab-bda48fdd6860.png)

![HAProxy](https://user-images.githubusercontent.com/62672863/81480432-6e5ad000-9247-11ea-9c05-2f5800b1c3b5.PNG)
