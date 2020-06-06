# Overview 

![photosapp](photo.png)
A simple NodeJS application based on Bootstrap UI.

Used as a demo project to  import into Jenkins X

# Import Project

```
jx import

# watch activities
jx get activities --filter photosapp --watch

# check kubernetes resources status
kubectl --namespace jx-staging logs -l app=photosapp
```