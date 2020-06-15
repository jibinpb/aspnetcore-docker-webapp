# aspnetcore-docker-webapp

## Create Application
```
dotnet new webapp --name aspnetcore-docker-webapp --output ./ --dry-run 
```
Change `localhost` to `0.0.0.0`

wget https://download.docker.com/linux/debian/dists/stretch/pool/stable/amd64/docker-ce_19.03.9~3-0~debian-stretch_amd64.deb
sudo dpkg -i docker-ce_19.03.9~3-0~debian-stretch_amd64.deb


wget https://www.openssl.org/source/openssl-1.1.1g.tar.gz