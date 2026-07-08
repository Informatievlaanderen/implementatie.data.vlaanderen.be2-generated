#||# oslo-converter-ea for diagram GRAR-Adresregister

#||# -------------------------------------

2026-07-08T09:44:25.999Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Implementatiemodel-GRAR-Adres:DCTerms:Agent:rapporteertAan)

2026-07-08T09:44:26.004Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Straatnaam:(Straatnaam -> Gemeente) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.004Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Adresuitbreiding) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.004Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Gemeentenaam) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.004Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Gemeente) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.005Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Straatnaam) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.005Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> Postinfo) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.005Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Standplaats:(Standplaats -> AdresseerbaarObject) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.005Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Adres:(Adres -> AdresseerbaarObject) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.005Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Perceel:RuimtelijkeEenheid:(RuimtelijkeEenheid -> AdresseerbaarObject) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.006Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Gebouw:Gebouweenheid:(Gebouweenheid -> AdresseerbaarObject) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.006Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Ligplaats:(Ligplaats -> AdresseerbaarObject) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.006Z info: Connector Model:Implementatiemodel-GRAR-Adres:SF:Punt:(Punt -> Geometrie) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.006Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-Adres:Postinfo:(Postinfo -> Gemeente) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.006Z info: Connector Model:Implementatiemodel-GRAR-Adres:OSLO-GRAR-IM:DataEnvelop:(DataEnvelop -> Links) is not an association with a source role. Ignoring this connector.

2026-07-08T09:44:26.007Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

2026-07-08T09:44:26.007Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Implementatiemodel-GRAR-Adres). Using fallback URI (http://todo.com/) instead.

2026-07-08T09:44:26.007Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Implementatiemodel-GRAR-Adres:PROV). Using fallback URI (http://todo.com/) instead.

2026-07-08T09:44:26.007Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Implementatiemodel-GRAR-Adres:ADMS). Using fallback URI (http://todo.com/) instead.

2026-07-08T09:44:26.007Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Implementatiemodel-GRAR-Adres:SF). Using fallback URI (http://todo.com/) instead.

Error: [PackageConverterHandler]: Unable to create URL from package URI (TODO) for package (Model:Implementatiemodel-GRAR-Adres:XSD).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/PackageConverterHandler.js:66:23

    at Array.forEach (<anonymous>)

    at PackageConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/PackageConverterHandler.js:41:24)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:34:39)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/EaUmlConversionService.js:42:42

    at async EaUmlConversionService.run (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/EaUmlConversionService.js:38:23)

#||# -------------------------------------

file adres-im.jsonld does not exist

