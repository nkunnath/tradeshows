## NKP cluster prep for tradeshows

### Enable platform apps
`kubectl apply -f platform-apps/`


### Create a Project and deploy the boutique app
1. `kubectl apply -f tradeshows/project/project.yaml`

2. `kubectl apply -f tradeshows/project/gitopsrepository.yaml`


### Create an edge workspace and two NKP clusters in it

1. Update the values in .env
source tradeshows/workspace/.env

2. Create clusters from create_cluster.yml
