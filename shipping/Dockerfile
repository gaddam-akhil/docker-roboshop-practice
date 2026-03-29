FROM maven:3.5 
WORKDIR /app
COPY src /app/src/
COPY pom.xml .
RUN mvn clean package
ENV  CART_ENDPOINT=cart:8080 \
     DB_HOST=mysql     
CMD ["java","-jar","target/shipping-1.0.jar"]  