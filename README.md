# desktop-java-simple

# Recipe

FROM codenvy/ubuntu_jdk8

# Commands

Command #1

mvn -f ${current.project.path} clean install && java -jar ${current.project.path}/target/*.jar