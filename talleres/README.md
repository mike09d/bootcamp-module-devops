# Talleres

A lo largo del curso, evolucionaremos la forma de desplegar la aplicación ocupando diferentes servicios de AWS:

1. [Taller 1](./01/README.md): Desplegando Mythical Mysfits en un servidor EC2

2. [Taller 2](./02/README.md): Desplegando la API de Mythical Mysfits usando Auto Scaling Groups

3. [Taller 3](./03/README.md): Desplegando la API usando CloudFormation y Auto Scaling Groups

4. [Taller 4](./04/README.md): Rolling Update de ASG usando CloudFormation

5. [Taller 5](./05/README.md): Blue/Green deployments con CloudFormation y Auto Scaling Groups

6. [Taller 6](./06/README.md): Introducción a CodeBuild

7. [Taller 7](./07/README.md): Introducción a CodePipeline

8. [Taller 8](./08/README.md): Introducción a CodeDeploy

9. [Taller 9](./09/README.md): CI/CD

10. [Taller 10](./10/README.md): VPC Peering

Bootcamp DevOps
Este ejercicio está basado en la aplicación del workshop Mythical Mysfits de AWS.

El objetivo es aprender, de forma incremental, el ciclo de vida de una aplicación así como demostrar los diferentes servicios de AWS que podemos ocupar para desplegar, automatizar y monitorear una aplicación.

Instrucciones
Hacer Fork de este repositorio en tu cuenta de GitHub.

Elige la región de AWS que ocuparás durante el curso: Virginia (us-east-1), Ohio (us-east-2) u Oregon (us-west-2) y crea un Key Pair en la consola de EC2 que lleve por nombre mythical-mysfits.

Después de clonar el repositorio, agrega un remote para mantener tu copia actualizada:

git remote add upstream https://github.com/eloyvega/bootcamp-module-devops.git
Ejecuta los siguientes comandos cada vez que necesites actualizar tu repositorio:

git fetch upstream
git checkout master
git merge upstream/master
git push origin master