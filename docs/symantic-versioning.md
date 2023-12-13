# Symantic versioning

Symantic versioning is een set van regels en vereisten die voorschrijven hoe versienummers op software worden toegewezen en opgehoogd.

Gegeven een versienummer MAJOR.MINOR.PATCH (bijv 4.2.18), verhoog:

- MAJOR (**1**.0.0)
    - Niet backwards compatible wijziging
    - Andere interface naar gebruiker
    - Redesign
    - Nieuwe features
    - Nieuwe workflows
- MINOR (1.**2**.0) 
    - Feature update
    - Nieuwe features worden geintroduceerd
    - Backwards compatible
- PATCH (0.1.**1**) -> bugfix
    - Bugfix
    - Kan elk moment worden toegepast
    - Geen nieuwe features
    - Volledig backwards compatible

Meer informatie over symantic versioning:<br/>
[https://semver.org](https://semver.org)
