#||# oslo-converter-ea for diagram OSLO-Trajectcontrole-IM-Enumeraties

#||# -------------------------------------

2026-07-10T13:35:16.352Z info: Connector Model:OSLO-Trajectcontroles-IM:W3C-REGORG:GeregistreerdeOrganisatie:(GeregistreerdeOrganisatie -> Agent) is not an association with a source role. Ignoring this connector.

2026-07-10T13:35:16.354Z info: Connector Model:OSLO-Trajectcontroles-IM:OSLO-Persoon:GeregistreerdPersoon:(GeregistreerdPersoon -> Agent) is not an association with a source role. Ignoring this connector.

2026-07-10T13:35:16.354Z info: Connector Model:OSLO-Trajectcontroles-IM:OSLO-Persoon:GeregistreerdPersoon:(GeregistreerdPersoon -> Geboorte) is not an association with a source role. Ignoring this connector.

2026-07-10T13:35:16.354Z info: Connector Model:OSLO-Trajectcontroles-IM:W3C-DPV:Certificaat:(Certificaat -> Agent) is not an association with a source role. Ignoring this connector.

2026-07-10T13:35:16.355Z info: Connector Model:OSLO-Trajectcontroles-IM:W3C-DPV:Certificaat:(Certificaat -> Agent) is not an association with a source role. Ignoring this connector.

2026-07-10T13:35:16.355Z info: Connector Model:OSLO-Trajectcontroles-IM:W3C-DPV:Certificaat:(Certificaat -> Voertuig) is not an association with a source role. Ignoring this connector.

2026-07-10T13:35:16.355Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model:Trajectcontroles). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model:Trajectcontroles:SCHEMA). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model:Trajectcontroles:DCTERMS). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model:Trajectcontroles:OSLO-Generiek). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model:Trajectcontroles:DataTypes). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model:DUMP). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Trajectcontroles-IM). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy:OSLO-Codelijst). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:OSLO-Trajectcontroles-IM:W3C-Person). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy:GNSS-DCAT-AP). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy:EU-IT6). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy:W3C-DQV). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy:IFC-BIM). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.356Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy:OSLO-Template). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.357Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Model - Copy:DUMP). Using fallback URI (http://todo.com/) instead.

2026-07-10T13:35:16.360Z warn: [ConnectorConverterHandler]: Connector (eigenaar) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-07-10T13:35:16.360Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (eigenaar) and the fallback URI (http://todo.com/) will be assigned.

2026-07-10T13:35:16.360Z warn: [ConnectorConverterHandler]: Connector (bestuurder) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-07-10T13:35:16.360Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (bestuurder) and the fallback URI (http://todo.com/) will be assigned.

2026-07-10T13:35:16.360Z warn: [ConnectorConverterHandler]: Connector (voertuig) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-07-10T13:35:16.360Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (voertuig) and the fallback URI (http://todo.com/) will be assigned.

Error: [ElementConverterHandler]: Invalid URL (TBD) for element (Model:Model:Trajectcontroles:FOAF:Agent).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:55:27

    at Array.forEach (<anonymous>)

    at ElementConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:42:24)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:38:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:38:37)

#||# -------------------------------------

file trajectcontrole.jsonld does not exist

