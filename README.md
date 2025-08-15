# django-birthday20

Static site for the Django birthday website

This is a [Hugo](https://gohugo.io/) project.

Running with Docker
-------------------

In `docker-compose.yml`, we have specified a `serve` target which you can run locally like this:

```bash
docker compose run --rm -u `id -u` --service-ports serve
```

Running without Docker
----------------------

Go to [Hugo Github release](https://github.com/gohugoio/hugo/releases)
and fetch the latest package for **hugo\_extended** for your system.

We want to align with the latest version always. If it doesn't work,
file an issue!

Example recipe for Ubuntu/Debian:

```bash
# Fetch .deb package from GitHub
wget https://github.com/gohugoio/hugo/releases/download/v0.148.2/hugo_extended_0.148.2_linux-amd64.deb -O hugo_extended.deb

# Install package
sudo apt install ./hugo_extended.deb

# Now from inside the cloned copy of this repository, run the Hugo development server:
hugo server
```
