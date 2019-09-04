# gcloud commands

### Project Commands:
Get Project List
```
gcloud projects list
```

See your current Project
```
gcloud config list
```

Set Project
```
gcloud config set project project-name
```

Check all regions
```
gcloud compute regions list
```

Set region
```
gcloud config set compute/region asia-south1
```

Set zone
```
gcloud config set compute/zone asia-south1-a
```
---
### VM Commands:
List of all VM instances
```
gcloud compute instances list
```

For SSH
```
gcloud compute ssh instance-name
```
