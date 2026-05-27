FROM almalinux:9
RUN dnf install -y nginx  
LABEL course="Devops with Docker" \
          learner="santhosh" \
          email="santhoshtonanki1996@gmail.com" \
          author="santhosh" \
          version="1.0" \
          description="This is a sample dockerfile to demonstrate the use of LABEL instruction in dockerfile" \
          url="https://www.joindevops.com" \
          license="MIT"
RUN rm -rf /usr/share/nginx/html/*
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]