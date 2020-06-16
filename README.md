# aspnetcore-docker-webapp

## Create Application
```
dotnet new webapp --name aspnetcore-docker-webapp --output ./ --dry-run 
```
Change `localhost` to `0.0.0.0` in file `Properties/launchSettings.json`

## Publish to Docker Hub 
The GitHub Action will automatically publish to Docker Hub
- https://hub.docker.com/r/jibinpb/aspnetcore-docker-webapp
