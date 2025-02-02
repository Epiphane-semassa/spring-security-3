# Configuration : Spring Security 3 

Ce projet offre une configuration de base pour Spring Security 3, prête à être utilisée dans vos applications Spring. Vous pouvez rapidement intégrer cette configuration pour sécuriser vos API et pages web.

## Configuration

### Port par défaut

Le serveur Tomcat intégré est configuré pour écouter sur le port 8090 par défaut. Vous pouvez modifier le port en modifiant le fichier `application.properties` :

```properties 
server.port=8090
```

### Swagger

Nous avons inclus la configuration Swagger pour vous aider à documenter et à tester vos API plus facilement.

- URL Swagger-UI : http://localhost:8090/swagger-ui/index.html
- URL de la documentation Swagger JSON : http://localhost:8090/v3/api-docs

### Authentification


Par défaut, la configuration inclut une configuration de base pour l'authentification. Vous pouvez personnaliser les utilisateurs en éditant le fichier `application.properties`. Par exemple 

```properties
registerUser.email=votreMail@gmail.com
registerUser.firstName=Nom
registerUser.lastName=Prenom
registerUser.password=mot_de_passe_de_plus_de_8_c
```

### Comment utiliser ce projet

1. Clonez ce référentiel sur votre machine locale en utilisant la commande suivante : ✅
    ```shell
    git clone hgit@github.com:Olakouns/spring-security-3.git
   ```
2. Ouvrez le projet dans votre IDE (IntelliJ, Eclipse, VSCode, etc.) ✅.
3. Personnalisez la configuration de Spring Security selon les besoins de votre application ✅.
4. Exécutez l'application Spring Boot ✅.
5. Accédez à Swagger-UI pour tester vos API et à la documentation Swagger JSON pour plus d'informations sur les endpoints ✅.
6. Vous êtes prêt à commencer à développer votre application sécurisée avec Spring Security 3 ! ✅


#### Pour plus d'informations sur Spring Security, consultez la documentation officielle 🤙 : https://docs.spring.io/spring-security/reference/index.html


### Contributions et problèmes


Si vous rencontrez des problèmes ou souhaitez contribuer à ce projet, veuillez créer une nouvelle ``issue`` ou une ``pull request`` sur GitHub.


#### Nous espérons que cette configuration de base de Spring Security 3 vous sera utile pour sécuriser vos applications. Bon développement 😁 !