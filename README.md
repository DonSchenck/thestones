# thestones frontend
Front end HTML for Rolling Stones album list activity

## Part of the Red Hat Developer learning path entitled "Using Red Hat OpenShift labels"


`oc new-app openshift/nginx:1.20-ubi8~https://github.com/donschenck/thestones --labels=app.kubernetes.io/part-of=thestones,systemname=thestones,tier=frontend,language=html,thestones=frontend`
