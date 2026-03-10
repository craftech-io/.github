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

- [AWS Lambda y Serverless](#aws-lambda-y-serverless) (4)
- [CI/CD y Acciones de GitHub](#ci-cd-y-acciones-de-github) (6)
- [Herramientas CLI y Automatización](#herramientas-cli-y-automatización) (23)
- [Infraestructura como Código](#infraestructura-como-código) (10)
- [Integraciones de Monitoreo y Alertas](#integraciones-de-monitoreo-y-alertas) (11)
- [Integración con Port.io](#integración-con-port.io) (8)
- [Kubernetes & EKS](#kubernetes--eks) (22)
- [Módulos de Base de Datos](#módulos-de-base-de-datos) (2)
- [Módulos de Infraestructura AWS](#módulos-de-infraestructura-aws) (16)
- [Módulos de Redes](#módulos-de-redes) (2)
- [Módulos de Seguridad e Identidad](#módulos-de-seguridad-e-identidad) (1)
- [Optimización de Costos](#optimización-de-costos) (2)
- [Otros](#otros) (15)
- [Referencias y Ejemplos](#referencias-y-ejemplos) (8)
- [Scripts y Utilidades](#scripts-y-utilidades) (6)
- [Sitios Web y Documentación](#sitios-web-y-documentación) (3)

---

## AWS Lambda y Serverless

- **[aws-budget-alerts](https://github.com/craftech-io/aws-budget-alerts)** - Solución serverless para presupuestos AWS
- **[aws-elastic-beanstalk-nighttime-shutdown](https://github.com/craftech-io/aws-elastic-beanstalk-nighttime-shutdown)** - Apagado programado de Elastic Beanstalk
- **[module-security-lambda](https://github.com/craftech-io/module-security-lambda)** - Funciones Lambda de seguridad
- **[slack-aws-cloudwatch-alerts-lambda](https://github.com/craftech-io/slack-aws-cloudwatch-alerts-lambda)** - Alertas de CloudWatch a Slack

## CI/CD y Acciones de GitHub

- (¿Qué es esto?) **[eks-helm-deploy-action](https://github.com/craftech-io/eks-helm-deploy-action)** - Despliegue EKS con Helm
- (¿Qué es esto?) **[eks-helmfile-deploy-action](https://github.com/craftech-io/eks-helmfile-deploy-action)** - Despliegue con Helmfile
- **[gitci_templates](https://github.com/craftech-io/gitci_templates)** - Plantillas GitLab CI/CD
- **[module-ci](https://github.com/craftech-io/module-ci)** - Automatización CI
- **[publish-terraform-module-action](https://github.com/craftech-io/publish-terraform-module-action)** - Publicador módulos Terraform
- (¿Qué es esto?) **[slack-action](https://github.com/craftech-io/slack-action)** - Notificaciones Slack

## Herramientas CLI y Automatización

- **[.github](https://github.com/craftech-io/.github)** - Config. central GitHub
- (¿Qué es esto?) **[alpine-aws-cli](https://github.com/craftech-io/alpine-aws-cli)** - Imagen Docker Alpine con AWS CLI
- **[aws-exams-app](https://github.com/craftech-io/aws-exams-app)** - Aplicación de exámenes AWS
- **[bash-scripts](https://github.com/craftech-io/bash-scripts)** - Scripts bash útiles - ¡Que viva BASH!
- **[cloudformation-templates](https://github.com/craftech-io/cloudformation-templates)** - Templates CloudFormation (IAM, presupuestos)
- **[cloudformation_atlantis](https://github.com/craftech-io/cloudformation_atlantis)** - Templates CloudFormation para Atlantis
- **[craftech](https://github.com/craftech-io/craftech)** - Centro de sugerencias e issues
- **[craftech-cli](https://github.com/craftech-io/craftech-cli)** - CLI interna para automatización
- **[craftech-steampipe](https://github.com/craftech-io/craftech-steampipe)** - Steampipe y dashboards Powerpipe
- **[docs](https://github.com/craftech-io/docs)** - Documentación de Craftech
- **[fork-dockertron](https://github.com/craftech-io/fork-dockertron)** - Fork de Sleakops para CLI
- **[hubspot-reports-automation](https://github.com/craftech-io/hubspot-reports-automation)** - Automatización HubSpot
- **[infrastructure-live-generator](https://github.com/craftech-io/infrastructure-live-generator)** - Generador repos infraestructura
- **[mcp_cli](https://github.com/craftech-io/mcp_cli)** - CLI DevOps inteligente con MCP
- **[module-installer](https://github.com/craftech-io/module-installer)** - Script instalador módulos
- **[MSP](https://github.com/craftech-io/MSP)** - Monorepo de herramientas MSP
- **[n8n-craftech](https://github.com/craftech-io/n8n-craftech)** - Infraestructura n8n AWS
- (¿Qué es esto?) **[pipeline-generator](https://github.com/craftech-io/pipeline-generator)** - Generador pipelines CI/CD
- **[pre-commit](https://github.com/craftech-io/pre-commit)** - Hooks pre-commit Craftech
- (Combinar con el de BASH SCRIPTS)  **[python-scripts](https://github.com/craftech-io/python-scripts)** - Colección scripts Python
- **[registry](https://github.com/craftech-io/registry)** - Registro privado Craftech
- **[terragrunt-dependencies-updater](https://github.com/craftech-io/terragrunt-dependencies-updater)** - CLI para actualizar módulos
- **[terragrunt-deployer](https://github.com/craftech-io/terragrunt-deployer)** - Deployer Terragrunt

## Infraestructura como Código

- (¿Qué es esto?)  **[cloudpiles-sidom-infra-live](https://github.com/craftech-io/cloudpiles-sidom-infra-live)** - PoC Sidom/Cloudpiles
- **[craftech-infrastructure-live](https://github.com/craftech-io/craftech-infrastructure-live)** - Infraestructura live Terragrunt
- (¿Qué es esto?) **[infrastructure-live-intelligential](https://github.com/craftech-io/infrastructure-live-intelligential)** - Infraestructura live Intelligential
- **[intro-to-terratest](https://github.com/craftech-io/intro-to-terratest)** - Ejemplos Terratest
- **[module-data-storage](https://github.com/craftech-io/module-data-storage)** - Módulos almacenamiento
- **[module-ec2-server](https://github.com/craftech-io/module-ec2-server)** - Módulos EC2
- **[module-iam](https://github.com/craftech-io/module-iam)** - Módulos IAM
- **[module-messaging](https://github.com/craftech-io/module-messaging)** - Módulos SNS/SQS/Kinesis
- **[package-gitlab](https://github.com/craftech-io/package-gitlab)** - Módulo GitLab Community
- **[terraform-aws-backup](https://github.com/craftech-io/terraform-aws-backup)** - Módulos de respaldos AWS

## Integraciones de Monitoreo y Alertas

- **[alerthub](https://github.com/craftech-io/alerthub)** - Normalizador de webhooks Grafana
- **[aws-health-slack-notifier](https://github.com/craftech-io/aws-health-slack-notifier)** - Monitor AWS Health a Slack
- **[discord-amazon-budget-alerts](https://github.com/craftech-io/discord-amazon-budget-alerts)** - Presupuestos AWS a Discord
- **[discord-amazon-cost-anomaly-alerts](https://github.com/craftech-io/discord-amazon-cost-anomaly-alerts)** - Anomalías de costos a Discord
- **[discord-amazon-devops-guru-alerts-lambda](https://github.com/craftech-io/discord-amazon-devops-guru-alerts-lambda)** - DevOps Guru a Discord
- **[discord-amazon-guardduty-alerts-lambda](https://github.com/craftech-io/discord-amazon-guardduty-alerts-lambda)** - GuardDuty a Discord
- **[discord-aws-cloudwatch-alerts-lambda](https://github.com/craftech-io/discord-aws-cloudwatch-alerts-lambda)** - Alertas AWS Lambda
- **[discord-grafana-alerts-lambda](https://github.com/craftech-io/discord-grafana-alerts-lambda)** - Grafana a Discord
- **[module-alarms](https://github.com/craftech-io/module-alarms)** - Módulos alarmas CloudWatch
- **[module-grafana-alerting](https://github.com/craftech-io/module-grafana-alerting)** - Módulos alertas Grafana
- **[module-monitoring](https://github.com/craftech-io/module-monitoring)** - Herramientas observabilidad

## Integración con Port.io

- **[module-port](https://github.com/craftech-io/module-port)** - Módulos Port modelos
- **[port-actions-catalog](https://github.com/craftech-io/port-actions-catalog)** - Catálogo acciones Port.io
- **[port-actions-module](https://github.com/craftech-io/port-actions-module)** - Módulo base acciones Port
- **[port-actions](https://github.com/craftech-io/port-actions)** - Backend serverless Port.io
- **[port-aws-auto-tag](https://github.com/craftech-io/port-aws-auto-tag)** - Auto-tagging AWS con OpenAI
- **[port-craftech](https://github.com/craftech-io/port-craftech)** - Integraciones Port.io Craftech
- **[port-idp-klap](https://github.com/craftech-io/port-idp-klap)** - Port IDP Klap
- **[port-io-manager](https://github.com/craftech-io/port-io-manager)** - Port.io Manager IaC

## Kubernetes & EKS

-  (Poner en LABS) **[argo-rollouts-meetup](https://github.com/craftech-io/argo-rollouts-meetup)** - Demo meetup ArgoCD/Rollouts
- **[argocd-diff-preview](https://github.com/craftech-io/argocd-diff-preview)** - ArgoCD Diff Preview
- (Poner en LABS) **[argocd-gitops-demo](https://github.com/craftech-io/argocd-gitops-demo)** - Demo ArgoCD GitOps
- **[argocd-repository-templates](https://github.com/craftech-io/argocd-repository-templates)** - Templates repositorios ArgoCD
- **[ci-tools](https://github.com/craftech-io/ci-tools)** - Docker terraform/terragrunt
- (Poner en LABS) **[demo-eks-scaling-with-keda-and-karpenter](https://github.com/craftech-io/demo-eks-scaling-with-keda-and-karpenter)** - Demo escalado EKS/KEDA
- **[eks-addons](https://github.com/craftech-io/eks-addons)** - Módulos add-ons EKS
- **[eks-cron-shutdown](https://github.com/craftech-io/eks-cron-shutdown)** - Apagado programado clusters EKS
- **[eks-management](https://github.com/craftech-io/eks-management)** - Herramientas gestión EKS
- **[eks-nightly-shutdown-lambda](https://github.com/craftech-io/eks-nightly-shutdown-lambda)** - Shutdown nocturno EKS
- **[helm-charts](https://github.com/craftech-io/helm-charts)** - Gráficos Helm de Craftech
- **[helm-charts-reference](https://github.com/craftech-io/helm-charts-reference)** - Charts Helm de referencia
- **[k6](https://github.com/craftech-io/k6)** - Despliegue de k6 para K8s
- **[kubernetes-application](https://github.com/craftech-io/kubernetes-application)** - Gráfico Helm de aplicación kube
- **[kubernetes-env-to-secrets](https://github.com/craftech-io/kubernetes-env-to-secrets)** - Env a secretos Kubernetes
- **[minikube-cluster](https://github.com/craftech-io/minikube-cluster)** - Cluster Minikube preconfigured
- **[module-eks](https://github.com/craftech-io/module-eks)** - Módulos cluster EKS
- **[module-eks-automode](https://github.com/craftech-io/module-eks-automode)** - Módulos EKS Automode
- **[shutdown-modules](https://github.com/craftech-io/shutdown-modules)** - Módulos shutdown/startup AWS
- **[terraform-kubernetes-application](https://github.com/craftech-io/terraform-kubernetes-application)** - Helm chart Kubernetes (DEPRECATED)
- **[vault-crd](https://github.com/craftech-io/vault-crd)** - Vault CRD para Kubernetes
- **[workshop-opentelemetry](https://github.com/craftech-io/workshop-opentelemetry)** - Workshop EKS OpenTelemetry

## Módulos de Base de Datos

- **[module-databases](https://github.com/craftech-io/module-databases)** - Módulos bases de datos
- **[module-dms](https://github.com/craftech-io/module-dms)** - Módulos DMS (Database Migration)

## Módulos de Infraestructura AWS

- **[module-api-gateway](https://github.com/craftech-io/module-api-gateway)** - Módulos API Gateway
- **[module-athena](https://github.com/craftech-io/module-athena)** - Módulos AWS Athena
- **[module-beanstalk](https://github.com/craftech-io/module-beanstalk)** - Módulo Elastic Beanstalk
- **[module-cloudfront](https://github.com/craftech-io/module-cloudfront)** - Módulos CloudFront (CDN)
- **[module-ecr](https://github.com/craftech-io/module-ecr)** - Módulos ECR
- **[module-identity-center](https://github.com/craftech-io/module-identity-center)** - Módulos Identity Center
- **[module-kafka](https://github.com/craftech-io/module-kafka)** - Módulos MSK (Kafka)
- **[module-kvs](https://github.com/craftech-io/module-kvs)** - Módulos ElastiCache
- **[module-load-balancer](https://github.com/craftech-io/module-load-balancer)** - Módulos Load Balancers
- **[module-migration](https://github.com/craftech-io/module-migration)** - Módulos migración infraestructura
- **[module-organizations](https://github.com/craftech-io/module-organizations)** - Módulos AWS Organizations
- **[modules-azure](https://github.com/craftech-io/modules-azure)** - Módulos VNet Azure
- **[terraform-aws-acm](https://github.com/craftech-io/terraform-aws-acm)** - Módulo certificados ACM
- **[terraform-aws-ecr](https://github.com/craftech-io/terraform-aws-ecr)** - Módulo ECR
- **[terraform-aws-lambda](https://github.com/craftech-io/terraform-aws-lambda)** - Módulos funciones Lambda
- **[terraform-aws-service-catalog](https://github.com/craftech-io/terraform-aws-service-catalog)** - Catálogo servicios AWS

## Módulos de Redes

- **[module-networking](https://github.com/craftech-io/module-networking)** - Módulos VPC AWS
- **[terraform-aws-route53](https://github.com/craftech-io/terraform-aws-route53)** - Módulo Route53

## Módulos de Seguridad e Identidad

- **[module-glue](https://github.com/craftech-io/module-glue)** - Módulos AWS Glue

## Optimización de Costos

- **[aws-nuke](https://github.com/craftech-io/aws-nuke)** - Limpieza automática cuentas AWS
- **[aws-nuke-account-cleanser-example](https://github.com/craftech-io/aws-nuke-account-cleanser-example)** - Framework limpieza cuentas AWS

## Otros

- **[atlantis](https://github.com/craftech-io/atlantis)** - Configuraciones Atlantis
- **[aws-partner-hubspot-connector](https://github.com/craftech-io/aws-partner-hubspot-connector)** - Conector AWS Partner/HubSpot
- (¿Qué es esto?) **[chartmuseum-auth-server](https://github.com/craftech-io/chartmuseum-auth-server)** - Auth server ChartMuseum
- (Eliminar) **[clients](https://github.com/craftech-io/clients)** - Recursos clientes
- (Poner en LABS) **[docker-templates](https://github.com/craftech-io/docker-templates)** - Templates Docker
- **[fast-tech-talks](https://github.com/craftech-io/fast-tech-talks)** - Materiales charlas tech
- (ME MUERO) **[fifa](https://github.com/craftech-io/fifa)** - Experimentación interna
- (Poner en LABS) **[keda-examples](https://github.com/craftech-io/keda-examples)** - Ejemplos KEDA
- **[labs](https://github.com/craftech-io/labs)** - Centro utilidades/experimentos
- **[module-ecs](https://github.com/craftech-io/module-ecs)** - Módulos gestión ECS
- (Eliminar) **[package-vault](https://github.com/craftech-io/package-vault)** - Módulo Vault
- **[tekton-ftt](https://github.com/craftech-io/tekton-ftt)** - Configuración Tekton FTT
- **[terralist](https://github.com/craftech-io/terralist)** - Administrador módulos Terraform
- **[verdaccio](https://github.com/craftech-io/verdaccio)** - Imágenes Docker Verdaccio
- **[wafr-custom-lenses](https://github.com/craftech-io/wafr-custom-lenses)** - Lenses personalizados WAFR

## Referencias y Ejemplos (TODO ESTO PONER EN LABS)

- **[crossplane-demo](https://github.com/craftech-io/crossplane-demo)** - Demo Crossplane IaC
- **[gcp-infrastructure-live-reference](https://github.com/craftech-io/gcp-infrastructure-live-reference)** - Referencia infraestructura GCP
- **[infrastructure-live-reference](https://github.com/craftech-io/infrastructure-live-reference)** - Ref. infraestructura live
- **[infrastructure-module-reference](https://github.com/craftech-io/infrastructure-module-reference)** - Ref. módulos infraestructura
- **[infrastructure-module-reference-security](https://github.com/craftech-io/infrastructure-module-reference-security)** - Referencia seguridad módulos
- **[infrastructure-multi-account-reference](https://github.com/craftech-io/infrastructure-multi-account-reference)** - Ref. multi-cuenta
- **[local-environment-reference](https://github.com/craftech-io/local-environment-reference)** - Ref. entorno local Kind/Skaffold
- **[terraform-template](https://github.com/craftech-io/terraform-template)** - Template módulos Terraform

## Scripts y Utilidades

- (Poner en Labs) **[assessment-scripts](https://github.com/craftech-io/assessment-scripts)** - Scripts evaluación infraestructura
- **[aws-ecr-http-proxy](https://github.com/craftech-io/aws-ecr-http-proxy)** - Proxy pass-through ECR
- (Eliminar?) **[backstage](https://github.com/craftech-io/backstage)** - Portal desarrolladores
- **[module-security](https://github.com/craftech-io/module-security)** - Módulos seguridad/secretos
- **[package-pritunl](https://github.com/craftech-io/package-pritunl)** - Módulo Pritunl VPN
- (Combinar con el Git CI Templates) **[pipelines-reference](https://github.com/craftech-io/pipelines-reference)** - Ejemplos pipelines CI/CD

## Sitios Web y Documentación

- **[blog](https://github.com/craftech-io/blog)** - Blog Craftech
- **[craftech.io](https://github.com/craftech-io/craftech.io)** - Sitio web Craftech.io
- **[docusaurus](https://github.com/craftech-io/docusaurus)** - Sitio Docusaurus

---

**Total de repositorios:** 139
