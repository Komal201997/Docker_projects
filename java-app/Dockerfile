#Getting base iamge
From openjdk:11

#working directory where all code will be kept
WORKDIR app/

#copy the app to the current directory
COPY Hello.java .

#compile  code
RUN javac Hello.java

#run java compiled code 
CMD ["java","Hello"]

