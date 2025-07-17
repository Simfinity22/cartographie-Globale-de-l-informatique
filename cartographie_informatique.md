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

---

### Modèles de Réseau

- OSI (Open Systems Interconnection)
- TCP/IP (Transmission Control Protocol / Internet Protocol)

---

### Switching, Routing & VLAN

- Switching : STP (Spanning Tree Protocol), RSTP, MSTP
- VLAN, VTP (VLAN Trunking Protocol)
- LACP (Link Aggregation Control Protocol)
- Routing : OSPF, BGP, RIP, EIGRP, IS-IS

---

### SDN (Software Defined Networking)

- OpenDaylight, ONOS, Cisco ACI

---

### Analyse & Diagnostic

- Outils : Wireshark, Nmap, tcpdump, NetFlow, IPFIX, ntopng, sFlow, Syslog

---

### Protocoles Réseau Fondamentaux

- IPv4
- IPv6

#### Protocole IPv4

- ARP (Address Resolution Protocol)
- ICMP (Internet Control Message Protocol)
- IGMP (Internet Group Management Protocol)
- DHCP (Dynamic Host Configuration Protocol)
- DNS (Domain Name System)

#### Protocole IPv6

- ICMPv6 (Internet Control Message Protocol for IPv6)
- NDP (Neighbor Discovery Protocol)
- DHCPv6 (Dynamic Host Configuration Protocol for IPv6)
- DNSSEC (DNS Security Extensions)

---

### Protocoles de Transport

- TCP (Transmission Control Protocol)
- UDP (User Datagram Protocol)
- SCTP (Stream Control Transmission Protocol)
- DCCP (Datagram Congestion Control Protocol)

---

### Protocoles d’Application

- HTTP / HTTPS
- FTP / SFTP / SCP
- SMTP, POP3, IMAP
- LDAP
- SIP, RTP, RTSP
- MQTT, CoAP

---

### Protocoles Multicast

- PIM (Protocol Independent Multicast)
- DVMRP (Distance Vector Multicast Routing Protocol)
- IGMP

---

### Protocoles de Virtualisation & Overlay

- GRE (Generic Routing Encapsulation)
- VXLAN (Virtual Extensible LAN)
- NVGRE
- MPLS (Multiprotocol Label Switching)

---

### Protocoles Sécurité & VPN

- IPSec
- SSL/TLS
- IKE
- L2TP, PPTP
- OpenVPN
- VPN entreprise : Cisco AnyConnect, FortiClient
- VPN grand public : ProtonVPN, NordVPN, ExpressVPN, Mullvad, TunnelBear

---

### Protocoles de Gestion & Supervision

- SNMP (Simple Network Management Protocol)
- Syslog
- NetFlow, sFlow, IPFIX
- NTP (Network Time Protocol)
- RADIUS, TACACS+

---

### Réseaux Sans Fil (Wi-Fi)

- IEEE 802.11 a/b/g/n/ac/ax
- WPA2, WPA3
- Bluetooth (IEEE 802.15.1)
- LTE, 5G NR

---

### IoT & Réseaux Bas Débit

- NB-IoT (Narrowband IoT)
- LoRaWAN
- Zigbee
- Z-Wave
- Thread
- Sigfox



- Virtualisation & Conteneurs

  - VMware vSphere, ESXi, Proxmox, KVM, Xen, Hyper-V
  - Docker, Podman, Buildah, Kaniko
  - Kubernetes, OpenShift, Rancher, Helm, Istio, Linkerd
  
- Cloud computing (IaaS)

  - AWS, Azure, GCP
  - Terraform, Ansible
  
- Services d’Annuaire & Gestion d’Identité

  - Active Directory (Microsoft)
  - LDAP : OpenLDAP, 389 Directory Server
  - FreeIPA
  - Azure AD

- Partage & Protocoles Réseau

  - Samba (partage fichiers Windows/Linux)
  - NFS (Network File System)
  - CIFS
  - FTP / SFTP / SCP

- Gestion de Configuration & Orchestration

  - Ansible
  - Puppet
  - Chef
  - SaltStack

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

  - SQL : Oracle, PostgreSQL, MySQL, MariaDB, MSSQL
  - NoSQL : MongoDB, CouchDB, Cassandra, DynamoDB, Redis, Neo4j
  - Streaming : Kafka, RabbitMQ, Pulsar

- Big Data et Data Enginnering 

  - Hadoop, Spark, Hive, Pig, Flink

- BI & DataViz

  - Power BI, Tableau, Superset, Grafana, Kibana, Looker

- Data Science & Machine Learning /Intelligence Artificielle

  - Environnement : Jupyter, RStudio, Colab, Anaconda, Spyder
  - Librairies : scikit-learn, TensorFlow, PyTorch, Keras, XGBoost, LightGBM
  - AutoML : H2O.ai, DataRobot, Azure AutoML

- ETL & Pipeline

  - Apache Airflow, NiFi, Talend, Pentaho

- MLOps

  - MLflow, Kubeflow, DVC, Seldon

- IA Avancée

  - Deep Learning, LLMs
  - Éthique de l’IA

---

## Cybersécurité & Confiance Numérique

- Concepts Fondamentaux :

  - Principes : CIA (Confidentialité, Intégrité, Disponibilité) 
  - AAA (Authentication, Authorization, Accounting)

- Sécurité Réseau & Applicative :

  - Pare-feu & Proxy : iptables, pfSense, OPNsense, IPFire, FortiGate, Palo Alto NGFW, Zscaler
  - IDS/IPS : Snort, Suricata, Zeek/Bro

  - VPN :
    - Entreprise : OpenVPN, WireGuard, IPsec, StrongSwan, Cisco AnyConnect, FortiClient
    - Grand public : ProtonVPN, NordVPN, ExpressVPN, Mullvad, TunnelBear

  - SIEM : Splunk, ELK Stack (ElasticSearch, Logstash, Kibana), Graylog, Wazuh, OSSEC

- PKI & Cryptographie :
  - Certificats SSL/TLS, OpenSSL, GPG, HashiCorp Vault, Keycloak
  - Autorités de Certification internes / publiques

- IAM & Gestion des Secrets :
  - CyberArk, HashiCorp Vault

- Gouvernance, Conformité & Audit :
  - ISO 27001, RGPD, SOC 2, PCI-DSS
  - Outils : OpenVAS, Lynis, Qualys, CIS Benchmarks

- Pentest & Red Team :
  - OS : Kali Linux, Parrot OS
  - Outils : Metasploit, Burp Suite, OWASP ZAP, Nikto, Nessus, Nmap, SQLmap, Hydra, John the Ripper, Hashcat, Aircrack-ng, Wifite

- Forensic & Analyse :
  - Outils : Autopsy, Volatility, FTK, Sleuth Kit, EnCase, Cellebrite
  - Réseau : Wireshark, tcpdump

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
  - Outils : Sparx Enterprise Architect, Bizzdesign, Orbus Software iServer, MEGA International

- IT Service Management (ITSM) :
  - Cadres : ITIL v4, COBIT
  - Outils : ServiceNow, Jira Service Management, BMC Remedy, Ivanti, ManageEngine ServiceDesk Plus

- Gestion de Projet :
  - Méthodologies : Prince2, PMP (PMI), CAPM, Scrum, Agile, Kanban
  - Outils : Microsoft Project, Jira, Asana, Trello, Monday.com, Wrike, ClickUp

- Continuité & Résilience :
  - Concepts : PCA (Plan de Continuité d’Activité), PRA (Plan de Reprise d’Activité)
  - Outils : Fusion Framework System, Archer Business Continuity, Continuity Logic, Castellan

- Conformité & Normes :
  - Normes : ISO 27001, ISO 22301, RGPD, SOC 2, PCI-DSS
  - Outils : OneTrust, RSA Archer, TrustArc, MetricStream

- Transformation Digitale :
  - Concepts : Urbanisation SI, Green IT & Sobriété Numérique
  - Outils : LeanIX, Planview, GreenIT.fr (ressources), EcoIndex

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

