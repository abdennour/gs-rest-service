FROM maven:3.8.1-openjdk-8-slim as build
COPY . .
RUN mvn package
# target/*.jar


# FROM base-runtime  as runtime
# COPY --from=build /code/artifact /path
# ENTRYPOINT /path/app