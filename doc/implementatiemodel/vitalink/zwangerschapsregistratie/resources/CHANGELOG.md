# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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
