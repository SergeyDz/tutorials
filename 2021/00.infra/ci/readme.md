# Concorse CI 

## Login to cli tool
```
fly --target example login --team-name my-team --concourse-url http://127.0.0.1:8090

fly -t example set-pipeline -p build-and-push-image -c ./example.pipeline.yml -l vars.yml
```