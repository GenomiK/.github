

**Genomi-k**
=============
![](https://admin-genomik-ng-assets.s3.amazonaws.com/images/github_cover.png)


## Proceso de desarrollo en el Backend

```mermaid
graph LR
A[Genera funcion lambda] --> B(Prueba en Postman)
B --> C(Sube cambios a github)
C --> D(Despliega en AWS)
D --> E(Implementa el Endpoint en el Front)
