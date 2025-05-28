# Desafio-3---AWS-

## Objetivo:
El objetivo de este ejercicio es aprender a configurar y utilizar roles de AWS IAM desde
la línea de comandos (CLI) para permitir la escritura en un bucket de S3

## Introducción
El desafío se realizó a través de AWS CLI corriendo en VBox con SO Ubuntu, previamente
creamos una cuenta en AWS para utilizar la capa gratuita siguiendo las recomendaciones de
agregar 2FA, Crear una usuario IAM para no utilizar el usuario raíz y agregar 2FA también para los
usuarios IAM. Luego conectamos AWS CLI con las credenciales para el usuario IAM que creamos
(admin).

## Requisitos:
1. Crear un bucket en s3, recuerda asignar un nombre único.
2. Crear un rol con una política que permita escribir en el bucket cerrado en el paso
anterior.
3. Generar un usuario IAM llamado s3-support y crear una credenciales programáticas.
4. Actualizar la política del rol para que permita al usuario s3-support asumir el rol.
5. Conecta el CLI con las credenciales del usuario s3-support.
6. Asume el rol de válido que puedas escribir en el bucket.

