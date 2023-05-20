| Group | AWS Component | Azure Component | Differences | Usage |
|---|---|---|---|---|
| Virtual Servers | EC2 (Elastic Compute Cloud) | Virtual Machines | Both provide scalable compute capacity in the cloud. AWS provides more customization options, Azure has more straightforward pricing. | Run applications, host websites, perform general server functions. |
| Container Orchestration | ECS (Elastic Container Service), EKS (Elastic Kubernetes Service) | AKS (Azure Kubernetes Service) | Both provide managed Kubernetes services. ECS is a proprietary AWS solution for running containers, not based on Kubernetes. | Deploy, manage, and scale containerized applications using Kubernetes. |
| Serverless Functions | Lambda | Functions | Both allow you to run your code without provisioning or managing servers. AWS Lambda supports more languages natively. Azure Functions offer better integration with Azure's other services. | Event-driven applications, real-time file processing, data transformation etc. |
| Batch Processing | AWS Batch | Azure Batch | Both allow large-scale parallel and high-performance computing applications to efficiently use the full scale of the cloud. | High performance computing, big data analysis, and other batch jobs. |
| Elastic Scaling | Auto Scaling | Virtual Machine Scale Sets | Both offer automatic scale-out and scale-in as per the defined policies. AWS Auto Scaling is more versatile, it can scale other resources in addition to EC2. | Automatically manage the scaling requirements according to the load on the applications. |
| Light-Weight Virtual Servers | Lightsail | Azure B-series VMs | AWS Lightsail offers simple virtual private servers while Azure B-series VMs offer cost efficiency for workloads that do not need the full performance continuously. | Running lightweight applications, simple web servers, developer environments. |
| Dedicated Servers | Dedicated Hosts | Dedicated Host | Both provide physical servers fully dedicated for your use. AWS provides more flexibility with the ability to use existing per-instance software licenses. | Compliance requirements, workload performance, licensing limitations. |
| Container Registry | ECR (Elastic Container Registry) | ACR (Azure Container Registry) | Both offer a Docker container registry to store and manage images. Integration with respective cloud's CI/CD tools. | Store, manage, and deploy Docker container images. |
| Edge Computing | AWS Wavelength, AWS Outposts, AWS Local Zones, AWS Snow Family | Azure Edge Zones, Azure Stack Edge, Azure Stack Hub, Azure Modular Datacenter, Azure Arc | Both providers offer a comprehensive suite of edge computing options, including data center-like controls, devices for rugged or remote locations, and hybrid/multi-cloud management tools. | Applications that require low latency access to end-users or onsite systems, local data processing, or local data storage. |
| VMWare Integration | VMWare Cloud on AWS | Azure VMware Solution | Both offer seamless integration with VMware for a unified hybrid cloud experience. | Extending, migrating and managing your VMware workloads in the cloud. |
| High Performance Computing | AWS ParallelCluster | Azure Batch, Azure CycleCloud | AWS ParallelCluster is an AWS supported Open Source cluster management tool that makes it easy for you to deploy and manage High Performance Computing (HPC) clusters in the AWS cloud. Azure offers Batch and CycleCloud for HPC scenarios. | Running high performance computing applications in the cloud. |
| Managed Application Runtime | AWS App Runner | Azure App Service | AWS App Runner is a service that makes it easy for developers to quickly build, deploy, and run containerized web applications and APIs, at scale and with no prior infrastructure experience required. Azure App Service is a fully managed platform for building, deploying, and scaling your web apps. | Running web applications and APIs without managing infrastructure. |
| Container Instances | AWS Fargate | Azure Container Instances | Both offer a way to run containers without managing servers or clusters. | Running containers without the need to manage the underlying infrastructure. |
| Service Mesh | AWS App Mesh | Azure Service Fabric | AWS App Mesh makes it easy to monitor and control microservices running on AWS. Azure Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers. | Microservices management, traffic routing and monitoring. |