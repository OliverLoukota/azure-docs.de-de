---
title: Regionale Verfügbarkeit und Datenresidenz
titleSuffix: Azure AD B2C
description: Hier finden Sie Informationen zur regionalen Verfügbarkeit, zur Datenresidenz und zu Azure Active Directory B2C-Vorschaumandanten.
services: active-directory-b2c
author: msmimart
manager: celestedg
ms.service: active-directory
ms.workload: identity
ms.topic: reference
ms.date: 10/20/2020
ms.author: mimart
ms.subservice: B2C
ms.custom: references_regions
ms.openlocfilehash: 9cb7a97b3f57ee7ac10babc53ee2263d51838777
ms.sourcegitcommit: ce8eecb3e966c08ae368fafb69eaeb00e76da57e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/21/2020
ms.locfileid: "92309678"
---
# <a name="azure-active-directory-b2c-region-availability--data-residency"></a>Azure Active Directory B2C: Regionale Verfügbarkeit und Datenresidenz

Regionale Verfügbarkeit und Datenresidenz sind zwei sehr unterschiedliche Konzepte, die in Azure AD B2C anders als in den restlichen Komponenten von Azure angewendet werden. In diesem Artikel werden die Unterschiede zwischen diesen beiden Konzepten erläutert und ihre Anwendung in Azure und Azure AD B2C miteinander verglichen.

Azure AD B2C ist **grundsätzlich weltweit verfügbar** , mit der Option für **Datenresidenz** in den **USA, in Europa und in der Region „Asien-Pazifik“** .

[Regionale Verfügbarkeit](#region-availability) gibt an, wo ein Dienst für die Verwendung verfügbar ist.

[Datenresidenz](#data-residency) gibt an, wo die Benutzerdaten gespeichert werden.

## <a name="region-availability"></a>Regionale Verfügbarkeit

Azure AD B2C ist über die öffentliche Azure-Cloud weltweit verfügbar.

Dies unterscheidet sich von dem Modell der meisten anderen Azure-Dienste, in dem *Verfügbarkeit* und *Datenresidenz* gekoppelt sind. Beispiele hierfür finden Sie auf der Seite [Verfügbare Produkte nach Region](https://azure.microsoft.com/regions/services/) und der Seite [Azure Active Directory B2C – Preise](https://azure.microsoft.com/pricing/details/active-directory-b2c/) von Azure.

## <a name="data-residency"></a>Datenresidenz

Benutzerdaten von Azure AD B2C werden entweder in den USA, in Europa oder in der Region „Asien-Pazifik“ gespeichert.

Die Datenresidenz wird durch das Land oder die Region bestimmt, das bzw. die Sie beim [Erstellen eines Azure AD B2C-Mandanten](tutorial-create-tenant.md) auswählen:

![Screenshot des Formulars „Mandanten erstellen“, Auswahl von Land oder Region.](./media/data-residency/data-residency-b2c-tenant.png)

Für die folgenden Länder/Regionen werden die Daten in den **USA** gespeichert:

> USA (US), Kanada (CA), Costa Rica (CR), Dominikanische Republik (DO), El Salvador (SV), Guatemala (GT), Mexiko (MX), Panama (PA), Puerto Rico (PR) sowie Trinidad und Tobago (TT)

Für die folgenden Länder/Regionen werden die Daten in **Europa** gespeichert:

> Algerien (DZ), Österreich (AT), Aserbaidschan (AZ), Bahrain (BH), Belarus (BY), Belgien (BE), Bulgarien (BG), Kroatien (HR), Zypern (CY), Tschechische Republik (CZ), Dänemark (DK), Ägypten (EG), Estland (EE), Finnland (FT), Frankreich (FR), Deutschland (DE), Griechenland (GR), Ungarn (HU), Island (IS), Irland (IE), Israel (IL), Italien (IT), Jordanien (JO), Kasachstan (KZ), Kenia (KE), Kuwait (KW), Lettland (LV), Libanon (LB), Liechtenstein (LI), Litauen (LT), Luxemburg (LU), Nordmazedonien (ML), Malta (MT), Montenegro (ME), Marokko (MA), Niederlande (NL), Nigeria (NG), Norwegen (NO), Oman (OM), Pakistan (PK), Polen (PL), Portugal (PT), Katar (QA), Rumänien (RO), Russland (RU), Saudi-Arabien (SA), Serbien (RS), Slowakei (SK), Slowenien (ST), Südafrika (ZA), Spanien (ES), Schweden (SE), Schweiz (CH), Tunesien (TN), Türkei (TR), Ukraine (UA), Vereinigte Arabische Emirate (AE) und Vereinigtes Königreich (GB)

Für die folgenden Länder/Regionen werden die Daten in der Region **Asien-Pazifik** gespeichert:

> Afghanistan (AF), Hongkong (SAR) (HK), Indien (IN), Indonesien (ID), Japan (JP), Südkorea (KR), Malaysia (MY), Philippinen (PH), Singapur (SG), Sri Lanka (LK), Taiwan (TW) und Thailand (TH)

Derzeit wird die Liste um die folgenden Länder/Regionen ergänzt. Sie können vorerst Azure AD B2C verwenden, indem Sie eines bzw. eine der oben genannten Länder/Regionen auswählen.

> Argentinien, Australien, Brasilien, Chile, Ecuador, Irak, Kolumbien, Neuseeland, Paraguay, Peru, Uruguay und Venezuela.

## <a name="remote-profile-solution"></a>Remoteprofillösung

[Benutzerdefinierte Richtlinien](custom-policy-overview.md) von Azure AD B2C ermöglichen die Integration in [RESTful-API-Dienste](custom-policy-rest-api-intro.md), was wiederum das Speichern und Lesen von Benutzerprofilen aus einer Remotedatenbank (etwa eine Marketingdatenbank, ein CRM-System oder eine beliebige Branchenanwendung) ermöglicht.  
- Während der Registrierung und der Profilbearbeitung ruft Azure AD B2C eine benutzerdefinierte REST-API auf, um das Benutzerprofil in der Remotedatenquelle zu speichern. Die Anmeldeinformationen des Benutzers werden im Azure AD B2C-Verzeichnis gespeichert. 
- Bei der Anmeldung ruft Azure AD B2C nach der Überprüfung der Anmeldeinformationen mit einem lokalen Konto oder einem Social Media-Konto die REST-API auf. Diese sendet daraufhin den eindeutigen Bezeichner des Benutzers als primären Benutzerschlüssel (E-Mail-Adresse oder Benutzerobjekt-ID). Die REST-API liest die Daten aus der Remotedatenbank und gibt das Benutzerprofil zurück.  

Nach Abschluss der Registrierung, Profilbearbeitung oder Anmeldung schließt Azure AD B2C das Benutzerprofil in das Zugriffstoken ein, das an die Anwendung zurückgegeben wird. Weitere Informationen finden Sie auf GitHub in der [Beispiellösung für Azure AD B2C-Remoteprofile](https://github.com/azure-ad-b2c/samples/tree/master/policies/remote-profile).

## <a name="preview-tenant"></a>Vorschaumandant

Wenn Sie während des Vorschauzeitraums von Azure AD B2C einen B2C-Mandanten erstellt haben, ist die Wahrscheinlichkeit hoch, dass der **Mandantentyp** auf **Vorschaumandant** festgelegt ist.

In diesem Fall können Sie Ihren Mandanten NUR für Entwicklungs- und Testzwecke verwenden. Verwenden Sie einen Vorschaumandanten NICHT für Produktionsanwendungen.

Es gibt **keinen Migrationspfad** von einem B2C-Vorschaumandanten zu einem B2C-Produktionsmandanten. Sie müssen einen neuen B2C-Mandanten für Ihre Produktionsanwendungen erstellen.

Beim Löschen eines B2C-Vorschaumandanten und dem Erstellen eines B2C-Produktionsmandanten mit demselben Domänennamen können bekannte Probleme auftreten. *Sie müssen einen B2C-Produktionsmandanten mit einem anderen Domänennamen erstellen* .

![Screenshot eines Mandantentyps als Vorschaumandant.](./media/data-residency/preview-b2c-tenant.png)

## <a name="next-steps"></a>Nächste Schritte

- [Erstellen eines Azure AD B2C-Mandanten](tutorial-create-tenant.md)
