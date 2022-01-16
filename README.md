# Conception et implémentation d’une infrastructure de déploiement continu

•	Installation et déployement de Gitlab en interne comme étant un SCM pour l’équipe de dev.

•	Configuration d’un pipeline automatique à travers Jenkins tel que à chaque évènement de Push de coté dev le projet sera construit et déployé dans un serveur pre-prod pour test et validation.

•	Après l’opération Push, la qualité du code projet sera vérifiée par Sonarqube. En fait, il générera automatiquement un rapport détaillé sur les tests effectués, les bugs, les vulnérabilités et les risques détectés après la compilation. 

•	Aprés chaque build , les artifacts ( docker images , maven build results) seront automatiquement sauvegardés dans des dépôts configurés précédemment dans Nexus.

•	Amélioration continue du pipeline selon les demandes de l’équipe de dev en se référant toujours à la méthode agile.

**Outils : Gitlab , Jenkins , Tomcat , SSH , Token , Ansible , Docker , maven , Sonarqube , Nexus.**
