FROM almalinux:latest
RUN yum install nginx -y
# when image creator is running this below command it will not run.
# when some one else tries to use your image then the below command will run
ONBUILD ADD simple.txt /tmp/
