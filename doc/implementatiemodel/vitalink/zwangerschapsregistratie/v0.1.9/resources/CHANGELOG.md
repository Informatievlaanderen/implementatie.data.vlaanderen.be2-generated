# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Released]

### [0.1.8] - 2026-10-23

### Added
- Attribuut PregnancyListEnvelope.ontvangstReferte (String [0..1]), URI https://implementatie.data.vlaanderen.be/ns/vitalink/zwangerschapsregistratie#ontvangstReferte. Hiermee bevestigt de afnemer de ontvangst van de vorige batch.
- Nieuwe OpenAPI-specificatie zwangerschapsstatussen_api.yaml (OpenAPI 3.1): gegenereerd door de toolchain, met handmatig toegevoegde paths en tags.

### Changed
- Zwangerschappen worden opgehaald in batches (batchSize, ontvangstReferte) in plaats van met een filter op het effectief tijdstip (effectiefTijdstipVan, effectiefTijdstipTot) en offset/limit-paginering.
- Endpoint: /zwangerschaps-registraties (was /api/v1/zwangerschapsregistraties).
- Kardinaliteit PregnancyListEnvelope.data: [1..1] -> [0..*].
- DataEnvelope is abstract. PregnancyListEnvelope bevat de geërfde eigenschappen (@id, warning) rechtstreeks.
- Organisatie.voorkeursnaam en Identificator.identificator zijn in de OpenAPI-specificatie objecten met @value (en @language of @type) in plaats van strings.
- Problemdetail.status is in de OpenAPI-specificatie een integer in plaats van een number.

### Removed
- Klasse PregnancyEnvelope en het endpoint om één zwangerschap op te halen op basis van het INSZ.
- Attribuut DataEnvelope.volgende. Datatype Link staat niet meer op het diagram.
- OpenAPI-bestanden van 0.1.7 (zwangerschapsregistratie_api.yaml, components.yaml).

### Fixed
- Periode.begin en Periode.einde zijn van het type DateTime (verwezen naar GetypeerdeString) en zijn in de OpenAPI-specificatie strings met format date-time.

### [0.1.7] - 2026-09-23

### Added
- Initiële productieversie

## [Unreleased]

### [0.1.7] - 2026-09-21

### Changed
- Nieuwe OpenAPI specificatie (YAML) met handmatige aanpassingen voor MAGDA.
- Aanpassingen meerdere kardinaliteiten.
- Toevoeging URIs voor Envelop, Problemdetail, Uitzondering & Annotatie

### [0.1.6] - 2026-09-15

### Added
- Toevoeging Zwangerschapsevenelope (+ list) structuur + problemdetail + additionele enteiten ter ondersteuning van het genereren van de OpenAPI specificatie.
- Toevoeging 'ignore'-tags voor ongebruikte relatierichtingen.
- Nieuwe OpenAPI specificatie werd toegevoegd aan resources in de repository.

### Fixed
- Correctie bereik van verschillende eigenschappen.
- Labels naar camelcase.
- 'gegevennaam' -> 'voornaam'

### Changed
- heeftPersoon URI -> namespace gezondheidstoestand

### [0.1.5] - 2026-09-09

### Added
- Toevoeging MedischVerslag met relaties steltOp/opgesteldDoor met Agent en documenteert/gedocumenteerdDoor met Medische Observatie.
- Toevoeging attribuut volledigeNaam aan Persoon.

### Fixed
- Toevoeging uri aan de 'documenteert'-eigenschap.

### Changed
- Verwijderen relatie 'uitvoerder' tussen MedischeObservatie en Agent.
- Zwangerschap als 'root'.
