# Containerize Django Application
  Before containerizing docker application make sure you to allow inbound traffic rules for port 8000
  ![Screenshot (117)](https://github.com/user-attachments/assets/8d75783e-03da-426f-89dd-8b52a045b6f5)


## Steps :
   1. Clone your github repo
      ```
      git clone https://github.com/aditya281121/Docker-Zero-to-Hero.git
      cd Docker-Zero-to-Hero/examples/python-web-app
   2. Build your image
      ```
      docker build .
   3. Check your image and copy your image id
      ```
      docker images
   4. Run your docker container
      ```
      docker run -p 8000:8000 -it [image-id]

 ##  Output
  ![Screenshot (118)](https://github.com/user-attachments/assets/a511d216-1178-48a7-89ca-229dd7aba0ff)

  ![Screenshot (119)](https://github.com/user-attachments/assets/66a73c86-c166-4574-bdce-02e502e9214b)

