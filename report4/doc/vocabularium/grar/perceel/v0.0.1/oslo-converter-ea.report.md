#||# oslo-converter-ea for diagram OSLO-PerceelImplementatie

#||# -------------------------------------

2026-08-20T14:23:15.424Z info: [ConnectorConverterHandler]: Ignoring hidden connector (OSLO-Perceel:OSLO-GeneriekVoc!!!:FormeelKader:(FormeelKader -> Object))

2026-08-20T14:23:15.426Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Perceel:RuimtelijkeEenheid:(RuimtelijkeEenheid -> RuimtelijkeEenheid))

2026-08-20T14:23:15.426Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Perceel:OSLO-Generiek:Gemeente:(Gemeente -> Object))

2026-08-20T14:23:15.426Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Perceel:OSLO-Generiek:FormeelKader:(FormeelKader -> Object))

2026-08-20T14:23:15.428Z info: Connector Model:OSLO-Perceel:RuimtelijkeEenheid:(RuimtelijkeEenheid -> Adres) is not an association with a source role. Ignoring this connector.

2026-08-20T14:23:15.429Z info: Connector Model:OSLO-Perceel:OSLO-GRAR-IM:DataEnvelop:(DataEnvelop -> Links) is not an association with a source role. Ignoring this connector.

2026-08-20T14:23:15.429Z info: Connector Model:OSLO-Perceel:OSLO-GRAR-IM:PerceelEnvelop:(PerceelEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-08-20T14:23:15.429Z info: Connector Model:OSLO-Perceel:OSLO-GRAR-IM:PercelenEnvelop:(PercelenEnvelop -> DataEnvelop) is not an association with a source role. Ignoring this connector.

2026-08-20T14:23:15.429Z info: Connector Model:OSLO-Perceel:KadastraalPlanperceel:(KadastraalPlanperceel -> RuimtelijkeEenheid) is not an association with a source role. Ignoring this connector.

2026-08-20T14:23:15.430Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

Error: [PackageConverterHandler]: Unable to create URL from package URI (todo.com) for package (Model:OSLO-Perceel:XSD).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/PackageConverterHandler.js:66:23

    at Array.forEach (<anonymous>)

    at PackageConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/PackageConverterHandler.js:41:24)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:34:39)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/EaUmlConversionService.js:42:42

    at async EaUmlConversionService.run (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/EaUmlConversionService.js:38:23)

#||# -------------------------------------

file perceel-im-voc.jsonld does not exist

