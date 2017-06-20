# docker-github-labeller

Automagically create issue labels in your GitHub projects. (`https://github.com/IonicaBizau/github-labeller`)

```
 docker run --rm \
            --interactive \
            --tty \
            -v "$(pwd):$(pwd)" \
            -w $(pwd)
            -it muccg/github-labeller -r <org>/<repo> -t <api-key> -c <labels.json>
```
