---
title: Information om utbetalnings princip – Microsoft Commercial Marketplace
description: Läs mer om information som rör utbetalnings principer för kommersiella Marketplace, inklusive scheman och återkoppling.
ms.service: marketplace
ms.subservice: partnercenter-marketplace-publisher
ms.topic: conceptual
author: mingshen-ms
ms.author: mingshen
ms.date: 09/28/2020
ms.openlocfilehash: eec5f85f38280757bc1e5d5c36a4dd1ac5ce8d22
ms.sourcegitcommit: 3c45a181ef86b3a4866e97fb50efeae8714ab3f7
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 10/19/2020
ms.locfileid: "92532005"
---
# <a name="payout-policy-details"></a>Information om utbetalningsprincip

I den här artikeln beskrivs Microsofts utbetalnings process, utbetalnings schema, var du hittar status för en utbetalning och en återställnings princip.

## <a name="payment-schedules"></a>Betalnings scheman

I följande avsnitt beskrivs vår utbetalnings process.

### <a name="enterprise-agreement-transactions-after-may-1-2020"></a>Enterprise-avtal transaktioner efter den 1 maj 2020

#### <a name="update-to-our-commercial-marketplace-publisher-payout-model"></a>Uppdatera till vår utbetalnings modell för den kommersiella Marketplace-utgivaren

Från och med den 1 maj 2020 uppdaterar vi vår utlösare som är relaterad till produkter som köpts på Azure Marketplace eller AppSource av kunder med en Microsoft-Enterprise-avtal. När en kund köper en produkt från Azure Marketplace eller AppSource med sina befintliga Microsoft-Enterprise-avtal för transaktioner efter den 1 maj 2020 kommer vi att börja utfärda inbetalningar i nästa utbetalnings cykel 30 dagar efter kund faktura. Transaktioner där en kund använder ett kredit kort har inte ändrats och kommer att fortsätta att ha en 30-dagars företags period innan utbetalning. Den här tabellen visar information om utbetalnings schema.

> [!NOTE]
> Se [processen för kund icke-betalning](#process-for-customer-non-payment) nedan för de åtgärder som vi vidtar om kunden inte betalar, men vi redan har utfärdat en utbetalning till dig.

| Händelse  | Datum (UTC) | Partner synlighet: rapporten utbetalning för partner Center  |  Partner synlighet: Partner Center Analytics\* |
| --- | --- | --- | --- |
| Transaktion eller månad för användning | 8/1/2020 – 8/31/2020 | E.t. | **Användnings rapport** : ny förbrukning som visas (uppdateras var fjärde timme)<br>**Order rapport** : ej tillämpligt |
| Slut period (månad) | 8/31/2020 | E.t. | **Användnings rapport** : slut på månads förbrukning som visas<br>**Order rapport** : ej tillämpligt |
| Order genererad | 9/3/2020 – 9/7/2020 | E.t. | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Beräkna utbetalning | 9/4/2020 – 9/10/2020 | Markerat som **obearbetat** i transaktions historik på instrument panelen för utbetalning | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Månatlig utbetalning | 10/5/2020 | Markerat som **kommande** i transaktions historik på instrument panelen för utbetalningar | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Utbetalnings datum\** | 10/15/2020 | Markerat som **skickat** i transaktions historik och i avsnittet betalningar på instrument panelen för utbetalning | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Kund faktura insamlad | 12/1/2020 | Markerat som **skickat** i transaktions historik och i avsnittet betalningar på instrument panelen för utbetalning | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva  |
|  |  |  |  |

\* Användnings-och order rapporter är tillgängliga i avsnittet analysera i Partner Center. \* *. Utbetalnings datumet är i PST (Pacific, normal tid).

### <a name="customers-who-pay-using-credit-card-or-invoice"></a>Kunder som betalar med kredit kort eller faktura

Alla inköp med ett kredit kort eller en månads faktura har en 30-dagars period för att säkerställa att penning beloppen rensas och det inte finns några åter betalningar eller misstänkt bedrägerier.

| Händelse  | Datum (UTC) | Partner synlighet: rapporten utbetalning för partner Center  |  Partner synlighet: Partner Center Analytics\*  |
| --- | --- | --- | --- |
| Transaktion eller månad för användning | 8/1/2019 - 8/31/2019 | E.t. | **Användnings rapport** : ny förbrukning som visas (uppdateras var fjärde timme)<br>**Order rapport** : ej tillämpligt |
| Slut period (månad) | 8/31/2019 | E.t. | **Användnings rapport** : slut på månads förbrukning som visas<br>**Order rapport** : ej tillämpligt |
| Order genererad | 9/3/2019 – 9/7/2019 | E.t. | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Kund faktura insamlad | 9/7/2019 – 9/10/2019 | E.t. | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Beräkna utbetalning | 9/8/2019 -9/12/2019 | Markerat som **obearbetat** i transaktions historiken på instrument panelen för utbetalning | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Månatlig utbetalning | 11/5/2019\* | Markerat som **kommande** i transaktions historiken för utbetalnings instrument panelen | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Utbetalnings datum\** | 11/15/2019 | Markerat som **skickat** i transaktions historiken och i avsnittet betalningar på instrument panelen för utbetalning | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
|  |  |  |  |

\* Användnings-och order rapporter är tillgängliga i avsnittet analysera i Partner Center.</br>\** Utbetalnings datumet är i PST (Pacific, normal tid).

### <a name="enterprise-agreement-transactions-prior-to-may-1-2020"></a>Enterprise-avtal transaktioner före den 1 maj 2020

Alla köp som inträffar före detta datum bearbetas och betalas enligt schemat nedan efter att Microsoft har samlat in betalning från kunder och bearbetat Marketplace-avgiften.

| Händelse  | Datum (UTC)  | Partner synlighet: rapporten utbetalning för partner Center  |  Partner synlighet: Partner Center Analytics\*  |
| --- | --- | --- | --- |
| Transaktion eller månad för användning | 8/1/2019 – 8/31/2019 | E.t. | **Användnings rapport** : ny förbrukning som visas (uppdateras var fjärde timme)<br>**Order rapport** : ej tillämpligt |
| Slut period (månad) | 8/31/2019 | E.t. | **Användnings rapport** : slut på månads förbrukning som visas<br>**Order rapport** : ej tillämpligt |
| Order genererad | 9/3/2019 – 9/7/2019 | E.t. | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Kund faktura insamlad | 12/1/2019 | E.t. | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Beräkna utbetalning | 12/5/2019 – 12/7/2019 | Markerat som **obearbetat** i transaktions historiken på instrument panelen för utbetalning | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Månatlig utbetalning | 1/5/2019 | Markerat som **kommande** i transaktions historiken för utbetalnings instrument panelen | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
| Utbetalnings datum\** | 1/15/2019 | Markerat som **skickat** i transaktions historik och i avsnittet betalningar på instrument panelen för utbetalning | **Användnings rapport** : förbrukning som visas med Ordernr/OrderLineItemID<br>**Order rapport** : kund order visas som aktiva |
|  |  |  |  |

\* Användnings-och order rapporter är tillgängliga i avsnittet analysera i Partner Center.</br>\** Utbetalnings datumet är i PST (Pacific, normal tid).

## <a name="process-for-customer-non-payment"></a>Process för ej betalnings kund

I sällsynta fall kan Microsoft inte samla in betalningar från kunder för sina kommersiella marknads marknads inköp. När en kund inte betalar Microsoft enligt deras fakturerings schema påbörjar vi samlings processen. Den här processen tar cirka fyra månader och inbegriper beständig kommunikation från Microsoft. Om betalningen inte tas emot i slutet av den här processen, skriver Microsoft ut medlen som ej insamlade.

Efter utbetalnings processen som har framställts här kan Microsoft redan betala ut pengar till utgivare (du) som slutligen inte kan samlas in. Därför har vi en process för att stämma av dessa belopp. För att se till att du har en varning om att din (redan inlevererad) betalning kan stämmas av får du ett meddelande när en kund befinner sig i Inkasso processen och köp kan förmodligen skrivas av.

Microsoft kommer att koppla tillbaka eventuella utbetalningar som redan betalats till dig med någon av följande metoder: (1) Microsoft kan subtrahera de obetalda beloppen från framtida utbetalningar. om till exempel $1 000 i utbetalningar betraktas som ej kan samlas in och skrivs av, kommer dina framtida utbetalningar att bli kvar tills $1 000 återställs eller (2) Microsoft kan begära en åter betalning eller faktura utgivare för alla insamlade belopp.

Följande är ett exempel schema:

| Händelse | Ungefärligt datum | Partner synlighet |
| --- | --- | --- |
| Exempel på utbetalnings datum | 10/15/2020 | Markerat som **skickat** i transaktions historik och i avsnittet betalningar i instrument panelen för utbetalning |
| <font color="red">Om kunden inte betalar Microsoft</font> | 12/2/2020 – 12/5/2020 | Ingen ändring, samma som ovan |
| Kunden får ett e-postmeddelande om betalning för första sent | 12/6/2020 | Inget |
| Kunden får regelbundna e-postmeddelanden med ökande angelägenhets grad | 12/7/2020 – 1/31/2021 | Inget |
| Utgivaren har meddelats att skriva av är troligt vis | 1/7/2021 | E-postmeddelande som skickas till utgivaren om att deras kunder ännu inte har skickat någon betalning. Transaktions-ID och dollar belopp ingår. |
| Kund mottar uppsägnings meddelande | 2/1/2021 | Inget |
| Samlings processens slut/medel skrivs av | 2/15/2021 | E-postmeddelande som skickas till utgivare som fonder har skrivits av. Transaktions-ID och dollar belopp ingår. |
| Utbetalningen dras av | 3/1/2021 | I Publisher visas en negativ transaktion i Partner Center utbetalnings instruktion |
| Utbetalningen nekas | 3/15/2021 | Framtida utbetalningar visas i utbetalnings instruktionen för partner Center. Utgivare får ingen betalning förrän saldot inte längre är negativt.  |
|||

## <a name="number-of-days-for-payments-to-reach-a-payout-account"></a>Antal dagar för betalningar för att uppnå ett utbetalnings konto

Vi skickar vanligt vis ut alla betalningar som förfaller under en månad den 15: e dagen i månaden, men det tar ytterligare tid för betalningen att komma åt ditt konto. Antalet dagar beror på betalnings metoden som vi använder för ditt konto, enligt beskrivningen nedan.

> [!NOTE]
> De dagar som visas nedan är ungefärliga; alla betalningar kan ta längre eller kortare tid att komma åt ditt konto.

| Betalningsmetod     | Antal dagar för att uppnå utbetalnings konto     |
|--------------------|--------------------------------------------|
| PayPal             | 1 arbets dag                             |
| ACH/SEPA           | 2-3 arbets dagar                          |
| Överföring av överföring      | 7-10 arbets dagar                         |
|

## <a name="next-steps"></a>Nästa steg

- [Skatteinformation](tax-details-marketplace.md)
