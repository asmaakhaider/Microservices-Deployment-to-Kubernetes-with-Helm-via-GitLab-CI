# Déploiement de microservices sur Kubernetes avec Helm via GitLab CI

## Étape 1 : Créer et Configurer de Gitlab CI

### La capture d'écran montre les différents répertoires du code source 
![Description de l'image]![alt text](<Screenshot from 2024-09-24 13-06-08.png>)
### des images essentielles pour le déploiement et le fonctionnement de l'application via Kubernetes et Helm
 ![alt text](<Screenshot from 2024-09-24 13-04-43.png>)

### Variables `DOCKER_PASSWORD`, `DOCKER_USERNAME` `KUBE_CONFIG`, utilisées pour l'authentification et la configuration de votre pipeline .
![alt text](<Screenshot from 2024-09-24 12-39-40.png>)

### la capture d'ecran montre cluster Kubernetes est `k3s-cluster`
![alt text](<Screenshot from 2024-09-24 12-40-36.png>)
### Le fichier de configuration de l'agent se trouve dans le répertoire `.gitlab/agents/k3s-cluster/config.yaml`
![alt text](<Screenshot from 2024-09-24 15-47-22.png>)

## Étape 2 : Lancer notre pipeline

### Enfin, exécutons notre pipeline une fois de plus et après un certain temps, en  obtiendrer le résultat suivant :
![alt text](<Screenshot from 2024-09-24 12-42-18.png>)
## Super, tout s'est bien passé, vérifions notre cluster Kuberntes et notre application si tout fonctionne comme prévu.
![alt text](<Screenshot from 2024-09-24 16-03-29.png>)
![alt text](<Screenshot from 2024-09-24 12-49-03.png>)
![alt text](<Screenshot from 2024-09-24 12-49-59.png>)
![alt text](<Screenshot from 2024-09-24 12-44-04.png>)
![alt text](<Screenshot from 2024-09-24 12-56-55.png>)
![alt text](<Screenshot from 2024-09-24 12-56-55.png>)
![alt text](<Screenshot from 2024-09-24 12-57-21.png>)
![alt text](<Screenshot from 2024-09-24 12-57-48.png>)



