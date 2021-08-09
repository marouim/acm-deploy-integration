# Deploiement applicatif et integrations avec ACM

### Déploiement 

Pour déployer les ressources de demo integrations, il suffit d'appliquer les fichiers subscription et channel sur un cluster ayant Advanced Cluster Management d'installé. 

``` 
oc apply -f subscription.yaml
oc apply -f channel.yaml
```

Appliquer ensuite le label integrations=yes sur le ou les clusters souhaités. 

### Demo script

#### 1 - Tour de roue de l'interface ACM 
- Overview
- Search
- Grafana dashboard

#### 2 - Installation de l'opérateur Camel-K dans plusieurs clusters
- Appliquer le label integrations sur les clusters A,B et C

#### 3 - Déployer une ressource Springboot Camel via ACM


 