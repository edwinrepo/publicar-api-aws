# ¿Cómo publicar una API desde api-gateway en aws

Tomado de: https://www.youtube.com/watch?v=V-ac_ZvdAW4

Para publicarlo se debe crear una api:

REST API
Develop a REST API where you gain complete control over the request and response along with API management capabilities.
Works with the following:
Lambda, HTTP, AWS Services

1) Se crea el recurso

![image](https://user-images.githubusercontent.com/70587582/225984069-3bf3bbf9-aa2c-48d7-86f5-2e4c72cb4ecf.png)

2) Se edita la configuración para invocar la función

![image](https://user-images.githubusercontent.com/70587582/225984303-25b91aac-71bc-410a-829c-50492c344cda.png)
![image](https://user-images.githubusercontent.com/70587582/225984433-bea64f6a-044e-4498-b8fc-bf6552974079.png)
![image](https://user-images.githubusercontent.com/70587582/225984527-d73d1e9c-5238-496c-96e4-24c2709e1ed6.png)

Se crea el plan
![image](https://user-images.githubusercontent.com/70587582/225984934-d2315d03-0bc2-4bb9-b8d6-6f3da50e78ea.png)

Se adiciona ese plan a la API
![image](https://user-images.githubusercontent.com/70587582/225987592-0f86c808-5441-4daf-b5e1-3bafcbc7779f.png)


2) Se crea el usuario y se adiciona a algún plan

![image](https://user-images.githubusercontent.com/70587582/225986230-91cdce86-12c3-4fe3-8315-fec39d32dc58.png)
![image](https://user-images.githubusercontent.com/70587582/225986464-14c0fb4b-c929-4936-aae8-18dc7c4c11de.png)



