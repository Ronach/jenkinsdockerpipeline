Pipeline d'intégration et de déploiement continu (CI/CD:Continuous Integration/Continuous Deployment) pour une application Java.
Le script du pipeline fait appel à Maven pour build lors du premier stage (création du .jar) puis qui build une image docker lors du second et enfin qui push cette image sur Docker Hub.
