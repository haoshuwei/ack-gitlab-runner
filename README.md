# GitLab Runner Helm Chart for ACK

set your values in `values.yaml` file, such as `gitlabUrl` `runnerRegistrationToken` and so on.

helm package:
```
$ helm package .
```

helm install:
```
helm install --namespace gitlab --name gitlab-runner *.tgz
```

more referrence can be found in [ack help document](https://help.aliyun.com/document_detail/106968.html)


