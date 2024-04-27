#Get the base Image 

FROM openjdk:8

#Working Directory to keep the files
WORKDIR  /app

#Copy code from HelloWorld.java to app for running inside the conatainer
COPY  HelloWorld.java /app

#Compile the code
RUN javac HelloWorld.java

# App is now ready to run
CMD ["java","HelloWorld"]
