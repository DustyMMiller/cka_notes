## Rolling Updates and Rollbacks

Way to upgrade deployments and rollback if there are issues

### Deployment Strategies
Recreate - destroy all current at once and then put up new
Rolling - Take down one at a time to update - Default

kubectl apply
kubectl set image
kubectl rollout undo deployment/<deployment>

