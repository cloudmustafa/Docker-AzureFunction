# Docker-AzureFunction
#Running Azure function on Docker
#Requires Azure Storage Emulator to run locally

#For VS Code:
1. func init . --docker
2. func new
3. docker build -t <IMAGE_NAME> . 
4. docker images
5. docker run -p 8080:80 <IMAGE_NAME>

