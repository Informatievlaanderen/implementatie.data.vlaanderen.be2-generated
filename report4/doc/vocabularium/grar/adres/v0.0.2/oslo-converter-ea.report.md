#||# oslo-converter-ea for diagram GRAR-Adresregister

#||# -------------------------------------

2026-11-26T16:45:01.875Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Implementatiemodel-GRAR-Adres:DCTerms:Agent:rapporteertAan)

2026-11-26T16:45:01.879Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:AdresEnvelop:(AdresEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.879Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:AdressenEnvelop:(AdressenEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.879Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:GemeenteEnvelop:(GemeenteEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.880Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Straatnaam:(Straatnaam -> Gemeente) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.880Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Adresuitbreiding) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.880Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Gemeentenaam) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.880Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Gemeente) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.881Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Straatnaam) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.881Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Postinfo) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.881Z info: Connector Model:Implementatiemodel-GRAR-Adres:SF:Punt:(Punt -> Geometrie) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.881Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:GemeentenEnvelop:(GemeentenEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.881Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:PostinfoEnvelop:(PostinfoEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.881Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:PostinfoLijstEnvelop:(PostinfoLijstEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.882Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:StraatnaamEnvelop:(StraatnaamEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.882Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:StraatnamenEnvelop:(StraatnamenEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.882Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Postinfo:(Postinfo -> Gemeente) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.882Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:DataEnvelop:(DataEnvelop -> Links) is not an association with a source role. Ignoring this connector.

2026-11-26T16:45:01.883Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

Error: [AttributeConverterHandler]: Unable to find domain object for attribute (Model:Implementatiemodel-GRAR-Adres:OSLO-Generiek:GeografischeNaam:taal).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:52:23

    at Array.forEach (<anonymous>)

    at AttributeConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:49:26)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:38:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:38:37)

#||# -------------------------------------

file adres-im-voc.jsonld does not exist

