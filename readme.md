- 이미지 업로드

```shell
$ curl -F 'image=@testimage.png' http://localhost:6080/api/images/upload
```

```shell
$ curl -F 'image=@testimage.png' http://image-service.sns.svc.cluster.local:8080/api/images/upload
```

- 이미지 조회

```text
http://localhost:6080/api/images/view/d87d46c4-3af3-4424-adb0-49f89a740a0d?thumbnail=true
```
```shell
$ http://image-service.sns.svc.cluster.local:8080/api/images/view/2f6e2a99-d43f-439d-9533-7ff412e2446e?thumbnail=true
```

```shell
$ echo 'alias k=kubectl' >> ~/.zshrc
source ~/.zshrc
```
