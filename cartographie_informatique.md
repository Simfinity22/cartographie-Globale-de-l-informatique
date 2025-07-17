# Cartographie Globale de l’Informatique 

---

## Théorie & Sciences de l’Information
- Logique Mathématique
- Théorie de l’Information
- Algorithmique & Complexité
- Automates & Langages Formels
- Mathématiques Discrètes

---

## Systèmes & Infrastructure
- Matériel (Hardware)

  - Architecture : CPU, GPU, FPGA

  - Stockage :

    - Mémoire Vive (Volatile) :

      - Registres CPU
      - Cache (L1, L2, L3)
      - RAM (DRAM, SRAM, VRAM)
      - Mémoire Persistante (NVRAM, Persistent Memory comme Intel Optane)

    - Stockage Secondaire (Non-volatile) :

      - Disques Durs (HDD) : stockage magnétique traditionnel
      - Disques SSD (Solid State Drive) : stockage flash NAND rapide
      - Disques Hybrides (SSHD) : combinaison HDD + SSD
      - Disques Optiques : CD, DVD, Blu-ray
      - Supports Amovibles : clés USB, cartes mémoire (SD, microSD)

    - Stockage d’Archivage & Tertiaire :

      - Bandes Magnétiques (LTO, DAT) : stockage longue durée et économique
      - Disques Optiques Archivables (Blu-ray M-Disc)
      - Stockage Cloud “Cold Storage” (ex : AWS Glacier, Google Coldline)

    - Stockage Réseau & Entreprise :

      - NAS (Network Attached Storage) : partage de fichiers via réseau local
      - SAN (Storage Area Network) : stockage bloc haute performance pour serveurs
      - RAID (Redundant Array of Independent Disks) : configurations redondantes pour performance et fiabilité
      - Stockage Distribué (Ceph, GlusterFS) : systèmes de fichiers répartis sur plusieurs machines
      - Stockage Objet (Amazon S3, Azure Blob Storage, MinIO) : stockage scalable orienté objets

    - Cartes d’extension :

      - Cartes réseau (NIC, cartes Wi-Fi)
      - Cartes son
      - Cartes graphiques (GPU dédiés)
      - Cartes d’accélération (TPU, ASICs)
      - Cartes de capture vidéo

    - Bus et Interfaces : 

      - PCIe, PCI, AGP
      - USB (Type-A, Type-C), Thunderbolt
      - SATA, NVMe
      - Ethernet (RJ45, fibre optique)
      - HDMI, DisplayPort, VGA (vidéo)
      - Bluetooth, Wi-Fi (cartes/radios)

    - Firmware & Microprogrammes :

      - BIOS / UEFI
      - Contrôleurs intégrés (microcontrôleurs dans SSD, carte réseau, etc.)

- Systèmes d’Exploitation

  - Linux (Debian, Ubuntu, CentOS, RHEL, Arch)
  - Windows (Desktop, Windows Server)
  - UNIX, BSD
  - macOS
  - Systèmes mobiles :
    - iOS
    - Android
  - Systèmes temps réel (RTOS) :
    - FreeRTOS
    - VxWorks
    - QNX
    - Zephyr

## Réseaux & Télécommunications

- Modèles de Réseau

  - OSI (Open Systems Interconnection)
  - TCP/IP (Transmission Control Protocol / Internet Protocol)

- Switching, Routing & VLAN

  - Switching : STP (Spanning Tree Protocol), RSTP, MSTP
  - VLAN, VTP (VLAN Trunking Protocol)
  - LACP (Link Aggregation Control Protocol)
  - Routing : OSPF, BGP, RIP, EIGRP, IS-IS

- SDN (Software Defined Networking)

  - OpenDaylight, ONOS, Cisco ACI

- Analyse & Diagnostic

  - Outils : Wireshark, Nmap, tcpdump, NetFlow, IPFIX, ntopng, sFlow, Syslog

- Protocoles Réseau Fondamentaux

  - IPv4
  - IPv6

- Protocole IPv4

  - ARP (Address Resolution Protocol)
  - ICMP (Internet Control Message Protocol)
  - IGMP (Internet Group Management Protocol)
  - DHCP (Dynamic Host Configuration Protocol)
  - DNS (Domain Name System)

- Protocole IPv6

  - ICMPv6 (Internet Control Message Protocol for IPv6)
  - NDP (Neighbor Discovery Protocol)
  - DHCPv6 (Dynamic Host Configuration Protocol for IPv6)
  - DNSSEC (DNS Security Extensions)

- Protocoles de Transport

  - TCP (Transmission Control Protocol)
  - UDP (User Datagram Protocol)
  - SCTP (Stream Control Transmission Protocol)
  - DCCP (Datagram Congestion Control Protocol)

- Protocoles d’Application

  - HTTP / HTTPS
  - FTP / SFTP / SCP
  - SMTP, POP3, IMAP
  - LDAP
  - SIP, RTP, RTSP
  - MQTT, CoAP

- Protocoles Multicast

  - PIM (Protocol Independent Multicast)
  - DVMRP (Distance Vector Multicast Routing Protocol)
  - IGMP

- Protocoles de Virtualisation & Overlay

  - GRE (Generic Routing Encapsulation)
  - VXLAN (Virtual Extensible LAN)
  - NVGRE
  - MPLS (Multiprotocol Label Switching)

- Protocoles Sécurité & VPN

  - IPSec
  - SSL/TLS
  - IKE
  - L2TP, PPTP
  - OpenVPN
  - VPN entreprise : Cisco AnyConnect, FortiClient
  - VPN grand public : ProtonVPN, NordVPN, ExpressVPN, Mullvad, TunnelBear

- Protocoles de Gestion & Supervision

  - SNMP (Simple Network Management Protocol)
  - Syslog
  - NetFlow, sFlow, IPFIX
  - NTP (Network Time Protocol)
  - RADIUS, TACACS+

- Réseaux Sans Fil (Wi-Fi)

  - IEEE 802.11 a/b/g/n/ac/ax
  - WPA2, WPA3
  - Bluetooth (IEEE 802.15.1)
  - LTE, 5G NR

- IoT & Réseaux Bas Débit

  - NB-IoT (Narrowband IoT)
  - LoRaWAN
  - Zigbee
  - Z-Wave
  - Thread
  - Sigfox

- Virtualisation & Conteneurs

  - Hyperviseurs & Virtualisation

    - Type 1 : VMware vSphere, ESXi, Proxmox, KVM, Xen, Hyper-V
    - Type 2 : VirtualBox, VMware Workstation, Parallels Desktop

    - Concepts avancés :
      - vMotion / Live Migration
      - High Availability (HA)
      - Fault Tolerance (FT)
      - Clustering
      - NUMA Awareness
      - GPU Passthrough / SR-IOV

  - Conteneurisation
    
    - Runtimes : Docker, containerd, CRI-O, runc, Kata Containers, Firecracker
    - Builders : Docker, Podman, Buildah, Kaniko, BuildKit
    - Registres : Docker Hub, Harbor, Quay.io, GitHub Container Registry, GCR, ECR

  - Orchestration & Scheduling
    
    - Kubernetes Ecosystem : Kubernetes, OpenShift, Rancher, K3s, KIND, kubeadm, Minikube
    - Gestion & Automatisation : Helm, Kustomize, ArgoCD, FluxCD, Tekton, Operators

  - Réseau & Service Mesh
    
    - Service Mesh : Istio, Linkerd, Consul Connect, Kuma
    - CNI Plugins : Flannel, Calico, Weave Net, Cilium

  - Sécurité Conteneurs
    
    - Sécurité Runtime : SELinux, AppArmor, Seccomp, PodSecurityPolicies, OPA, Falco
    - Scanning & Compliance : Trivy, Clair, Anchore, Docker Bench for Security, Kube-bench

  - Stockage & Persistance
    
    - CSI Plugins : Ceph RBD, Longhorn, Portworx, OpenEBS
    - Concepts : Persistent Volumes (PV), Persistent Volume Claims (PVC), StatefulSets

  - Supervision & Observabilité
    
    - Monitoring & Tracing : Prometheus, Grafana, Thanos, Loki, Jaeger, OpenTelemetry

  - Infrastructure as Code & Automation
    
    - Outils : Terraform, Ansible, Pulumi, Crossplane
  
- Cloud computing (IaaS, PaaS, SaaS, CaaS)

  - IaaS
    - AWS EC2, AWS EBS, AWS VPC, AWS Elastic IP
    - Azure Virtual Machines, Azure Managed Disks, Azure Virtual Network
    - Google Compute Engine, Google Persistent Disks, Google VPC
    - OpenStack (plateforme cloud open source)
    - DigitalOcean Droplets
    - IBM Cloud Virtual Servers
    - Oracle Cloud Infrastructure Compute
    - VMware Cloud on AWS

  - PaaS
    - AWS Elastic Beanstalk, AWS Lambda (serverless)
    - Azure App Service, Azure Functions
    - Google App Engine, Google Cloud Functions
    - Heroku
    - Red Hat OpenShift (Kubernetes PaaS)
    - Cloud Foundry
    - Mendix, OutSystems (Low-code PaaS)
    - IBM Cloud Foundry
    - SAP Cloud Platform

  - SaaS
    - Microsoft 365, Google Workspace
    - Salesforce, ServiceNow
    - Dropbox, Box
    - Slack, Microsoft Teams, Zoom
    - Atlassian Jira, Confluence
    - Adobe Creative Cloud
    - Zendesk, Freshdesk
    - GitHub, GitLab (en mode SaaS)

  - CaaS
    - AWS Fargate, Azure Container Instances, Google Cloud Run
    - DigitalOcean App Platform
    - Red Hat OpenShift (CaaS et PaaS)
    - Rancher
    - Docker Enterprise, Mirantis Kubernetes Engine
    - Google Anthos (multi-cloud Kubernetes)
    - VMware Tanzu
    - Portainer

  - Infrastructure as Code (IaC)
    - Terraform, Pulumi
    - AWS CloudFormation, Azure ARM Templates, Google Deployment Manager
    - Ansible (provisioning)
    - Chef, Puppet, SaltStack
    - Packer

  - Orchestration & Automation
    - Kubernetes, OpenShift, Rancher, K3s, MicroK8s
    - Helm, Kustomize (gestion des charts)
    - ArgoCD, FluxCD (GitOps)
    - Jenkins X, Tekton (CI/CD Kubernetes-native)
    - Spinnaker

  - Cloud Networking & Security
    - AWS Security Groups, Network ACLs, AWS WAF, AWS Shield
    - Azure NSG (Network Security Groups), Azure Firewall
    - Google Cloud Firewall, Cloud Armor
    - VPN CloudHub, AWS Transit Gateway
    - Service Mesh : Istio, Linkerd, Consul Connect
    - Zero Trust Architecture, BeyondCorp

  - Storage & Databases managés
    - AWS S3, Glacier, EFS, FSx
    - Azure Blob Storage, File Storage, Data Lake Storage
    - Google Cloud Storage, Filestore, Bigtable
    - Bases relationnelles : AWS RDS, Azure SQL Database, Google Cloud SQL
    - Bases NoSQL : DynamoDB, Cosmos DB, Google Firestore, MongoDB Atlas
    - Bases en mémoire : Redis Labs, Amazon ElastiCache, Azure Cache for Redis

  - Serverless & Functions
    - AWS Lambda, Azure Functions, Google Cloud Functions
    - IBM Cloud Functions (OpenWhisk)
    - Knative (Kubernetes serverless framework)
    - Fission, OpenFaaS

  - Monitoring & Observability
    - AWS CloudWatch, Azure Monitor, Google Stackdriver (Operations)
    - Prometheus, Grafana
    - Datadog, New Relic, Dynatrace
    - ELK Stack (Elasticsearch, Logstash, Kibana)
    - OpenTelemetry

  - DevOps & CI/CD dans le Cloud
    - AWS CodePipeline, Azure DevOps, Google Cloud Build
    - GitHub Actions, GitLab CI/CD, Jenkins, Travis CI, CircleCI
    - Spinnaker, Harness
    - Vault (HashiCorp) pour gestion des secrets
    - SonarQube (qualité code)

  - Multi-cloud & Hybrid Cloud
    - Anthos (Google)
    - Azure Arc
    - AWS Outposts
    - HashiCorp Consul & Terraform Enterprise
    - VMware Cloud Foundation
    - Cloud management platforms : RightScale, Scalr, Morpheus

  - Cloud Cost Management & Governance
    - AWS Cost Explorer, Azure Cost Management, Google Cloud Billing
    - CloudHealth, Cloudability, Spot.io
    - Policies & Quotas : AWS Organizations, Azure Policy, GCP Organization Policies

  - Containers & Runtime
    - Docker, Podman, Buildah, Kaniko
    - containerd, CRI-O
    - OpenShift Container Platform
    - VMware Harbor (registry)
    - Google Artifact Registry, AWS ECR, Azure Container Registry


  
- Services d’Annuaire & Gestion d’Identité

  - Active Directory (Microsoft)
    - AD DS (Domain Services)
    - AD FS (Federation Services)
    - AD LDS (Lightweight Directory Services)
    - Azure AD Connect (sync on-premises AD avec Azure AD)
    - Azure AD Domain Services
    - Microsoft Entra ID (nouveau nom pour Azure AD)
    - Microsoft Identity Manager (MIM)
    - Group Policy Objects (GPO)
    - Kerberos Authentication
    - NTLM Authentication
    - LDAP over SSL/TLS (LDAPS)

  - LDAP (Lightweight Directory Access Protocol)
    - OpenLDAP
    - 389 Directory Server (Red Hat)
    - Apache Directory Server
    - Microsoft Active Directory (implémentation LDAP)
    - ApacheDS
    - OpenDJ
    - Protocoles associés : SASL, StartTLS
    - Schémas LDAP (schema extensions, RFC 4512)
    - Synchronisation LDAP : Syncrepl

  - FreeIPA
    - Intégration Kerberos + LDAP + DNS + CA (Certificate Authority)
    - Gestion centralisée des identités, politiques et audits
    - IPA Server, IPA Client
    - Authentification forte (2FA)
    - Gestion des hôtes et groupes
    - Intégration avec SSSD (System Security Services Daemon)

  - Azure AD
    - Azure Active Directory B2B (Business to Business)
    - Azure Active Directory B2C (Business to Consumer)
    - Microsoft Entra Verified ID (Identity verification)
    - OAuth 2.0, OpenID Connect, SAML support
    - Conditional Access Policies
    - Identity Protection
    - Privileged Identity Management (PIM)
    - Passwordless Authentication (FIDO2, Windows Hello)
    - Azure AD Domain Services (Managed Domain)
    - Self-Service Password Reset (SSPR)
    - Integration avec Microsoft 365, Intune, Teams

  - Protocoles & Standards d’Authentification & Autorisation
    - Kerberos
    - NTLM
    - OAuth 2.0
    - OpenID Connect (OIDC)
    - SAML (Security Assertion Markup Language)
    - RADIUS
    - TACACS+
    - SCIM (System for Cross-domain Identity Management)
    - FIDO2 / WebAuthn (authentification sans mot de passe)

  - IAM (Identity and Access Management) Solutions
    - Keycloak (Open Source IAM)
    - Okta
    - Auth0
    - Ping Identity
    - OneLogin
    - ForgeRock
    - Centrify
    - AWS IAM (Identity and Access Management)
    - Google Cloud IAM
    - Azure RBAC (Role-Based Access Control)

  - Gestion des accès & politiques
    - RBAC (Role-Based Access Control)
    - ABAC (Attribute-Based Access Control)
    - PBAC (Policy-Based Access Control)
    - MFA (Multi-Factor Authentication)
    - Single Sign-On (SSO)
    - Just-in-Time Access
    - Identity Federation
    - Access Reviews / Certifications

  - Gestion des secrets et tokens
    - OAuth tokens
    - JWT (JSON Web Tokens)
    - API Keys
    - HashiCorp Vault
    - AWS Secrets Manager
    - Azure Key Vault
    - CyberArk

- Partage & Protocoles Réseau

  - Samba (partage fichiers Windows/Linux)
    - SMB (Server Message Block) protocol versions : SMB1, SMB2, SMB3
    - CIFS (Common Internet File System)
    - Active Directory integration
    - Winbind (intégration utilisateurs AD)
    - Samba Domain Controller (Primary et Backup)
    - Printing via Samba (CUPS integration)
    - smbclient (outil ligne de commande)
    - smb.conf (fichier de configuration)
    - VFS modules (Virtual File System)
    - Kerberos authentication support
    - Encryption and signing support (SMB3)
  
  - NFS (Network File System)
    - Versions : NFSv3, NFSv4, NFSv4.1, NFSv4.2
    - Stateless vs Stateful protocol
    - Kerberos security integration (sec=krb5)
    - ACL support (Access Control Lists)
    - NFS over TCP/UDP
    - Mountd, rpcbind, nfsd (daemons)
    - automount / autofs
    - Ganesha NFS (user-space NFS server)
    - Client-side caching and delegations
  
  - CIFS (Common Internet File System)
    - Souvent confondu avec SMB (implémentation Microsoft)
    - Compatible avec Samba
    - Utilisé surtout pour Windows file sharing
    - Support des locks et journaling
  
  - FTP / SFTP / SCP
    - FTP (File Transfer Protocol)
      - Active vs Passive modes
      - FTP over TLS/SSL (FTPS)
      - Anonymous FTP
      - FTP Servers : vsftpd, proftpd, pure-ftpd
    - SFTP (SSH File Transfer Protocol)
      - Fonctionne via SSH (port 22)
      - Clients : OpenSSH sftp, WinSCP, FileZilla
      - Authentification par clés ou mots de passe
      - Support de transferts sécurisés et gestion des permissions
    - SCP (Secure Copy)
      - Utilise SSH pour transfert sécurisé
      - Commande simple pour copier fichiers entre hôtes
      - Moins flexible que SFTP (pas d’interface interactive)
  
  - Autres protocoles et outils associés
    - Rsync (synchronisation efficace via SSH)
    - WebDAV (HTTP-based file sharing)
    - AFP (Apple Filing Protocol, macOS)
    - NCP (NetWare Core Protocol)
    - FTP clients graphiques : FileZilla, Cyberduck
    - FTP servers populaires : IIS FTP, Wu-ftpd
    - FTP bounce attack (sécurité)
    - SCP alternatives : rsync, sftp
    - SMB Direct / SMB over RDMA (pour haute performance)
    - Distributed File Systems : GlusterFS, CephFS, Lustre

- Gestion de Configuration & Orchestration

  - Ansible
    - Playbooks YAML
    - Modules intégrés (file, user, yum, apt, systemd, etc.)
    - Rôles et collections
    - Ansible Tower / AWX (interface web, gestion centralisée)
    - Inventaires dynamiques (cloud, VMware, etc.)
    - Ansible Galaxy (partage de rôles)
    - Ansible Vault (chiffrement des secrets)
    - Automation sans agent (agentless)
    - Intégration avec CI/CD (Jenkins, GitLab CI)
  
  - Puppet
    - Puppet DSL (Domain Specific Language)
    - Manifests et modules
    - Puppet Enterprise (console, reporting)
    - Puppet Forge (catalogue de modules)
    - Agents Puppet sur machines gérées
    - Puppet Bolt (exécution sans agent)
    - Resource abstraction layer (RAL)
    - Classification automatique (node classification)
    - Reporting et audits de configuration
  
  - Chef
    - Recipes et cookbooks (Ruby DSL)
    - Chef Server, Chef Workstation, Chef Client
    - Knife (outil en ligne de commande)
    - Chef Supermarket (catalogue de cookbooks)
    - InSpec (tests d’infrastructure)
    - Habitat (packaging d’applications)
    - Chef Automate (dashboard, compliance, workflow)
    - Gestion de dépendances et environnement (Berkshelf)
    - Support du cloud et containers
  
  - SaltStack
    - Salt Master / Salt Minion (architecture master/minion)
    - SLS files (Salt State files, YAML)
    - Exécutions à distance (remote execution)
    - Pillar data (données sécurisées)
    - Salt SSH (gestion sans agent)
    - Orchestration via Salt Orchestrate
    - Event-driven automation (reactors)
    - Salt Cloud (provisioning cloud)
    - Intégration avec Kubernetes, Docker
    - Salt Mine (partage d’informations entre minions)
  
  - Autres outils & concepts associés
    - Terraform (Infrastructure as Code, provisioning)
    - CFEngine (ancien, mais encore utilisé)
    - Juju (orchestration services)
    - Consul (service discovery, configuration)
    - Vault (gestion des secrets, HashiCorp)
    - Packer (build d’images machine)
    - GitOps (flux de gestion infra via Git)
    - CI/CD intégration (GitLab, Jenkins, ArgoCD)
    - Configuration as Data (définition déclarative)
    - Idempotence (exécution répétée sans effet indésirable)

---

## Développement & Ingénierie Logicielle

- Langages de programmation
  - Bas Niveau :
    - Assembleur (x86, ARM, MIPS…)
    - Ada
    - C
    
  - Moyen Niveau : 
    - C++
    - Rust
    - Go
    - C#
    - Objective-C
    
  - Haut Niveau :
    - Java
    - Kotlin
    - Scala
    - Python
    - Ruby
    - PHP
    - Perl
    - Lua
    - JavaScript
    - TypeScript
    - Dart
    - Swift
    - R
    - F#
    - Erlang
    - Haskell
    
- Paradigmes 
  
  - POO, Fonctionnel, Réactif
  
- Génie Logiciel & DevOps
  
  - Méthodes Agiles, Scrum
  - Git, GitHub, GitLab, Bitbucket, Gitea
  - CI/CD : Jenkins, GitLab CI, GitHub Actions, Travis CI, CircleCI, Drone CI
  - Tests (Unitaire, Intégration), TDD, BDD, SRE

- Langages de Script & Automatisation
  
  - Bash / Shell scripting
  - PowerShell
  - Groovy (Jenkins pipelines)
  - [Note : Python, Perl, Ruby, Lua sont aussi largement utilisés pour le scripting]



## Développement Web

### Frontend

- HTML
- CSS
- JavaScript Frameworks : React, Angular, Vue.js, Svelte
- Frameworks Fullstack / SSR : Next.js, Nuxt.js

### Backend

- Node.js
- Django
- Flask
- Spring Boot
- Express
- NestJS
- Laravel
- Symfony
- Ruby on Rails
- .NET
- ASP.NET Core

### API & Intégration

- REST
- GraphQL
- Swagger / OpenAPI
- Postman
- gRPC

---

## Développement Mobile

- iOS (Swift, Objective-C)
- Android natif (Java, Kotlin)
- Cross-platform : Flutter, React Native, Xamarin, Ionic

---

## IDE & Éditeurs

- Visual Studio Code (VS Code)
- JetBrains : IntelliJ IDEA, PyCharm, WebSt
- Eclipse 

---

## Données & Intelligence Artificielle

- Bases de Données
  - SQL : Oracle, PostgreSQL, MySQL, MariaDB, MSSQL, SQLite, CockroachDB, Amazon Aurora
  - NoSQL : MongoDB, CouchDB, Cassandra, DynamoDB, Redis, Neo4j, Elasticsearch, HBase, Amazon DocumentDB
  - Streaming : Apache Kafka, RabbitMQ, Apache Pulsar, Amazon Kinesis, Google Pub/Sub

- Big Data et Data Engineering
  - Hadoop, Apache Spark, Apache Hive, Apache Pig, Apache Flink, Apache Beam, Presto/Trino, Apache NiFi

- BI & Data Visualization
  - Power BI, Tableau, Apache Superset, Grafana, Kibana, Looker, QlikView, Metabase, Google Data Studio

- Data Science & Machine Learning / Intelligence Artificielle
  - Environnements : Jupyter Notebook/JupyterLab, RStudio, Google Colab, Anaconda, Spyder, VS Code, Quarto
  - Librairies/Frameworks : scikit-learn, TensorFlow, PyTorch, Keras, XGBoost, LightGBM, CatBoost, OpenCV, SpaCy
  - AutoML : H2O.ai, DataRobot, Azure AutoML, Google AutoML, Auto-sklearn

- ETL & Pipelines
  - Outils : Apache Airflow, Apache NiFi, Talend, Pentaho Data Integration, Luigi, DBT, Prefect

- MLOps
  - MLflow, Kubeflow, DVC, Seldon Core, TensorFlow Extended (TFX), Pachyderm, Metaflow

- IA Avancée
  - Deep Learning, Large Language Models (LLMs), Reinforcement Learning, GANs, Éthique de l’IA, Explainable AI (XAI), Federated Learning

---

## Cybersécurité & Confiance Numérique

- Concepts Fondamentaux :

  - Principes : CIA (Confidentialité, Intégrité, Disponibilité)
  - AAA (Authentication, Authorization, Accounting)
  - Modèles de sécurité : Bell-LaPadula, Biba, Clark-Wilson, Brewer-Nash
  - Paradigmes modernes :
    - Défense en profondeur
    - Principe du moindre privilège
    - Sécurité Zéro Trust (Zero Trust)
    - Sécurité adaptative (Adaptive Security)
    - Sécurité basée sur les risques (Risk-Based Security)
  - Gestion des risques : Analyse des risques, Évaluation des vulnérabilités, Modèles de menace (STRIDE, DREAD)
  - Gestion des accès : MFA, SSO, IAM, PAM
  - Surveillance & détection : IDS/IPS, SIEM, UEBA
  - Conformité et audit : RGPD, HIPAA, PCI-DSS, ISO 27001

- Cryptographie & PKI :

  - Chiffrement symétrique (AES, DES, 3DES)
  - Chiffrement asymétrique (RSA, ECC, Diffie-Hellman)
  - Hachage (SHA-2, SHA-3, MD5)
  - Signatures numériques, certificats SSL/TLS
  - outils : CyberChef, Hashcat, John the Ripper, RsaCtfTool, CrackStation, Cain & Abel, fcrackzip, stegsolve
  - Autorités de Certification internes et publiques

- Gestion des Identités & Accès (IAM) & Gestion des Secrets :

  - IAM : Azure AD, Okta, Keycloak, FreeIPA
  - Gestion des secrets : CyberArk, HashiCorp Vault, AWS Secrets Manager, Azure Key Vault

- Sécurité Réseau & Applicative :

  - Pare-feu & Proxy : iptables, pfSense, OPNsense, IPFire, FortiGate, Palo Alto NGFW, Zscaler
  - IDS/IPS : Snort, Suricata, Zeek/Bro
  - VPN :
    - Entreprise : OpenVPN, WireGuard, IPsec, StrongSwan, Cisco AnyConnect, FortiClient
    - Grand public : ProtonVPN, NordVPN, ExpressVPN, Mullvad, TunnelBear
  - SIEM : Splunk, ELK Stack (ElasticSearch, Logstash, Kibana), Graylog, Wazuh, OSSEC

- Gouvernance, Conformité & Audit :

  - Normes : ISO 27001, RGPD, SOC 2, PCI-DSS
  - Outils : OpenVAS, Lynis, Qualys, CIS Benchmarks

- Pentest & Red Team :

  - OS : Kali Linux, Parrot OS
  - Outils : Metasploit, Burp Suite, OWASP ZAP, Nikto, Nessus, Nmap, SQLmap, Hydra, John the Ripper, Hashcat, Aircrack-ng, Wifite

- Forensic & Analyse :

  - Autopsy, Sleuth Kit, Volatility, FTK Imager, Wireshark, tcpdump, binwalk, foremost, strings, exiftool, Bulk Extractor, PhotoRec, Scalpel

- PWN / Exploit Binaire :
    - GDB, pwntools, Ghidra, IDA Pro, Binary Ninja, Radare2, angr, ROPgadget, one_gadget, peda, pwndbg, checksec

- Reverse Engineering :
    - Ghidra, IDA Pro, Binary Ninja, Hopper, x64dbg, OllyDbg, Frida, apktool, jadx, JEB Decompiler, de4dot, dnSpy, dotPeek, unicorn

- Web :
    - Burp Suite, OWASP ZAP, sqlmap, wfuzz, dirb, gobuster, nikto, wpscan, FFUF, Postman, curl, mitmproxy, Fiddler, XSStrike, JWT Tool, NoSQLMap

- OSINT :
    - Maltego, SpiderFoot, theHarvester, Recon-ng, Shodan, Censys, Google Dorks, FOCA, Metagoofil, sherlock, holehe, social-analyzer, Amass, OSINT Framework, Creepy, Twint, GHunt, Sn0int, Skymem, ReconDog

- Steganography :
    - Steghide, zsteg, stegsolve, stegosuite, exiftool, binwalk, outguess, pngcheck, audacity, Sonic Visualiser, stegcracker

- Mobile :
    - MobSF, Frida, apktool, JADX, Ghidra, drozer, objection, Magisk, Androguard

- Networking :
    - Wireshark, tcpdump, Scapy, tshark, Netcat, socat, Nmap, hping3, Ettercap, Bettercap, mitmproxy, Snort, Suricata

- Hardware / IoT :
    - Bus Pirate, JTAGulator, Chipsec, Logic Analyser (Saleae), OpenOCD, Flashrom, FTDI, RFIDler, Proxmark3, HackRF, GQRX, SDR#

- Miscellaneous :
    - Python, Bash, Perl, Ruby, pwntools, SageMath, custom scripts, sed, awk, jq

- Social Engineering :
    - SET (Social-Engineer Toolkit), Gophish, King Phisher, Evilginx2, Modlishka, BeEF


---

## Interfaces & Tech Immersives

- UX/UI Design : 
  - Outils : Figma, Adobe XD, Sketch, InVision, Axure RP
  - Concepts : Design System, Accessibilité, Responsive Design

- Réalité Augmentée (AR) :
  - Frameworks : ARKit (Apple), ARCore (Google), Vuforia, Wikitude
  - Exemples : Apps mobiles, Retail, Industrie

- Réalité Virtuelle (VR) :
  - Plateformes : Oculus Quest, HTC Vive, Valve Index 
  - Frameworks : Unity 3D, Unreal Engine, WebXR 

- Métavers & Interfaces Homme-Machine (IHM) :
  - Technologies : Web3D, OpenXR, Haptics, Eye Tracking 
  - Exemples : VR social, collaboration immersive

- IoT & Edge Computing :
  - Protocoles : MQTT, CoAP, LoRaWAN
  - Plateformes : AWS IoT, Azure IoT Hub, Google Cloud IoT
  - Matériel : Raspberry Pi, ESP32, NVIDIA Jetson

- Systèmes Embarqués :
  - Cartes & Microcontrôleurs : Arduino, Raspberry Pi, STM32, ESP32
  - OS Temps Réel (RTOS) : FreeRTOS, Zephyr, VxWorks, QNX
  - Outils : PlatformIO, Keil MDK, IAR Embedded Workbench

---

## Gouvernance & Management

- Architecture d’Entreprise :
  - Cadres : TOGAF, Zachman, ArchiMate
  - Outils : Sparx Enterprise Architect, Bizzdesign, Orbus iServer, MEGA International, Avolution ABACUS, HOPEX (MEGA)

- IT Service Management (ITSM) :
  - Référentiels : ITIL v4, COBIT 5 / COBIT 2019, ISO/IEC 20000
  - Outils : ServiceNow, Jira Service Management, BMC Remedy, Ivanti, ManageEngine ServiceDesk Plus, Freshservice, Cherwell

- Gestion de Projet :
  - Méthodologies : PMBOK (PMP, CAPM), Prince2, Agile, Scrum, Kanban, Lean
  - Outils : Microsoft Project, Jira, Asana, Trello, Monday.com, Wrike, ClickUp, Smartsheet, Redmine

- Continuité & Résilience :
  - Concepts : PCA (Plan de Continuité d’Activité), PRA (Plan de Reprise d’Activité), Disaster Recovery, Crisis Management
  - Normes : ISO 22301 (BCMS), ISO 27031 (ICT DR)
  - Outils : Fusion Framework System, RSA Archer Business Continuity, Castellan, Continuity Logic, Everbridge

- Transformation Digitale & Urbanisation SI :
  - Concepts : Urbanisation des SI, Green IT, Sobriété Numérique, Cloud Adoption Frameworks
  - Outils : LeanIX, Planview, MEGA HOPEX, Alfabet, EcoIndex, GreenIT.fr (ressources)

- Gouvernance, Conformité & Normes :
  - Référentiels NIST :
    - NIST SP 800-53 : Security and Privacy Controls
    - NIST CSF : Cybersecurity Framework
    - NIST SP 800-37 : Risk Management Framework (RMF)
    - NIST SP 800-30 : Risk Assessments
    - NIST SP 800-171 : Protection of CUI
    - NIST SP 800-207 : Zero Trust Architecture
  - Normes ISO/IEC :
    - ISO/IEC 27001 : Management de la Sécurité de l’Information (ISMS)
    - ISO/IEC 27002 : Contrôles de sécurité
    - ISO/IEC 27005 : Gestion des risques
    - ISO/IEC 27701 : Privacy Information Management
    - ISO/IEC 20000 : ITSM
    - ISO/IEC 38500 : Gouvernance des SI
    - ISO 22301 : Continuité d’activité
    - ISO 31000 : Management du risque
    - ISO 9001 : Qualité
    - ISO/IEC 29100 : Privacy Framework
    - IEC 62443 : Sécurité des systèmes industriels et OT/ICS
  - Bonnes Pratiques Complémentaires :
    - COBIT, ITIL, PMBOK, Prince2, Agile/Scrum
  - Outils GRC & Conformité :
    - RSA Archer, MetricStream, OneTrust, TrustArc, ISMS.online, LogicManager, Drata, Vanta, ServiceNow GRC, Qualys, Tenable.io

---

## Certifications Globales

### Généralistes & Entry-level

- **CompTIA :** ITF+, A+, Network+, Security+, CySA+, CASP+
- **Linux :** LPIC-1, LPIC-2, LPIC-3
- **Red Hat :** RHCSA, RHCE
- **VMware :** VCTA, VCP, VCAP, VCDX

### Cloud

- **AWS :** Cloud Practitioner, Solutions Architect, Developer, SysOps
- **Microsoft Azure :** AZ-900, AZ-104, AZ-305
- **Google Cloud :** ACE, PCA, PCD, PME
- **Alibaba Cloud :** ACA, ACP
- **HashiCorp :** Terraform Associate
- **Kubernetes :** CKA, CKAD, CKS

### Réseau & Sécurité

- **Cisco :** CCNA, CCNP, CCIE
- **Juniper :** JNCIA, JNCIS, JNCIP
- **Fortinet :** NSE 1 → 8
- **Palo Alto :** PCNSA, PCNSE
- **Aruba :** Certified Mobility Associate / Professional
- **EC-Council :** CEH (Certified Ethical Hacker)
- **Offensive Security :** OSCP, OSCE
- **(ISC)² :** CISSP, SSCP
- **ISACA :** CISM, CISA
- **GIAC :** GSEC, GPEN, GWAPT, etc.

### DevOps & Conteneurs

- **Jenkins :** Jenkins Engineer
- **GitLab :** Certified CI/CD Associate
- **Docker :** DCA (*suspendue*)
- **HashiCorp :** Terraform Associate, Vault Associate
- **Puppet :** Certified Professional

### Données & IA

- **Microsoft Azure :** Data Engineer
- **Google Cloud :** Professional Data Engineer, Machine Learning Engineer
- **TensorFlow :** Developer Certificate
- **Databricks :** Certified Data Engineer Associate / Professional
- **IBM :** Certified AI Engineer

### Gouvernance & Management

- **ITIL :** 4 Foundation, Managing Professional
- **PRINCE2 :** Foundation / Practitioner
- **PMI :** PMP, CAPM
- **TOGAF :** 9 Certified
- **COBIT :** 5 Foundation

