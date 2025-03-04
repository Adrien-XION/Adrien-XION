# Outils de Cybersécurité et Conformité ISO 27001
## Guide d'implémentation adapté à la taille des entreprises

### Introduction
- **Panorama des outils essentiels de cybersécurité**
- **Correspondance avec la norme ISO 27001:2022**
- **Recommandations adaptées selon la taille de l'entreprise**
- **Guide d'implémentation pratique**

---

### Protection des Terminaux

#### EDR (Endpoint Detection and Response)
- **Outil de référence**: Microsoft Defender for Endpoint
- **Référence ISO 27001**: A.8.16 (Activités de surveillance)
- **Mesures associées**: A.5.7, A.8.7, A.8.15, A.5.25
- **Recommandation**:
  - Grandes et moyennes entreprises: Indispensable
  - Petites entreprises: Utile

#### Guide Hygiène ANSSI: #14
- Mettre en place un niveau de sécurité minimal sur l'ensemble du parc informatique

---

### Surveillance et Détection

#### SIEM (Security Information & Event Management)
- **Outil de référence**: SPLUNK, Zabbix
- **Référence ISO 27001**: A.8.15 (Journalisation)
- **Mesures associées**: A.8.16, A.8.17, A.5.25, A.6.8
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes entreprises: Utile
  - Petites entreprises: Inadapté

#### Guide Hygiène ANSSI: #36
- Activer et configurer les journaux des composants les plus importants

---

### Sécurité du Périmètre

#### Pare-feu
- **Outil de référence**: Stormshield, Fortinet
- **Référence ISO 27001**: A.8.20 (Sécurité des réseaux)
- **Mesures associées**: A.8.21, A.8.22, A.8.23, A.5.37
- **Recommandation**: Indispensable pour toutes les entreprises

#### Guide Hygiène ANSSI: #17
- Activer et configurer le pare-feu local des postes de travail

---

### Systèmes de Détection d'Intrusion

#### IDS/IPS
- **Outil de référence**: Snort, Suricata
- **Référence ISO 27001**: A.8.25 (Cycle de vie de développement sécurisé)
- **Mesures associées**: A.8.19, A.8.9, A.8.32, A.5.37
- **Recommandation**:
  - Grandes et moyennes entreprises: Indispensable
  - Petites entreprises: Confort

#### Guide Hygiène ANSSI: #25
- Sécuriser les interconnexions réseau dédiées avec les partenaires

---

### Protection des Applications Web

#### WAF (Web Application Firewall)
- **Outil de référence**: AWS WAF, Cloudflare WAF
- **Référence ISO 27001**: A.8.16 (Activités de surveillance)
- **Mesures associées**: A.5.7, A.8.15, A.5.25, A.5.26
- **Recommandation**: Utile pour grandes et moyennes entreprises, Confort pour petites

#### Guide Hygiène ANSSI: #23
- Cloisonner les services visibles depuis Internet du reste du système d'information

---

### Audit et Conformité

#### Outils d'Audit
- **Outil de référence**: OpenScap
- **Référence ISO 27001**: A.5.36 (Conformité aux politiques)
- **Mesures associées**: A.5.35, A.9.2, A.9.1, A.8.29
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes et petites entreprises: Utile

#### Guide Hygiène ANSSI: #38
- Procéder à des contrôles et audits de sécurité réguliers

---

### Développement Sécurisé

#### CI/CD (Intégration/Déploiement Continu)
- **Outil de référence**: Trivy, SonarCube
- **Référence ISO 27001**: A.8.25 (Cycle de vie de développement sécurisé)
- **Mesures associées**: A.8.26, A.8.28, A.8.29, A.8.32
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes entreprises: Utile
  - Petites entreprises: Confort

#### Guide Hygiène ANSSI: #34
- Définir une politique de mise à jour des composants du système d'information

---

### Infrastructure Résiliente

#### Virtualisation
- **Outil de référence**: vSphere, Proxmox
- **Référence ISO 27001**: A.8.32 (Gestion des changements)
- **Mesures associées**: A.5.23, A.8.14, A.8.9, A.8.22
- **Recommandation**:
  - Grandes et moyennes entreprises: Indispensable
  - Petites entreprises: Utile

#### Guide Hygiène ANSSI: #19
- Segmenter le réseau et mettre en place un cloisonnement entre ces zones

---

### Continuité d'Activité

#### Solutions de Sauvegarde
- **Outil de référence**: Veeam Replication Backup
- **Référence ISO 27001**: A.8.13 (Sauvegarde des informations)
- **Mesures associées**: A.8.14, A.5.30, A.8.10, A.5.29
- **Recommandation**: Indispensable pour toutes les entreprises

#### Guide Hygiène ANSSI: #37
- Définir et appliquer une politique de sauvegarde des composants critiques

---

### Autonomie Numérique

#### Auto-hébergement
- **Outil de référence**: iRedMail, NextCloud, GitLab, Terraform
- **Référence ISO 27001**: A.8.31 (Séparation des environnements)
- **Mesures associées**: A.8.27, A.8.9, A.8.6, A.5.30
- **Recommandation**:
  - Grandes entreprises: Utile
  - Moyennes et petites entreprises: Confort

#### Guide Hygiène ANSSI: #23
- Cloisonner les services visibles depuis Internet

---

### Gestion des Terminaux

#### UEM (Unified Endpoint Management)
- **Outil de référence**: IBM MaaS360, MobileIron, VMware Workspace ONE
- **Référence ISO 27001**: A.8.23 (Filtrage Internet)
- **Mesures associées**: A.8.1, A.5.18, A.5.15, A.6.7
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes entreprises: Utile
  - Petites entreprises: Inadapté

#### Guide Hygiène ANSSI: #30
- Prendre des mesures de sécurisation physique des terminaux nomades

---

### Travail à Distance Sécurisé

#### Sécurité Distante
- **Outil de référence**: Cisco AnyConnect, Fortinet FortiClient
- **Référence ISO 27001**: A.8.10 (Suppression d'information)
- **Mesures associées**: A.8.11, A.8.12, A.5.12, A.5.33
- **Recommandation**:
  - Grandes et moyennes entreprises: Indispensable
  - Petites entreprises: Utile

#### Guide Hygiène ANSSI: #32
- Sécuriser la connexion réseau des postes utilisés en situation de nomadisme

---

### Automatisation

#### Déploiement Automatique
- **Outil de référence**: MDT, Ansible
- **Référence ISO 27001**: A.8.21 (Sécurité des services réseau)
- **Mesures associées**: A.6.7, A.8.20, A.8.22, A.8.5
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes entreprises: Utile
  - Petites entreprises: Confort

#### Guide Hygiène ANSSI: #34
- Définir une politique de mise à jour des composants

---

### Sécurité Physique

#### Contrôle d'Accès Physique
- **Outil de référence**: Pyrescom
- **Référence ISO 27001**: A.7.4 (Surveillance de la sécurité physique)
- **Mesures associées**: A.7.2, A.7.1, A.7.3, A.7.6
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes et petites entreprises: Utile

#### Guide Hygiène ANSSI: #26
- Contrôler et protéger l'accès aux salles serveurs et aux locaux techniques

---

### Gestion des Identités

#### Annuaire d'Entreprise
- **Outil de référence**: LDAP, Active Directory
- **Référence ISO 27001**: A.8.17 (Synchronisation des horloges)
- **Mesures associées**: A.5.16, A.5.17, A.5.18, A.5.15
- **Recommandation**:
  - Grandes et moyennes entreprises: Indispensable
  - Petites entreprises: Utile

#### Guide Hygiène ANSSI: #5
- Disposer d'un inventaire exhaustif des comptes privilégiés

---

### Contrôle des Accès Réseau

#### Solutions NAC
- **Outil de référence**: NAC, Bastion, RADIUS
- **Référence ISO 27001**: A.8.19 (Installation de logiciels)
- **Mesures associées**: A.8.20, A.8.22, A.8.5, A.8.2
- **Recommandation**:
  - Grandes et moyennes entreprises: Indispensable
  - Petites entreprises: Utile

#### Guide Hygiène ANSSI: #21
- Utiliser des protocoles sécurisés dès qu'ils existent

---

### Gestion des Incidents

#### Système de Ticketing
- **Outil de référence**: GLPI, SimplyDesk
- **Référence ISO 27001**: A.5.36 (Conformité aux politiques)
- **Mesures associées**: A.5.24, A.5.26, A.5.27, A.6.8
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes entreprises: Utile
  - Petites entreprises: Confort

#### Guide Hygiène ANSSI: #40
- Définir une procédure de gestion des incidents de sécurité

---

### Sécurité des Communications

#### Gestion des Certificats
- **Outil de référence**: Certbot, ACME.sh
- **Référence ISO 27001**: A.8.28 (Codage sécurisé)
- **Mesures associées**: A.8.24, A.5.17, A.8.5, A.5.33
- **Recommandation**:
  - Grandes entreprises: Indispensable
  - Moyennes entreprises: Utile
  - Petites entreprises: Confort

#### Guide Hygiène ANSSI: #13
- Privilégier lorsque c'est possible une authentification forte

---

### Infrastructure à Clé Publique

#### Autorité de Certification (CA) Interne
- **Outil de référence**: Dogtag PKI, EJBCA
- **Référence ISO 27001**: A.8.28 (Codage sécurisé)
- **Mesures associées**: A.8.24, A.8.27, A.5.15, A.5.14
- **Recommandation**: Indispensable pour toutes les entreprises

#### Guide Hygiène ANSSI: #13
- Privilégier lorsque c'est possible une authentification forte
