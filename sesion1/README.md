
# Sesión 1: Introducción a AWS y Herramientas Básicas

## Documentación

- [Anexo-AWS_Cloud9.pdf](docs/Anexo-AWS_Cloud9.pdf): Documento sobre AWS Cloud9.
- [Anexo-AWS_CloudShell.pdf](docs/Anexo-AWS_CloudShell.pdf): Documento sobre AWS CloudShell.
- [Clase1-Introduccion.pdf](docs/Clase1-Introduccion.pdf): Introducción a los conceptos básicos de AWS.
- [Practica-Creacion-Sesion-AWS.pdf](docs/Practica-Creacion_Sesion_AWS.pdf): Guía sobre cómo crear y gestionar sesiones en AWS usando boto3.

## Notebooks

- [Creacion-Sesion-AWS.ipynb](notebooks/Creacion_Sesion_AWS.ipynb): Notebook de Jupyter con ejemplos de creación y gestión de sesiones en AWS usando boto3.

## Configuración de Credenciales de AWS

Para ejecutar el código en los notebooks, necesitarás tener configuradas tus credenciales de AWS en tu sistema. Aquí tienes cómo hacerlo:

1. **Instalar AWS CLI**:

   Si no tienes AWS CLI instalado, puedes seguir las instrucciones [aquí](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).

2. **Configurar tus credenciales**:

   Ejecuta el siguiente comando y sigue las instrucciones para introducir tu `AWS Access Key ID` y `AWS Secret Access Key`:

   ```bash
   aws configure
   ```

   Esto creará un archivo de configuración en `~/.aws/credentials` con tus credenciales de AWS.

3. **Verificar configuración**:

   Puedes verificar que tus credenciales están configuradas correctamente ejecutando:

   ```bash
   aws sts get-caller-identity
   ```

   Deberías ver una respuesta que incluya tu `Account` y `Arn`.

## Uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/AWS-Project.git
   cd Apuntes-AWS/session1
   ```

2. Revisar la documentación en la carpeta `/docs`.

3. Configurar tus credenciales de AWS siguiendo las instrucciones en la sección anterior.

4. Abrir y ejecutar los notebooks en la carpeta `/notebooks` usando Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/Creacion-Sesion-AWS.ipynb
   ```

## Contribuir

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para cualquier mejora o corrección.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
