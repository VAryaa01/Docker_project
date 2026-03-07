# stable official Java runtime base image, pull a base image gives all required tools and libraries.
FROM eclipse-temurin:17-jdk-alpine



# working directory create a folder where the app code will be stored.
WORKDIR /app


# copy the source code from you host machine to your conatainer.
COPY src/Main.java /app/Main.java

#compile the application code.
RUN javac Main.java

# run the application
CMD ["java" , "Main"]

