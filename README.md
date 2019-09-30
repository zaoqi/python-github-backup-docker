# python-github-backup-docker

A Docker image for [https://github.com/josegonzalez/python-github-backup](https://github.com/josegonzalez/python-github-backup)

# Examples

```
docker run -it --rm -v "$(pwd)/output:/output" zaoqi/python-github-backup <user> --token <token> --output-directory /output --repositories
```
