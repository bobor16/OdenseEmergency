FROM ubuntu:20.04
# install curl
RUN apt-get update && apt-get install -y curl

# Run the curl command
RUN curl -H "Content-Type: application/json" -X GET https://backend-lyh2tel4na-ew.a.run.app/health

