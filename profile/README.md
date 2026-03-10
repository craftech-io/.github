## 🦦 Contribuir al ecosistema:

Valoramos enormemente la retroalimentación de nuestra comunidad y creemos que este espacio colaborativo será fundamental para enriquecer y hacer crecer nuestro proyecto. Sea que hayas detectado un error, tengas una idea brillante o desees proponer una mejora, estamos ansiosos por escuchar lo que tienes para decir.

Te invitamos a ser parte activa de este espacio, donde cada opinión cuenta y cada aporte es apreciado. Juntos, podemos impulsar nuestro proyecto hacia nuevas alturas.

¡Esperamos tus contribuciones y agradecemos tu participación en este emocionante viaje de desarrollo!

## ¿Cómo Contribuir?

Para contribuir a nuestro proyecto, por favor sigue las reglas y pautas establecidas en nuestro archivo [CONTRIBUTING.md](https://github.com/craftech-io/.github/blob/main/CONTRIBUTING.md). Este archivo contiene las instrucciones sobre cómo participar, las reglas para contribuir, y cualquier otra información relevante sobre el proceso de contribución.

¡Gracias por tu interés en contribuir al proyecto! Esperamos ver tus ideas y aportes pronto.

---

# Repositorios de Craftech.io

Bienvenido a la organización **Craftech.io** en GitHub. Este documento proporciona un índice completo de todos nuestros repositorios organizados por categorías.

Aquí encontrarás herramientas, módulos de Terraform, ejemplos de infraestructura, integraciones y mucho más para ayudarte a implementar mejores prácticas en DevOps, infraestructura en la nube y orquestación de contenedores.

## Tabla de Contenidos

- [AWS Lambda y Serverless](#aws-lambda-y-serverless) (5)
- [CI/CD y Acciones de GitHub](#ci-cd-y-acciones-de-github) (6)
- [Herramientas CLI y Automatización](#herramientas-cli-y-automatización) (25)
- [Infraestructura como Código](#infraestructura-como-código) (12)
- [Integraciones de Monitoreo y Alertas](#integraciones-de-monitoreo-y-alertas) (11)
- [Integración con Port.io](#integración-con-port.io) (2)
- [Kubernetes & EKS](#kubernetes--eks) (22)
- [Módulos de Base de Datos](#módulos-de-base-de-datos) (2)
- [Módulos de Infraestructura AWS](#módulos-de-infraestructura-aws) (16)
- [Módulos de Redes](#módulos-de-redes) (2)
- [Módulos de Seguridad e Identidad](#módulos-de-seguridad-e-identidad) (1)
- [Optimización de Costos](#optimización-de-costos) (2)
- [Otros](#otros) (16)
- [Referencias y Ejemplos](#referencias-y-ejemplos) (8)
- [Scripts y Utilidades](#scripts-y-utilidades) (6)
- [Sitios Web y Documentación](#sitios-web-y-documentación) (3)

---

## AWS Lambda y Serverless

- **[aws-budget-alerts](https://github.com/craftech-io/aws-budget-alerts)** - Sin descripción disponible
- **[aws-elastic-beanstalk-nighttime-shutdown](https://github.com/craftech-io/aws-elastic-beanstalk-nighttime-shutdown)** - Sin descripción disponible
- **[module-security-lambda](https://github.com/craftech-io/module-security-lambda)** - Sin descripción disponible
- **[port-actions](https://github.com/craftech-io/port-actions)** - Este repositorio contiene recursos para desplegar un backend sin servidor para port.io para usar en acciones de auto-servicio
- **[slack-aws-cloudwatch-alerts-lambda](https://github.com/craftech-io/slack-aws-cloudwatch-alerts-lambda)** - Sin descripción disponible

## CI/CD y Acciones de GitHub

- **[eks-helm-deploy-action](https://github.com/craftech-io/eks-helm-deploy-action)** - Acción de GitHub para desplegar en clusters de AWS EKS usando helm
- **[eks-helmfile-deploy-action](https://github.com/craftech-io/eks-helmfile-deploy-action)** - Una acción de GitHub para desplegar un gráfico usando helmfile
- **[gitci_templates](https://github.com/craftech-io/gitci_templates)** - Sin descripción disponible
- **[module-ci](https://github.com/craftech-io/module-ci)** - Módulos para automatizar tareas comunes de CI, como instalar dependencias, ejecutar pruebas y publicar versiones
- **[publish-terraform-module-action](https://github.com/craftech-io/publish-terraform-module-action)** - Sin descripción disponible
- **[slack-action](https://github.com/craftech-io/slack-action)** - Notificar el resultado de las Acciones de GitHub a un canal de Slack sobre el estado de los flujos de trabajo

## Herramientas CLI y Automatización

- **[.github](https://github.com/craftech-io/.github)** - Repositorio central de configuración y estándares de GitHub para la organización: workflows, plantillas y políticas compartidas.
- **[alpine-aws-cli](https://github.com/craftech-io/alpine-aws-cli)** - Sin descripción disponible
- **[aws-exams-app](https://github.com/craftech-io/aws-exams-app)** - Sin descripción disponible
- **[bash-scripts](https://github.com/craftech-io/bash-scripts)** - Scripts bash útiles - ¡Que viva BASH!
- **[cloudformation-templates](https://github.com/craftech-io/cloudformation-templates)** - Sin descripción disponible
- **[cloudformation_atlantis](https://github.com/craftech-io/cloudformation_atlantis)** - Sin descripción disponible
- **[craftech](https://github.com/craftech-io/craftech)** - Sin descripción disponible
- **[craftech-cli](https://github.com/craftech-io/craftech-cli)** - Sin descripción disponible
- **[craftech-steampipe](https://github.com/craftech-io/craftech-steampipe)** - Este repositorio centraliza las consultas de Steampipe y la generación de dashboards con Powerpipe, todo dockerizado para un entorno de desarrollo con...
- **[docs](https://github.com/craftech-io/docs)** - Documentación de Craftech
- **[fork-dockertron](https://github.com/craftech-io/fork-dockertron)** - Es un repositorio forkeado de Sleakops, la idea es que pase a ser una lib desde sleakops para integrar a la cli. Cuando eso pase este repositorio se e...
- **[hubspot-reports-automation](https://github.com/craftech-io/hubspot-reports-automation)** - Repositorio con script que automatiza la creación de reportes con datos de HubSpot
- **[infrastructure-live-generator](https://github.com/craftech-io/infrastructure-live-generator)** - Resources for an automated generation of infrastructure live repositories
- **[mcp_cli](https://github.com/craftech-io/mcp_cli)** - Este repositorio contiene una herramienta de línea de comandos (CLI) que actúa como un agente de DevOps inteligente. Utiliza el Model Context Protocol...
- **[module-installer](https://github.com/craftech-io/module-installer)** - Un script para facilitar la instalación de módulos de script
- **[MSP](https://github.com/craftech-io/MSP)** - Sin descripción disponible
- **[n8n-craftech](https://github.com/craftech-io/n8n-craftech)** - Infraestructura base para el despliegue de n8n en AWS utilizando VPC, ALB, EC2 y RDS PostgreSQL.
- **[pipeline-generator](https://github.com/craftech-io/pipeline-generator)** - Python CLI que genera CI/CD para repositorios de infraestructura en vivo
- **[port-aws-auto-tag](https://github.com/craftech-io/port-aws-auto-tag)** - Scripts made it in Python for AWS resource tagging usin OpenAI API
- **[port-io-manager](https://github.com/craftech-io/port-io-manager)** - Port.io Manager IaC
- **[pre-commit](https://github.com/craftech-io/pre-commit)** - Una colección de hooks de pre-commit utilizados por Craftech
- **[python-scripts](https://github.com/craftech-io/python-scripts)** - Repositorio para scripts de Python
- **[registry](https://github.com/craftech-io/registry)** - Este es el registro privado de Craftech
- **[terragrunt-dependencies-updater](https://github.com/craftech-io/terragrunt-dependencies-updater)** - Sin descripción disponible
- **[terragrunt-deployer](https://github.com/craftech-io/terragrunt-deployer)** - Un script de Python para desplegar con Terragrunt

## Infraestructura como Código

- **[cloudpiles-sidom-infra-live](https://github.com/craftech-io/cloudpiles-sidom-infra-live)** - Repo para levnatar la PoC de Sidom / Cloudpiles
- **[craftech-infrastructure-live](https://github.com/craftech-io/craftech-infrastructure-live)** - Sin descripción disponible
- **[infrastructure-live-intelligential](https://github.com/craftech-io/infrastructure-live-intelligential)** - Live repository for intelligential
- **[intro-to-terratest](https://github.com/craftech-io/intro-to-terratest)** - Sin descripción disponible
- **[module-data-storage](https://github.com/craftech-io/module-data-storage)** - Módulos Terraform para configurar mejores prácticas para depósitos S3, EBS, EFS y más servicios de almacenamiento.
- **[module-ec2-server](https://github.com/craftech-io/module-ec2-server)** - Este repositorio contiene los recursos esenciales para administrar servidores EC2, con grupos de seguridad y datos de usuario
- **[module-iam](https://github.com/craftech-io/module-iam)** - Código Terraform y scripts para crear recursos de IAM.
- **[module-messaging](https://github.com/craftech-io/module-messaging)** - Repositorio para servicios de mensajería (SNS, SQS, Kinesis)
- **[module-port](https://github.com/craftech-io/module-port)** - Módulos Terraform para desplegar modelos de puerto y exportadores
- **[package-gitlab](https://github.com/craftech-io/package-gitlab)** - Un módulo de Craftech para desplegar Gitlab Community
- **[port-idp-klap](https://github.com/craftech-io/port-idp-klap)** - Resources for Port IDP - Klap
- **[terraform-aws-backup](https://github.com/craftech-io/terraform-aws-backup)** - Sin descripción disponible

## Integraciones de Monitoreo y Alertas

- **[alerthub](https://github.com/craftech-io/alerthub)** - Alerthub es un servicio escrito en Go que recibe los webhooks de alerta generados por Grafana Alerting, los normaliza y los almacena en una base de da...
- **[aws-health-slack-notifier](https://github.com/craftech-io/aws-health-slack-notifier)** - Hub central de monitoreo de eventos de AWS Health en múltiples regiones. Centraliza notificaciones en Slack mediante Amazon Q Developer (Chat...
- **[discord-amazon-budget-alerts](https://github.com/craftech-io/discord-amazon-budget-alerts)** - Una solución sin servidor usando AWS SAM para crear presupuestos de AWS con auto-ajuste y enviar alertas de costos a un canal de Discord.
- **[discord-amazon-cost-anomaly-alerts](https://github.com/craftech-io/discord-amazon-cost-anomaly-alerts)** - Una solución sin servidor para enviar alertas de detección de anomalías de costos de AWS a un canal de Discord usando AWS Lambda y SAM.
- **[discord-amazon-devops-guru-alerts-lambda](https://github.com/craftech-io/discord-amazon-devops-guru-alerts-lambda)** - Función AWS Lambda para enviar notificaciones de Discord desde Amazon DevOps Guru
- **[discord-amazon-guardduty-alerts-lambda](https://github.com/craftech-io/discord-amazon-guardduty-alerts-lambda)** - Sin descripción disponible
- **[discord-aws-cloudwatch-alerts-lambda](https://github.com/craftech-io/discord-aws-cloudwatch-alerts-lambda)** - Función Lambda de Python para alertas de AWS
- **[discord-grafana-alerts-lambda](https://github.com/craftech-io/discord-grafana-alerts-lambda)** - Función AWS Lambda para enviar notificaciones de Discord desde Grafana
- **[module-alarms](https://github.com/craftech-io/module-alarms)** - Sin descripción disponible
- **[module-grafana-alerting](https://github.com/craftech-io/module-grafana-alerting)** - Un repositorio para módulos de Terraform de alertas de Grafana
- **[module-monitoring](https://github.com/craftech-io/module-monitoring)** - Código Terraform y scripts para desplegar herramientas de observabilidad

## Integración con Port.io

- **[port-actions-catalog](https://github.com/craftech-io/port-actions-catalog)** - Catálogo de acciones definidas para Port
- **[port-actions-module](https://github.com/craftech-io/port-actions-module)** - Módulo base para acciones de Port

## Kubernetes & EKS

- **[argo-rollouts-meetup](https://github.com/craftech-io/argo-rollouts-meetup)** - Repositorio con la configuración y archivos necesarios para desarrollar la demo para la meetup de ArgoCD+ArgoRollouts+ArgoNotifications
- **[argocd-diff-preview](https://github.com/craftech-io/argocd-diff-preview)** - Guía de implementación de ArgoCD Diff Preview | Automatice el análisis del impacto de la infraestructura inyectando diffs de aplicaciones de ArgoCD ...
- **[argocd-gitops-demo](https://github.com/craftech-io/argocd-gitops-demo)** - Sin descripción disponible
- **[argocd-repository-templates](https://github.com/craftech-io/argocd-repository-templates)** - Sin descripción disponible
- **[ci-tools](https://github.com/craftech-io/ci-tools)** - Repositorio para imagen de docker con terraform/terragrunt y terraform/terratest.
- **[demo-eks-scaling-with-keda-and-karpenter](https://github.com/craftech-io/demo-eks-scaling-with-keda-and-karpenter)** - Aplicación de escalado de muestra con KEDA y Karpenter en Amazon EKS utilizando nodos de Fargate y Terraform
- **[eks-addons](https://github.com/craftech-io/eks-addons)** - Este repositorio contiene una colección de módulos Terraform diseñados para simplificar la instalación y administración de complementos en clusters de Amazon EKS
- **[eks-cron-shutdown](https://github.com/craftech-io/eks-cron-shutdown)** - Aplicación en Python para el apagado y encendido programado de clusters EKS (autoscaling groups y fargate) para reducción de costos.
- **[eks-management](https://github.com/craftech-io/eks-management)** - Este repositorio proporciona una colección de módulos Terraform y configuraciones para desplegar herramientas de administración en clusters de Amazon EKS.
- **[eks-nightly-shutdown-lambda](https://github.com/craftech-io/eks-nightly-shutdown-lambda)** - Una función AWS Lambda sin servidor que apaga automáticamente tu cluster de Amazon EKS fuera de las horas para reducir costos
- **[helm-charts](https://github.com/craftech-io/helm-charts)** - Gráficos Helm de Craftech
- **[helm-charts-reference](https://github.com/craftech-io/helm-charts-reference)** - Sin descripción disponible
- **[k6](https://github.com/craftech-io/k6)** - Despliegue de k6 para K8s
- **[kubernetes-application](https://github.com/craftech-io/kubernetes-application)** - Gráfico Helm de aplicación kube
- **[kubernetes-env-to-secrets](https://github.com/craftech-io/kubernetes-env-to-secrets)** - Convertir archivos de entorno a secretos de Kubernetes
- **[minikube-cluster](https://github.com/craftech-io/minikube-cluster)** - Cluster de Minikube con servicios principales de K8s
- **[module-eks](https://github.com/craftech-io/module-eks)** - Código Terraform y scripts para desplegar un cluster de Amazon Elastic Kubernetes Service (EKS).
- **[module-eks-automode](https://github.com/craftech-io/module-eks-automode)** - Este repositorio contiene los recursos esenciales para administrar el plano de control de un cluster de Amazon Elastic Kubernetes Service (EKS). Tambi...
- **[shutdown-modules](https://github.com/craftech-io/shutdown-modules)** - Este repositorio contiene módulos Terraform diseñados para automatizar el apagado e inicio de recursos de AWS, ayudando a optimizar costos
- **[terraform-kubernetes-application](https://github.com/craftech-io/terraform-kubernetes-application)** - Sin descripción disponible
- **[vault-crd](https://github.com/craftech-io/vault-crd)** - Vault CRD para compartir secretos de Vault con Kubernetes
- **[workshop-opentelemetry](https://github.com/craftech-io/workshop-opentelemetry)** - Sin descripción disponible

## Módulos de Base de Datos

- **[module-databases](https://github.com/craftech-io/module-databases)** - Código Terraform y scripts para desplegar recursos de bases de datos relacionales (por ejemplo: MySQL, PostgreSQL, Redshift) en AWS
- **[module-dms](https://github.com/craftech-io/module-dms)** - Sin descripción disponible

## Módulos de Infraestructura AWS

- **[module-api-gateway](https://github.com/craftech-io/module-api-gateway)** - Código Terraform y scripts para desplegar AWS API Gateway
- **[module-athena](https://github.com/craftech-io/module-athena)** - Módulos de Terraform para la configuración y gestión de AWS Athena (bases de datos, grupos de trabajo y catálogos).
- **[module-beanstalk](https://github.com/craftech-io/module-beanstalk)** - Un módulo Terraform elástico de Beanstalk para desplegar Elastic Beanstalk | AWS
- **[module-cloudfront](https://github.com/craftech-io/module-cloudfront)** - Código Terraform y scripts para desplegar una distribución de Amazon CloudFront (CDN)
- **[module-ecr](https://github.com/craftech-io/module-ecr)** - Este módulo Terraform se utiliza para crear ECR en AWS
- **[module-identity-center](https://github.com/craftech-io/module-identity-center)** - Un módulo Terraform que le permite administrar toda una estructura de Identity Center en AWS
- **[module-kafka](https://github.com/craftech-io/module-kafka)** - Código Terraform y scripts para desplegar un cluster de Amazon Managed Streaming for Apache Kafka (MSK).
- **[module-kvs](https://github.com/craftech-io/module-kvs)** - Código Terraform y scripts para desplegar clusters de almacén de clave-valor (por ejemplo: redis o memcached) usando Amazon ElastiCache
- **[module-load-balancer](https://github.com/craftech-io/module-load-balancer)** - Código Terraform y scripts para desplegar Load Balancers en AWS
- **[module-migration](https://github.com/craftech-io/module-migration)** - Sin descripción disponible
- **[module-organizations](https://github.com/craftech-io/module-organizations)** - Sin descripción disponible
- **[modules-azure](https://github.com/craftech-io/modules-azure)** - Paquetes para crear una configuración de redes virtuales (VNet) de mejores prácticas en Azure y tareas relacionadas con redes, como proxies
- **[terraform-aws-acm](https://github.com/craftech-io/terraform-aws-acm)** - Módulo Terraform que crea y valida certificados ACM
- **[terraform-aws-ecr](https://github.com/craftech-io/terraform-aws-ecr)** - Módulo Terraform que crea un AWS Elastic Container Registry
- **[terraform-aws-lambda](https://github.com/craftech-io/terraform-aws-lambda)** - Módulos para desplegar y administrar funciones AWS Lambda
- **[terraform-aws-service-catalog](https://github.com/craftech-io/terraform-aws-service-catalog)** - Catálogo de servicios para AWS

## Módulos de Redes

- **[module-networking](https://github.com/craftech-io/module-networking)** - Paquetes para crear una configuración de Virtual Private Cloud (VPC) de mejores prácticas en AWS y tareas relacionadas con redes, como proxies.
- **[terraform-aws-route53](https://github.com/craftech-io/terraform-aws-route53)** - Módulo Terraform que crea recursos de Route53 en AWS

## Módulos de Seguridad e Identidad

- **[module-glue](https://github.com/craftech-io/module-glue)** - Sin descripción disponible

## Optimización de Costos

- **[aws-nuke](https://github.com/craftech-io/aws-nuke)** - Sin descripción disponible
- **[aws-nuke-account-cleanser-example](https://github.com/craftech-io/aws-nuke-account-cleanser-example)** - Sin descripción disponible

## Otros

- **[atlantis](https://github.com/craftech-io/atlantis)** - Archivos y configuraciones de Atlantis
- **[aws-partner-hubspot-connector](https://github.com/craftech-io/aws-partner-hubspot-connector)** - Sin descripción disponible
- **[chartmuseum-auth-server](https://github.com/craftech-io/chartmuseum-auth-server)** - Servidor de aplicaciones que proporciona tokens JWT para autenticación de ChartMuseum
- **[clients](https://github.com/craftech-io/clients)** - Este repositorio se utilizará para almacenar recursos de clientes arbitrarios que aún no están listos para compartir
- **[docker-templates](https://github.com/craftech-io/docker-templates)** - Este repositorio contiene plantillas para aplicaciones que fueron dockerizadas. Si es posible, incluya también un docker-compose
- **[fast-tech-talks](https://github.com/craftech-io/fast-tech-talks)** - Sin descripción disponible
- **[fifa](https://github.com/craftech-io/fifa)** - Sin descripción disponible
- **[keda-examples](https://github.com/craftech-io/keda-examples)** - Repositorio para almacenar ejemplos de Keda
- **[labs](https://github.com/craftech-io/labs)** - Repositorio central de utilidades, experimentos y desarrollos complementarios con valor reutilizable para la organización.
- **[module-ecs](https://github.com/craftech-io/module-ecs)** - Este repositorio contiene los recursos esenciales para administrar clusters de ECS, tareas, servicios y otros.
- **[package-vault](https://github.com/craftech-io/package-vault)** - Un módulo de Craftech para desplegar Hashicorp Vault
- **[port-craftech](https://github.com/craftech-io/port-craftech)** - Integraciones y configuraciones para Getport.io específicas de Craftech.
- **[tekton-ftt](https://github.com/craftech-io/tekton-ftt)** - Repositorio creado para propósitos de FTT
- **[terralist](https://github.com/craftech-io/terralist)** - Administre sus módulos y proveedores con una API REST
- **[verdaccio](https://github.com/craftech-io/verdaccio)** - Repositorio para imágenes de Docker de Verdaccio
- **[wafr-custom-lenses](https://github.com/craftech-io/wafr-custom-lenses)** - Sin descripción disponible

## Referencias y Ejemplos

- **[crossplane-demo](https://github.com/craftech-io/crossplane-demo)** - Sin descripción disponible
- **[gcp-infrastructure-live-reference](https://github.com/craftech-io/gcp-infrastructure-live-reference)** - Sin descripción disponible
- **[infrastructure-live-reference](https://github.com/craftech-io/infrastructure-live-reference)** - Repositorio de infraestructura en vivo de ejemplo para referencia
- **[infrastructure-module-reference](https://github.com/craftech-io/infrastructure-module-reference)** - Repositorio de módulos de infraestructura de ejemplo
- **[infrastructure-module-reference-security](https://github.com/craftech-io/infrastructure-module-reference-security)** - Sin descripción disponible
- **[infrastructure-multi-account-reference](https://github.com/craftech-io/infrastructure-multi-account-reference)** - Repositorio de infraestructura en vivo de ejemplo
- **[local-environment-reference](https://github.com/craftech-io/local-environment-reference)** - Un repositorio de referencia para crear la configuración del entorno local usando Kind y Skaffold
- **[terraform-template](https://github.com/craftech-io/terraform-template)** - Este repositorio contiene la plantilla para crear módulos Terraform mantenidos por Craftech

## Scripts y Utilidades

- **[assessment-scripts](https://github.com/craftech-io/assessment-scripts)** - Repositorio para evaluaciones e inventario de infraestructura
- **[aws-ecr-http-proxy](https://github.com/craftech-io/aws-ecr-http-proxy)** - Un proxy de paso a través basado en nginx para AWS ECR con soporte de caché y actualización de token
- **[backstage](https://github.com/craftech-io/backstage)** - Backstage es una plataforma abierta para crear portales de desarrolladores
- **[module-security](https://github.com/craftech-io/module-security)** - Código Terraform y scripts para configurar mejores prácticas para administrar secretos, credenciales y servidores
- **[package-pritunl](https://github.com/craftech-io/package-pritunl)** - Un módulo de Craftech para desplegar Pritunl VPN (basado en OpenVPN)
- **[pipelines-reference](https://github.com/craftech-io/pipelines-reference)** - Un repositorio con ejemplo de configuración de pipeline para diferentes proveedores de CI/CD

## Sitios Web y Documentación

- **[blog](https://github.com/craftech-io/blog)** - Blog de Craftech
- **[craftech.io](https://github.com/craftech-io/craftech.io)** - El sitio web de craftech.io
- **[docusaurus](https://github.com/craftech-io/docusaurus)** - Sin descripción disponible

---

**Total de repositorios:** 139
