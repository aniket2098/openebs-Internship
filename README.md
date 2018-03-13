Steps to Execute in the terminal:

1) git clone https://github.com/aniket2098/openebs-Internship.git

2) cd openebs-Internship
   
3) kubectl apply -f pods.yaml

4) kubectl apply -f deployment.yaml
    
5) kubectl apply -f service.yaml

6) sudo docker run -e NAME="any_username" -p 127.0.0.1:80:80 aniket2098/friendlyhello:latest


   In browser type the link on which its running(link provided after execution of step 6).
