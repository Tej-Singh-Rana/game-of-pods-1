#### To set the user credentials
```
kubectl config set-credentials martin --client-key=/root/martin.key --client-certificate=/root/martin.crt
```

#### To create a context 'developer' 
```
kubectl config set-context developer --cluster=kubernetes --user=martin
```

#### To set the context
```
kubectl config use-context developer
```
