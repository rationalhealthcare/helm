```
kubectl create secret docker-registry -n {kube namespace} regcred --docker-server=docker.pkg.github.com --docker-username={github username} --docker-password={github password} --docker-email={github email}
```