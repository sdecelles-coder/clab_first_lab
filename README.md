## Download des images requis pour ce lab

### Nokia
C'est la manière la plus simple de préparer un lab.

To download the [ghcr.io/nokia/srlinux:24.10](http://ghcr.io/nokia/srlinux:24.10) container image, use the docker pull command. This command retrieves the specified image from the GitHub Container Registry (GHCR) and stores it locally on your system, provided you have Docker installed and running.

À partir du répertoire où se trouve le fichier yaml  ( /root/clab_first_lab )

```
docker pull ghcr.io/nokia/srlinux:24.10
```

After executing this command, you can verify that the image has been successfully downloaded by listing your local Docker images:

```
docker images
```

This will display a list of all Docker images available on your system

Ceci est une modif
