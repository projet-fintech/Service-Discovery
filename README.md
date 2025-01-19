
---

### **Service Discovery (README)**

![image](https://github.com/user-attachments/assets/cf73729f-c7c4-4784-a113-bbfdf76475c3)


```markdown
# Service Discovery

## Description
Ce microservice utilise Eureka pour enregistrer et découvrir dynamiquement tous les autres microservices.

## Fonctionnalités
- Enregistrement des microservices.
- Découverte dynamique des services.

## Dépendances
- Spring Cloud Netflix Eureka

## Lancer le service
```bash
mvn clean install
java -jar target/service-discovery.jar
