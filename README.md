# Chuck App for RH Forum 2019

### Deploy DB
```bash
oc create -f db/
```


### Deploy API
```bash
helm template api  | oc create -f -
```


### Deploy UI
```bash
oc create -f ui/
```
