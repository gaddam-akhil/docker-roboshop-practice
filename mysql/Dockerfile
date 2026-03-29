FROM mysql:8
COPY db /docker-entrypoint-initdb.d/
ENV MYSQL_ROOT_PASSWORD=RoboShop@1 \
    default-authentication-plugin=mysql_native_password