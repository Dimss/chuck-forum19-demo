# Chuck App for RH Forum 2019

### Deploy DB
oc create -f db/

### Deploy API
helm template api  | oc create -f -

### Deploy UI
oc create -f ui/