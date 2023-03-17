FROM almalinux
ADD https://raw.githubusercontent.com/trussworks/terraform-aws-s3-private-bucket/main/main.tf /tmp/
ADD apache-tomcat-9.0.73-embed.tar.gz /tmp/
WORKDIR /app
ADD foo.txt /app/
ADD bar/ /app/bar/
ENTRYPOINT ["tail", "-f", "/dev/null"]
# ADD [SOURCE] [DESTINATION