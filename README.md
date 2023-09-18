# database-management
My first commit to a branch
FROM rocker/rstudio
RUN apt-get update && apt-get install -y git wget
