# k8s-sync-chart

k8s-sync is a kubernetes cronjob that runs periodically and downloads a list of every user that can use kubernetes and sets up their account.

k8s-sync creates DSMLP User Resources

- Pod security policy
- User pv/pvcs
- Home directory

https://ucsdcollab.atlassian.net/wiki/spaces/ETS/pages/49781900/k8s-sync
