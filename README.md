

## Create pipeline resources

```bash
sudo kubectl apply -f task-go-build.yaml
sudo kubectl apply -f task-git-push.yaml
sudo kubectl apply -f pipeline-hello-world.yaml
```

## Start pipeline

```bash
sudo kubectl apply -f pipelinerun-hello-world.yaml
```