# madsblog-deploy-terraform-function-app-01

main.tf
- Declaración del provider.

- Si estás configurando un entorno colaborativo con Terraform, te sugiero generar un Remote State File (https://madsblog.net/2023/08/28/remote-terraform-state-file-terraform-tfstate-en-azure-blob-storage/)
- Creación del RG, Storage Account y App Service Plan.
- Creación de Azure Functions: configuración de runtime, versión de runtime y habilitación de Cors para Portal.Azure. Esto último permitirá usar la sección de Test en "Code+Test".


locals.tf
- Aquí definimos las variables utilizadas para los nombres.


variables.tf
- En este apartado declararemos el provider "Random" para los strings numéricos de las variables.