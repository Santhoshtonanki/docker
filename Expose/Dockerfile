FROM almalinux:9
RUN dnf install -y nginx
CMD ["nginx", "-g", "daemon off;"]
LABEL course="Devops with Docker" \
          learner="santhosh" \
          email="santhoshtonanki1996@gmail.com" \
          author="santhosh" \
          version="1.0" \
          description="This is a sample dockerfile to demonstrate the use of LABEL instruction in dockerfile" \
          license="MIT"
EXPOSE 8080