---
title: Unterstützte Azure Resource Manager-Ressourcentypen
description: Stellen Sie eine Liste der Azure Resource Manager-Ressourcentypen bereit, die von Azure Resource Graph und dem Änderungsverlauf unterstützt werden.
ms.date: 02/04/2021
ms.topic: reference
ms.custom: generated
ms.openlocfilehash: 865aed468f8a6bcb848b77a82467efc2c531398b
ms.sourcegitcommit: f377ba5ebd431e8c3579445ff588da664b00b36b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 02/05/2021
ms.locfileid: "99594332"
---
# <a name="azure-resource-graph-table-and-resource-type-reference"></a>Azure Resource Graph-Tabelle und Ressourcentypreferenz

Azure Resource Graph unterstützt die folgenden **Ressourcentypen** von [Azure Resource Manager](../../../azure-resource-manager/management/overview.md). Jeder **Ressourcentyp** ist Teil einer **Tabelle** in Resource Graph.

## <a name="advisorresources"></a>advisorresources

- microsoft.advisor/configurations
- microsoft.advisor/recommendations
- microsoft.advisor/recommendations/suppressions
- microsoft.advisor/suppressions

## <a name="alertsmanagementresources"></a>alertsmanagementresources

- microsoft.alertsmanagement/alerts

## <a name="guestconfigurationresources"></a>guestconfigurationresources

- microsoft.guestconfiguration/guestconfigurationassignments

## <a name="maintenanceresources"></a>maintenanceresources

- microsoft.maintenance/configurationassignments
- microsoft.maintenance/updates

## <a name="patchassessmentresources"></a>patchassessmentresources

- microsoft.compute/virtualmachines/patchassessmentresults
- microsoft.compute/virtualmachines/patchassessmentresults/softwarepatches
- microsoft.hybridcompute/machines/patchassessmentresults
- microsoft.hybridcompute/machines/patchassessmentresults/softwarepatches

## <a name="patchinstallationresources"></a>patchinstallationresources

- microsoft.compute/virtualmachines/patchinstallationresults
- microsoft.compute/virtualmachines/patchinstallationresults/softwarepatches
- microsoft.hybridcompute/machines/patchinstallationresults
- microsoft.hybridcompute/machines/patchinstallationresults/softwarepatches

## <a name="policyresources"></a>policyresources

- microsoft.policyinsights/policystates

## <a name="recoveryservicesresources"></a>recoveryservicesresources

- microsoft.dataprotection/backupvaults/backupinstances
- microsoft.dataprotection/backupvaults/backupjobs
- microsoft.dataprotection/backupvaults/backuppolicies
- microsoft.recoveryservices/vaults/alerts
- Microsoft.RecoveryServices/vaults/backupFabrics/protectionContainers/protectedItems (Sicherungselemente)
- microsoft.recoveryservices/vaults/backupjobs
- microsoft.recoveryservices/vaults/backuppolicies

## <a name="resourcecontainers"></a>resourcecontainers

- microsoft.resources/subscriptions (Abonnements)
- Microsoft.Resources/subscriptions/resourceGroups (Ressourcengruppen)

## <a name="resources"></a>ressourcen

- 84codes.CloudAMQP/servers (CloudAMQP)
- Citrix.Services/XenAppEssentials (Citrix Virtual Apps Essentials)
- Citrix.Services/XenDesktopEssentials (Citrix Virtual Desktops Essentials)
- Conexlink.MyCloudIt/accounts (MyCloudIT – Azure-Desktophosting)
- Crypteron.DataSecurity/apps (Crypteron)
- gridpro.evops/accounts
- gridpro.evops/accounts/eventrules
- gridpro.evops/accounts/requesttemplates
- gridpro.evops/accounts/views
- Hive.Streaming/services (Hive-Streaming)
- incapsula.waf/accounts
- LiveArena.Broadcast/services (LiveArena-Broadcast)
- Mailjet.Email/services (Mailjet Email Service)
- Microsoft.AAD/domainServices (Azure AD Domain Services)
- microsoft.aadiam/azureadmetrics
- microsoft.aadiam/privateLinkForAzureAD (Private Link für Azure AD)
- microsoft.aadiam/tenants
- microsoft.agfoodplatform/farmbeats
- microsoft.aisupercomputer/accounts
- microsoft.aisupercomputer/accounts/jobgroups
- microsoft.aisupercomputer/accounts/jobgroups/jobs
- microsoft.alertsmanagement/actionrules
- microsoft.alertsmanagement/resourcehealthalertrules
- microsoft.alertsmanagement/smartdetectoralertrules
- Microsoft.AnalysisServices/servers (Analysis Services)
- microsoft.anybuild/clusters
- Microsoft.ApiManagement/service (API Management-Dienste)
- microsoft.appassessment/migrateprojects
- Microsoft.AppConfiguration/configurationStores (App Configuration)
- Microsoft.AppPlatform/Spring (Azure Spring Cloud)
- microsoft.archive/collections
- Microsoft.Attestation/attestationProviders (Nachweisanbieter)
- Microsoft.Authorization/resourceManagementPrivateLinks (private Ressourcenmanagementverbindung)
- microsoft.automanage/accounts
- microsoft.automanage/configurationprofilepreferences
- Microsoft.Automation/AutomationAccounts (Automation-Konten)
- microsoft.automation/automationaccounts/configurations
- Microsoft.Automation/automationAccounts/runbooks (Runbook)
- microsoft.autonomousdevelopmentplatform/accounts
- Microsoft.AutonomousSystems/workspaces (Bonsai)
- Microsoft.AVS/privateClouds (private AVS-Clouds)
- microsoft.azconfig/configurationstores
- Microsoft.AzureActiveDirectory/b2cDirectories (B2C-Mandanten)
- Microsoft.AzureActiveDirectory/guestUsages (Gastnutzung)
- Microsoft.AzureArcData/dataControllers (Azure Arc-Datencontroller)
- Microsoft.AzureArcData/postgresInstances (Azure Database for PostgreSQL-Servergruppen – Azure Arc)
- Microsoft.AzureArcData/sqlManagedInstances (SQL Managed Instance – Azure Arc)
- Microsoft.AzureArcData/sqlServerInstances (SQL Server – Azure Arc)
- microsoft.azuredata/datacontrollers
- microsoft.azuredata/hybriddatamanagers
- microsoft.azuredata/postgresinstances
- microsoft.azuredata/sqlbigdataclusters
- microsoft.azuredata/sqlinstances
- microsoft.azuredata/sqlmanagedinstances
- microsoft.azuredata/sqlserverinstances
- Microsoft.AzureData/sqlServerRegistrations (SQL Server-Registrierungen)
- microsoft.azurestack/edgesubscriptions
- microsoft.azurestack/linkedsubscriptions
- Microsoft.Azurestack/registrations (Azure Stack Hub)
- Microsoft.AzureStackHCI/clusters (Azure Stack HCI)
- microsoft.azurestackhci/galleryimages
- microsoft.azurestackhci/networkinterfaces
- microsoft.azurestackhci/virtualnetworks
- microsoft.baremetal/consoleconnections
- Microsoft.BareMetal/crayServers (Cray-Server)
- Microsoft.BareMetal/monitoringServers (Überwachungsserver)
- Microsoft.BareMetalInfrastructure/bareMetalInstances (BareMetal-Instanzen)
- Microsoft.Batch/batchAccounts (Batch-Konten)
- microsoft.batchai/clusters
- microsoft.batchai/fileservers
- microsoft.batchai/jobs
- microsoft.batchai/workspaces
- Microsoft.Bing/accounts (Bing-Ressourcen)
- Microsoft.BingMaps/mapApis (Bing Maps API for Enterprise)
- microsoft.biztalkservices/biztalk
- Microsoft.Blockchain/blockchainMembers (Azure Blockchain-Dienst)
- Microsoft.Blockchain/cordaMembers (Corda)
- Microsoft.Blockchain/watchers (Blockchain Data Manager)
- Microsoft.BotService/botServices (Bot Service)
- Microsoft.Cache/Redis (Azure Cache for Redis)
- Microsoft.Cache/RedisEnterprise (Redis Enterprise)
- Microsoft.Cdn/CdnWebApplicationFirewallPolicies (Web Application Firewall-Richtlinien (WAF))
- microsoft.cdn/profiles (CDN-Profile)
- microsoft.cdn/profiles/afdendpoints
- microsoft.cdn/profiles/endpoints (Endpunkte)
- Microsoft.CertificateRegistration/certificateOrders (App Service Certificate)
- microsoft.chaos/chaosexperiments
- microsoft.classicCompute/domainNames (Clouddienste (klassisch))
- Microsoft.ClassicCompute/VirtualMachines (VMs (klassisch))
- Microsoft.ClassicNetwork/networkSecurityGroups (Netzwerksicherheitsgruppe (klassisch))
- Microsoft.ClassicNetwork/reservedIps (IP-Reservierung (klassisch))
- Microsoft.ClassicNetwork/virtualNetworks (virtuelle Netzwerke (klassisch))
- Microsoft.ClassicStorage/StorageAccounts (Speicherkonten (klassisch))
- microsoft.cloudes/accounts
- microsoft.cloudsearch/indexes
- Microsoft.CloudTest/accounts (CloudTest-Konten)
- Microsoft.CloudTest/hostedpools (gehostete 1ES-Pools)
- Microsoft.CloudTest/images (CloudTest-Images)
- Microsoft.CloudTest/pools (CloudTest-Pools)
- microsoft.codespaces/plans
- Microsoft.Cognition/syntheticsAccounts (Synthetics-Konten)
- Microsoft.CognitiveServices/accounts (Cognitive Services)
- Microsoft.Compute/availabilitySets (Verfügbarkeitsgruppen)
- microsoft.compute/capacityreservationgroups
- microsoft.compute/capacityreservationgroups/capacityreservations
- microsoft.compute/capacityreservations
- Microsoft.Compute/cloudServices (Clouddienste (erweiterter Support))
- Microsoft.Compute/diskAccesses (Datenträgerzugriffe)
- Microsoft.Compute/diskEncryptionSets (Datenträgerverschlüsselungssätze)
- Microsoft.Compute/disks (Datenträger)
- Microsoft.Compute/galleries (Kataloge mit freigegebenen Images)
- microsoft.compute/galleries/applications
- microsoft.compute/galleries/applications/versions
- Microsoft.Compute/galleries/images (Imagedefinitionen)
- Microsoft.Compute/galleries/images/versions (Imageversionen)
- Microsoft.Compute/hostgroups (Hostgruppen)
- Microsoft.Compute/hostgroups/hosts (Hosts)
- Microsoft.Compute/images (Images)
- Microsoft.Compute/ProximityPlacementGroups (Näherungsplatzierungsgruppen)
- microsoft.compute/restorepointcollections
- microsoft.compute/sharedvmextensions
- microsoft.compute/sharedvmextensions/versions
- microsoft.compute/sharedvmimages
- microsoft.compute/sharedvmimages/versions
- Microsoft.Compute/snapshots (Momentaufnahmen)
- Microsoft.Compute/sshPublicKeys (SSH-Schlüssel)
- microsoft.compute/swiftlets
- Microsoft.Compute/VirtualMachines (VMs)
- microsoft.compute/virtualmachines/extensions
- microsoft.compute/virtualmachines/runcommands
- Microsoft.Compute/virtualMachineScaleSets (VM-Skalierungsgruppen)
- Microsoft.Confluent/organizations (Confluent-Organisationen)
- Microsoft.ConnectedCache/cacheNodes (Connected Cache-Ressourcen)
- microsoft.connectedvehicle/platformaccounts
- Microsoft.ContainerInstance/containerGroups (Containerinstanzen)
- Microsoft.ContainerRegistry/registries (Containerregistrierungen)
- microsoft.containerregistry/registries/agentpools
- microsoft.containerregistry/registries/buildtasks
- Microsoft.ContainerRegistry/registries/replications (Replikationen von Containerregistrierungen)
- microsoft.containerregistry/registries/taskruns
- microsoft.containerregistry/registries/tasks
- Microsoft.ContainerRegistry/registries/webhooks (Webhooks für Containerregistrierungen)
- Microsoft.ContainerService/containerServices (Containerdienste (veraltet))
- Microsoft.ContainerService/managedClusters (Kubernetes-Dienste)
- microsoft.containerservice/openshiftmanagedclusters
- microsoft.contoso/clusters
- microsoft.contoso/employees
- microsoft.contoso/towers
- microsoft.costmanagement/connectors
- microsoft.customproviders/resourceproviders
- microsoft.d365customerinsights/instances
- Microsoft.DataBox/jobs (Data Box)
- Microsoft.DataBoxEdge/dataBoxEdgeDevices (Azure Stack Edge/Data Box Gateway)
- Microsoft.Databricks/workspaces (Azure Databricks-Dienste)
- Microsoft.DataCatalog/catalogs (Data Catalog)
- microsoft.datacatalog/datacatalogs
- Microsoft.DataCollaboration/workspaces (Datenzusammenarbeit)
- Microsoft.Datadog/monitors (Datadog)
- Microsoft.DataFactory/dataFactories (Data Factorys)
- Microsoft.DataFactory/factories (Data Factorys (V2))
- Microsoft.DataLakeAnalytics/accounts (Data Lake Analytics)
- Microsoft.DataLakeStore/accounts (Data Lake Storage Gen1)
- microsoft.datamigration/controllers
- Microsoft.DataMigration/services (Azure Database Migration Service)
- Microsoft.DataMigration/services/projects (Azure-Datenbankmigrationsprojekte)
- microsoft.datamigration/slots
- Microsoft.DataProtection/BackupVaults (Sicherungstresore)
- microsoft.dataprotection/resourceoperationgatekeepers
- Microsoft.DataShare/accounts (Datenfreigaben)
- Microsoft.DBforMariaDB/servers (Azure Database for MariaDB-Server)
- Microsoft.DBforMySQL/flexibleServers (flexible Azure Database for MySQL-Server)
- Microsoft.DBforMySQL/servers (Azure Database for MySQL-Server)
- Microsoft.DBforPostgreSQL/flexibleServers (flexible Azure Database for PostgreSQL-Server)
- Microsoft.DBforPostgreSQL/serverGroups (Azure Database for PostgreSQL-Servergruppen)
- Microsoft.DBforPostgreSQL/servers (Azure Database for PostgreSQL-Server)
- Microsoft.DBforPostgreSQL/serversv2 (Azure Database for PostgreSQL-Server v2)
- microsoft.dbforpostgresql/singleservers
- microsoft.delegatednetwork/controller
- microsoft.delegatednetwork/delegatedsubnets
- microsoft.delegatednetwork/orchestratorinstances
- microsoft.deploymentmanager/artifactsources
- Microsoft.DeploymentManager/Rollouts (Rollouts)
- microsoft.deploymentmanager/servicetopologies
- microsoft.deploymentmanager/servicetopologies/services
- microsoft.deploymentmanager/servicetopologies/services/serviceunits
- microsoft.deploymentmanager/steps
- Microsoft.DesktopVirtualization/ApplicationGroups (Anwendungsgruppen)
- Microsoft.DesktopVirtualization/HostPools (Hostpools)
- microsoft.desktopvirtualization/scalingplans
- Microsoft.DesktopVirtualization/Workspaces (Arbeitsbereiche)
- microsoft.devices/elasticpools
- microsoft.devices/elasticpools/iothubtenants
- Microsoft.Devices/IotHubs (IoT Hub)
- Microsoft.Devices/ProvisioningServices (Device Provisioning Service)
- Microsoft.DeviceUpdate/Accounts (Geräteupdate für IoT-Hubs)
- microsoft.deviceupdate/accounts/instances
- microsoft.devops/pipelines (DevOps Starter)
- microsoft.devspaces/controllers
- microsoft.devtestlab/labcenters
- Microsoft.DevTestLab/labs (DevTest Labs)
- microsoft.devtestlab/labs/servicerunners
- Microsoft.DevTestLab/labs/virtualMachines (VMs)
- microsoft.devtestlab/schedules
- Microsoft.DigitalTwins/digitalTwinsInstances (Azure Digital Twins)
- Microsoft.DocumentDb/databaseAccounts (Azure Cosmos DB-Konten)
- Microsoft.DomainRegistration/domains (App Service-Domänen)
- Microsoft.Elastic/monitors (elastisch)
- microsoft.enterpriseknowledgegraph/services
- Microsoft.EventGrid/domains (Event Grid-Domänen)
- Microsoft.EventGrid/partnerNamespaces (Event Grid-Partnernamespaces)
- Microsoft.EventGrid/partnerRegistrations (Event Grid-Partnerregistrierungen)
- Microsoft.EventGrid/partnerTopics (Event Grid-Partnerthemen)
- Microsoft.EventGrid/systemTopics (Event Grid-Systemthemen)
- Microsoft.EventGrid/topics (Event Grid-Themen)
- Microsoft.EventHub/clusters (Event Hubs-Cluster)
- Microsoft.EventHub/namespaces (Event Hubs-Namespaces)
- Microsoft.Experimentation/experimentWorkspaces (Experimentarbeitsbereiche)
- Microsoft.ExtendedLocation/CustomLocations (benutzerdefinierte Standorte)
- microsoft.falcon/namespaces
- microsoft.footprintmonitoring/profiles
- microsoft.gaming/titles
- Microsoft.Genomics/accounts (Genomics-Konten)
- microsoft.guestconfiguration/automanagedaccounts
- Microsoft.HanaOnAzure/hanaInstances (SAP HANA in Azure)
- Microsoft.HanaOnAzure/sapMonitors (Azure Monitor für SAP-Lösungen)
- microsoft.hardwaresecuritymodules/dedicatedhsms
- Microsoft.HDInsight/clusters (HDInsight-Cluster)
- Microsoft.HealthBot/healthBots (Azure Health Bot)
- Microsoft.HealthcareApis/services (Azure API for FHIR)
- microsoft.healthcareapis/services/privateendpointconnections
- microsoft.healthcareapis/workspaces
- microsoft.healthcareapis/workspaces/dicomservices
- Microsoft.HybridCompute/machines (Server – Azure Arc)
- microsoft.hybridcompute/machines/extensions
- Microsoft.HybridCompute/privateLinkScopes (Azure Arc: Private Link-Bereiche)
- Microsoft.HybridData/dataManagers (StorSimple Data Manager)
- Microsoft.HybridNetwork/devices (Azure-Netzwerkfunktions-Manager – Geräte)
- Microsoft.HybridNetwork/networkFunctions (Azure-Netzwerkfunktions-Manager – Netzwerkfunktionen)
- microsoft.hybridnetwork/virtualnetworkfunctions
- Microsoft.ImportExport/jobs (Import-/Exportaufträge)
- microsoft.industrydatalifecycle/basemodels
- microsoft.industrydatalifecycle/custodiancollaboratives
- microsoft.industrydatalifecycle/derivedmodels
- microsoft.industrydatalifecycle/membercollaboratives
- microsoft.industrydatalifecycle/modelmappings
- microsoft.industrydatalifecycle/pipelinesets
- microsoft.insights/actiongroups
- microsoft.insights/activitylogalerts
- microsoft.insights/alertrules
- microsoft.insights/autoscalesettings
- microsoft.insights/components (Application Insights)
- microsoft.insights/datacollectionrules (Datensammlungsregeln)
- microsoft.insights/guestdiagnosticsettings
- microsoft.insights/metricalerts
- microsoft.insights/notificationgroups
- microsoft.insights/notificationrules
- Microsoft.Insights/privateLinkScopes (Azure Monitor: Private Link-Bereiche)
- microsoft.insights/querypacks
- microsoft.insights/scheduledqueryrules
- microsoft.insights/webtests (Verfügbarkeitstests)
- microsoft.insights/workbooks (Azure-Arbeitsmappen)
- microsoft.insights/workbooktemplates (Vorlagen für Azure-Arbeitsmappen)
- Microsoft.IntelligentITDigitalTwin/digitalTwins (Minervas)
- microsoft.intelligentitdigitaltwin/digitaltwins/assets
- microsoft.intelligentitdigitaltwin/digitaltwins/executionplans
- microsoft.intelligentitdigitaltwin/digitaltwins/testplans
- microsoft.intelligentitdigitaltwin/digitaltwins/tests
- Microsoft.IoTCentral/IoTApps (IoT Central-Anwendungen)
- Microsoft.IoTSpaces/Graph (Digital Twins (veraltet))
- microsoft.keyvault/hsmpools
- microsoft.keyvault/managedhsms
- Microsoft.KeyVault/vaults (Schlüsseltresore)
- Microsoft.Kubernetes/connectedClusters (Kubernetes – Azure Arc)
- Microsoft.Kusto/clusters (Azure Data Explorer-Cluster)
- Microsoft.Kusto/clusters/databases (Azure Data Explorer-Datenbanken)
- Microsoft.LabServices/labAccounts (Lab Services)
- Microsoft.LoadTestService/LoadTests (cloudnative Auslastungstests)
- Microsoft.Logic/integrationAccounts (Integrationskonten)
- Microsoft.Logic/integrationServiceEnvironments (Integrationsdienstumgebungen)
- Microsoft.Logic/integrationServiceEnvironments/managedApis (verwalteter Connector)
- Microsoft.Logic/workflows (Logik-Apps)
- Microsoft.Logz/monitors (Logz-Hauptkonto)
- Microsoft.Logz/monitors/accounts (Logz-Unterkonto)
- Microsoft.MachineLearning/commitmentPlans (Machine Learning Studio (klassisch): Webdienstpläne)
- Microsoft.MachineLearning/webServices (Machine Learning Studio (klassisch): Webdienste)
- Microsoft.MachineLearning/workspaces (Machine Learning Studio (klassisch): Arbeitsbereiche)
- microsoft.machinelearningcompute/operationalizationclusters
- microsoft.machinelearningservices/modelinventories
- microsoft.machinelearningservices/modelinventory
- Microsoft.MachineLearningServices/workspaces (Machine Learning)
- microsoft.machinelearningservices/workspaces/batchendpoints
- microsoft.machinelearningservices/workspaces/batchendpoints/deployments
- microsoft.machinelearningservices/workspaces/inferenceendpoints
- microsoft.machinelearningservices/workspaces/inferenceendpoints/deployments
- Microsoft.MachineLearningServices/workspaces/onlineEndpoints (ML-Apps)
- Microsoft.MachineLearningServices/workspaces/onlineEndpoints/deployments (ML-App-Entwicklung)
- Microsoft.Maintenance/maintenanceConfigurations (Wartungskonfigurationen)
- microsoft.maintenance/maintenancepolicies
- microsoft.managedidentity/groups
- Microsoft.ManagedIdentity/userAssignedIdentities (verwaltete Identitäten)
- microsoft.managednetwork/managednetworkgroups
- microsoft.managednetwork/managednetworkpeeringpolicies
- microsoft.managednetwork/managednetworks
- microsoft.managednetwork/managednetworks/managednetworkgroups
- microsoft.managednetwork/managednetworks/managednetworkpeeringpolicies
- Microsoft.Maps/accounts (Azure Maps-Konten)
- microsoft.maps/accounts/creators
- Microsoft.Maps/accounts/privateAtlases (Azure Maps Creator-Ressourcen)
- Microsoft.MarketplaceApps/classicDevServices (klassische Entwicklungsdienste)
- microsoft.media/mediaservices (Media Services)
- microsoft.media/mediaservices/liveevents (Liveereignisse)
- microsoft.media/mediaservices/streamingEndpoints (Streamingendpunkte)
- microsoft.media/mediaservices/transforms
- microsoft.microservices4spring/appclusters
- microsoft.migrate/assessmentprojects
- microsoft.migrate/migrateprojects
- microsoft.migrate/movecollections
- Microsoft.Migrate/projects (Migrationsprojekte)
- Microsoft.MixedReality/holographicsBroadcastAccounts (Holographics Broadcast-Konten)
- Microsoft.MixedReality/objectUnderstandingAccounts (Object Understanding-Konten)
- Microsoft.MixedReality/remoteRenderingAccounts (Remote Rendering-Konten)
- Microsoft.MixedReality/spatialAnchorsAccounts (Spatial Anchors-Konten)
- microsoft.mixedreality/surfacereconstructionaccounts
- Microsoft.NetApp/netAppAccounts (NetApp-Konten)
- microsoft.netapp/netappaccounts/backuppolicies
- Microsoft.NetApp/netAppAccounts/capacityPools (Kapazitätspools)
- Microsoft.NetApp/netAppAccounts/capacityPools/Volumes (Volumes)
- microsoft.netapp/netappaccounts/capacitypools/volumes/mounttargets
- Microsoft.NetApp/netAppAccounts/capacityPools/volumes/snapshots (Momentaufnahmen)
- Microsoft.Network/applicationGateways (Anwendungsgateways)
- Microsoft.Network/ApplicationGatewayWebApplicationFirewallPolicies (Web Application Firewall-Richtlinien (WAF))
- Microsoft.Network/applicationSecurityGroups (Anwendungssicherheitsgruppen)
- Microsoft.Network/azureFirewalls (Firewalls)
- Microsoft.Network/bastionHosts (Bastion)
- Microsoft.Network/connections (Verbindungen)
- microsoft.network/customipprefixes
- microsoft.network/ddoscustompolicies
- Microsoft.Network/ddosProtectionPlans (DDoS-Schutzpläne)
- Microsoft.Network/dnsZones (DNS-Zonen)
- microsoft.network/dscpconfigurations
- Microsoft.Network/expressRouteCircuits (ExpressRoute-Leitungen)
- microsoft.network/expressroutecrossconnections
- microsoft.network/expressroutegateways
- Microsoft.Network/expressRoutePorts (ExpressRoute Direct)
- Microsoft.Network/firewallPolicies (Firewallrichtlinien)
- Microsoft.Network/frontdoors (Front Door)
- Microsoft.Network/FrontDoorWebApplicationFirewallPolicies (Web Application Firewall-Richtlinien (WAF))
- microsoft.network/ipallocations
- Microsoft.Network/ipGroups (IP-Gruppen)
- Microsoft.Network/LoadBalancers (Load Balancer)
- Microsoft.Network/localnetworkgateways (lokale Netzwerkgateways)
- microsoft.network/mastercustomipprefixes
- Microsoft.Network/natGateways (NAT-Gateways)
- Microsoft.Network/NetworkExperimentProfiles (Internet Analyzer-Profile)
- microsoft.network/networkintentpolicies
- Microsoft.Network/networkinterfaces (Netzwerkschnittstellen)
- Microsoft.Network/networkManagers (Netzwerk-Manager)
- microsoft.network/networkprofiles
- Microsoft.Network/NetworkSecurityGroups (Netzwerksicherheitsgruppen)
- microsoft.network/networkvirtualappliances
- microsoft.network/networkwatchers (Network Watcher)
- microsoft.network/networkwatchers/connectionmonitors
- microsoft.network/networkwatchers/flowlogs (NSG-Datenflussprotokolle)
- microsoft.network/networkwatchers/lenses
- microsoft.network/networkwatchers/pingmeshes
- microsoft.network/p2svpngateways
- Microsoft.Network/privateDnsZones (Privates DNS-Zonen)
- microsoft.network/privatednszones/virtualnetworklinks
- microsoft.network/privateendpointredirectmaps
- Microsoft.Network/privateEndpoints (private Endpunkte)
- Microsoft.Network/privateLinkServices (Private Link-Dienste)
- Microsoft.Network/PublicIpAddresses (öffentliche IP-Adressen)
- Microsoft.Network/publicIpPrefixes (öffentliche IP-Präfixe)
- Microsoft.Network/routeFilters (Routenfilter)
- Microsoft.Network/routeTables (Routingtabellen)
- microsoft.network/sampleresources
- microsoft.network/securitypartnerproviders
- Microsoft.Network/serviceEndpointPolicies (Dienstendpunktrichtlinien)
- Microsoft.Network/trafficmanagerprofiles (Traffic Manager-Profile)
- microsoft.network/virtualhubs
- microsoft.network/virtualhubs/bgpconnections
- microsoft.network/virtualhubs/ipconfigurations
- Microsoft.Network/virtualNetworkGateways (VNet-Gateways)
- Microsoft.Network/virtualNetworks (virtuelle Netzwerke)
- microsoft.network/virtualnetworktaps
- microsoft.network/virtualrouters
- Microsoft.Network/virtualWans (Virtual WAN)
- microsoft.network/vpngateways
- microsoft.network/vpnserverconfigurations
- microsoft.network/vpnsites
- Microsoft.NotificationHubs/namespaces (Notification Hub-Namespaces)
- Microsoft.NotificationHubs/namespaces/notificationHubs (Notification Hub)
- microsoft.nutanix/interfaces
- microsoft.nutanix/nodes
- microsoft.objectstore/osnamespaces
- microsoft.offazure/hypervsites
- microsoft.offazure/importsites
- microsoft.offazure/mastersites
- microsoft.offazure/serversites
- microsoft.offazure/vmwaresites
- Microsoft.OpenLogisticsPlatform/workspaces (Open Supply Chain-Plattform)
- microsoft.operationalinsights/clusters
- Microsoft.OperationalInsights/querypacks (Log Analytics-Abfragepakete)
- Microsoft.OperationalInsights/workspaces (Log Analytics-Arbeitsbereiche)
- Microsoft.OperationsManagement/solutions (Lösungen)
- microsoft.operationsmanagement/views
- microsoft.orbital/contactprofiles
- microsoft.orbital/spacecrafts
- Microsoft.Peering/peerings (Peerings)
- Microsoft.Peering/peeringServices (Peering Service)
- Microsoft.Portal/dashboards (freigegebene Dashboards)
- microsoft.portalsdk/rootresources
- microsoft.powerbi/privatelinkservicesforpowerbi
- microsoft.powerbi/tenants
- microsoft.powerbi/workspacecollections
- Microsoft.PowerBIDedicated/capacities (Power BI Embedded)
- Microsoft.ProjectBabylon/Accounts (Babylon-Konten)
- Microsoft.Purview/Accounts (Purview-Konten)
- Microsoft.Quantum/Workspaces (Quantum-Arbeitsbereiche)
- Microsoft.RecoveryServices/vaults (Recovery Services-Tresore)
- Microsoft.RedHatOpenShift/openShiftClusters (OpenShift-Cluster)
- Microsoft.Relay/namespaces (Relays)
- microsoft.remoteapp/collections
- microsoft.resiliency/chaosexperiments
- microsoft.resourceconnector/appliances
- Microsoft.resourcegraph/queries (Resource Graph-Abfragen)
- Microsoft.Resources/deploymentScripts (Bereitstellungsskripts)
- Microsoft.Resources/templateSpecs (Vorlagenspezifikationen)
- microsoft.resources/templatespecs/versions
- Microsoft.SaaS/applications (Software-as-a-Service (SaaS, klassisch))
- Microsoft.SaaS/resources (CPX-Platzhalter)
- Microsoft.Scheduler/jobCollections (Scheduler-Auftragssammlungen)
- microsoft.scvmm/clouds
- Microsoft.scvmm/virtualMachines (SCVMM-VM – Azure Arc)
- microsoft.scvmm/virtualmachinetemplates
- microsoft.scvmm/virtualnetworks
- microsoft.scvmm/vmmservers
- Microsoft.Search/searchServices (Suchdienste)
- microsoft.security/automations
- microsoft.security/iotsecuritysolutions
- Microsoft.SecurityDetonation/chambers (Sicherheitsdetonationskammern)
- Microsoft.ServiceBus/namespaces (Service Bus-Namespaces)
- Microsoft.ServiceFabric/clusters (Service Fabric-Cluster)
- microsoft.servicefabric/containergroupsets
- Microsoft.ServiceFabric/managedclusters (verwaltete Service Fabric-Cluster)
- Microsoft.ServiceFabricMesh/applications (Gitteranwendungen)
- microsoft.servicefabricmesh/gateways
- microsoft.servicefabricmesh/networks
- microsoft.servicefabricmesh/secrets
- microsoft.servicefabricmesh/volumes
- Microsoft.ServicesHub/connectors (Services Hub-Connectors)
- Microsoft.SignalRService/SignalR (SignalR)
- microsoft.singularity/accounts
- microsoft.solutions/appliancedefinitions
- microsoft.solutions/appliances
- Microsoft.Solutions/applicationDefinitions (Dienstkatalog: verwaltete Anwendungsdefinitionen)
- Microsoft.Solutions/applications (verwaltete Anwendungen)
- microsoft.solutions/jitrequests
- microsoft.spoolservice/spools
- Microsoft.Sql/instancePools (Instanzenpools)
- Microsoft.Sql/managedInstances (SQL Managed Instance)
- Microsoft.Sql/managedInstances/databases (verwaltete Datenbanken)
- Microsoft.Sql/servers (SQL-Server)
- Microsoft.Sql/servers/databases (SQL-Datenbanken)
- Microsoft.Sql/servers/elasticpools (elastische SQL-Pools)
- microsoft.sql/servers/jobaccounts
- Microsoft.Sql/servers/jobAgents (Agent für elastische Aufträge)
- Microsoft.Sql/virtualClusters (virtuelle Cluster)
- microsoft.sqlvirtualmachine/sqlvirtualmachinegroups
- Microsoft.SqlVirtualMachine/SqlVirtualMachines (SQL-VMs)
- microsoft.sqlvm/dwvm
- Microsoft.Storage/StorageAccounts (Speicherkonten)
- Microsoft.StorageCache/caches (HPC-Caches)
- microsoft.storagepool/diskpools
- Microsoft.StorageSync/storageSyncServices (Storage-Synchronisierungsdienste)
- Microsoft.StorageSyncDev/storageSyncServices (Storage-Synchronisierungsdienste)
- Microsoft.StorageSyncInt/storageSyncServices (Storage-Synchronisierungsdienste)
- Microsoft.StorSimple/Managers (StorSimple-Geräte-Manager)
- Microsoft.StreamAnalytics/clusters (Stream Analytics-Cluster)
- Microsoft.StreamAnalytics/StreamingJobs (Stream Analytics-Aufträge)
- microsoft.swiftlet/virtualmachines
- microsoft.swiftlet/virtualmachinesnapshots
- Microsoft.Synapse/privateLinkHubs (Azure Synapse Analytics (Private Link-Hubs))
- Microsoft.Synapse/workspaces (Azure Synapse Analytics)
- Microsoft.Synapse/workspaces/bigDataPools (Apache Spark-Pools)
- microsoft.synapse/workspaces/sqldatabases
- Microsoft.Synapse/workspaces/sqlPools (dedizierte SQL-Pools)
- microsoft.terraformoss/providerregistrations
- Microsoft.TimeSeriesInsights/environments (Time Series Insights-Umgebungen)
- Microsoft.TimeSeriesInsights/environments/eventsources (Time Series Insights-Ereignisquellen)
- Microsoft.TimeSeriesInsights/environments/referenceDataSets (Time Series Insights-Referenzdatasets)
- microsoft.token/stores
- microsoft.tokenvault/vaults
- microsoft.virtualmachineimages/imagetemplates
- microsoft.visualstudio/account (Azure DevOps-Organisationen)
- microsoft.visualstudio/account/extension
- microsoft.visualstudio/account/project (DevOps-Starter)
- microsoft.vmware/arczones
- microsoft.vmware/resourcepools
- microsoft.vmware/vcenters
- Microsoft.VMware/VirtualMachines (AVS-VMs)
- microsoft.vmware/virtualmachinetemplates
- microsoft.vmware/virtualnetworks
- Microsoft.VMwareCloudSimple/dedicatedCloudNodes (CloudSimple-Knoten)
- Microsoft.VMwareCloudSimple/dedicatedCloudServices (CloudSimple-Dienste)
- Microsoft.VMwareCloudSimple/virtualMachines (CloudSimple-VMs)
- microsoft.vmwareonazure/privateclouds
- microsoft.vmwarevirtustream/privateclouds
- microsoft.vsonline/accounts
- Microsoft.VSOnline/Plans (Visual Studio-Onlinepläne)
- microsoft.web/apimanagementaccounts
- microsoft.web/apimanagementaccounts/apis
- microsoft.web/certificates
- Microsoft.Web/connectionGateways (lokale Datengateways)
- Microsoft.Web/connections (API-Verbindungen)
- Microsoft.Web/customApis (benutzerdefinierter Logic Apps-Connector)
- Microsoft.Web/HostingEnvironments (App Service-Umgebungen)
- Microsoft.Web/KubeEnvironments (App Service-Kubernetes-Umgebungen)
- Microsoft.Web/serverFarms (App Service-Pläne)
- Microsoft.Web/sites (App Services)
- microsoft.web/sites/premieraddons
- Microsoft.Web/sites/slots (App Service (Slots))
- Microsoft.Web/StaticSites (Static Web Apps (Vorschau))
- Microsoft.WindowsESU/multipleActivationKeys (Windows-Mehrfachaktivierungsschlüssel)
- Microsoft.WindowsIoT/DeviceServices (Windows 10 IoT Core Services)
- microsoft.workloadbuilder/migrationagents
- microsoft.workloadbuilder/workloads
- MyGet.PackageManagement/services (MyGet – NuGet, NPM, Bower und Vsix gehostet)
- Paraleap.CloudMonix/services (CloudMonix)
- Pokitdok.Platform/services (PokitDok-Plattform)
- Providers.Test/statefulIbizaEngines (Anwendungsbewertungen)
- providers.test/statefulresources
- providers.test/statefulresources/nestedresources
- providers.test/statelessresources
- RavenHq.Db/databases (RavenHQ)
- Raygun.CrashReporting/apps (Raygun)
- Sendgrid.Email/accounts (SendGrid-Konten)
- Sparkpost.Basic/services (SparkPost)
- stackify.retrace/services (Stackify)
- test.shoebox/testresources
- test.shoebox/testresources2
- TrendMicro.DeepSecurity/accounts (Deep Security SaaS)
- U2uconsult.TheIdentityHub/services (The Identity Hub)
- Wandisco.Fusion/fusionGroups (LiveData Planes)
- Wandisco.Fusion/fusionGroups/azureZones (Azure-Zonen)
- Wandisco.Fusion/fusionGroups/azureZones/plugins (Plug-Ins)
- Wandisco.Fusion/fusionGroups/hiveReplicationRules (Hive-Replikationsregeln)
- Wandisco.Fusion/fusionGroups/managedOnPremZones (lokale Zonen)
- wandisco.fusion/fusiongroups/onpremzones
- Wandisco.Fusion/fusionGroups/replicationRules (Replikationsregeln)
- Wandisco.Fusion/migrators (LiveData-Migrationen)
- Wandisco.Fusion/migrators/liveDataMigrations (Migrationen)
- Wandisco.Fusion/migrators/targets (Ziele)

## <a name="securityresources"></a>securityresources

- microsoft.security/assessments
- microsoft.security/assessments/subassessments
- microsoft.security/locations/alerts (Sicherheitswarnungen (Vorschau))
- microsoft.security/pricings
- microsoft.security/regulatorycompliancestandards
- microsoft.security/regulatorycompliancestandards/regulatorycompliancecontrols
- microsoft.security/regulatorycompliancestandards/regulatorycompliancecontrols/regulatorycomplianceassessments
- microsoft.security/securescores
- microsoft.security/securescores/securescorecontrols

## <a name="servicehealthresources"></a>servicehealthresources

- microsoft.resourcehealth/events

## <a name="next-steps"></a>Nächste Schritte

- Erfahren Sie mehr über die [Abfragesprache](../concepts/query-language.md).
- Erfahren Sie mehr über das [Erkunden von Ressourcen](../concepts/explore-resources.md).
- Sehen Sie sich Beispiele für [einfache Abfragen](../samples/starter.md) an.
