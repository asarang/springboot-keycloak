# springboot-keycloak


Keycloak needs setting up with the following

Relam name -SpringBootKeycloak

Client name springboot-keycloak-client 

realm roles admin and user

roles app_admin, and app_user

create users

assing realm_role to user

To generate Access Key via Post man run the following

![image](https://user-images.githubusercontent.com/440499/231831577-3d89f64a-f532-43e9-827a-cb0a593a2022.png)

URL = http://localhost:8080/realms/SpringBootKeycloak/protocol/openid-connect/token

In Bdoy element add

grant_type:password

client_id:springboot-keycloak-client

username:<username>

password:<password>


Once key is generated copy it and add it to authorisation token in 

![image](https://user-images.githubusercontent.com/440499/231832226-b83f4e28-22bc-49d8-a6f1-420ec212b08b.png)
