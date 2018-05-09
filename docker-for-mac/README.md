# ingress nginx

https://github.com/kubernetes/ingress-nginx/blob/master/docs/deploy/index.md

## command

**run**


```
$ kubectl apply -f ingress-nginx.yml
```

**status**

```
$ kubectl -n ingress-nginx get all
```

## guid

annotaion prefix = `ingress.kubernetes.io`