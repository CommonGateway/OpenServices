# OpenServices

## Over OpenServices

OpenServices, gebaseerd op het Symfony framework, biedt een robuuste oplossing voor het hosten en beheren van (micro)services binnen overheidsorganisaties. Met een 'haven first' benadering faciliteert OpenServices een gestandaardiseerd platform voor de implementatie, integratie en het beheer van diverse microservices zoals OpenWoo, Waardepapier en Notificatie Service. Dit framework stelt overheidsinstanties in staat om efficiënter en effectiever te werken door de naadloze koppeling van diensten en het delen van data.

## Kernfunctionaliteiten

- **Microservice Management:** Beheer eenvoudig een reeks van microservices onder één dak.
- **Haven First Benadering:** Geoptimaliseerd voor de hosting en orkestratie van microservices, met prioriteit voor veiligheid en schaalbaarheid.
- **Naadloze Integratie:** Ondersteunt de koppeling met bestaande overheidsdiensten zoals KOOP en systemen zoals het Zaaksysteem.
- **Event Driven:** Set cloud events om naar interne events waar vanuit code snel op kan worden ingehaakt
- **Veiligheid en Compliance:** Ontworpen met een focus op veiligheidsstandaarden en compliance met overheidsvoorschriften.

## Installatie

### Locale Installatie
Vereisten:
- PHP 7.4 of hoger
- Symfony 5 of hoger
- Docker (voor containerisatie)

Stap-voor-stap installatiegids:
1. Clone het OpenServices repository: `git clone https://github.com/ConductionNL/OpenServices.git`
2. Installeer afhankelijkheden: `composer install`
3. Configureer de .env bestanden met uw database en andere service-specifieke instellingen.
4. Start de services: `docker-compose up -d`

### Haven (Kubernetes) Installatie

## Gebruik

Na installatie kunt u beginnen met het configureren en deployen van uw microservices binnen het OpenServices framework. Raadpleeg de documentatie voor specifieke configuratiegidsen voor elke service, zoals OpenWoo, Waardepapier en Notificatie Service.

## Bijdragen

Wij verwelkomen bijdragen van de community! Als u wilt bijdragen aan OpenServices, gelieve ons te contacteren via info@conduction.nl of een pull request in te dienen via onze GitHub repository.

## Licentie

OpenServices is uitgegeven onder een EUPL 1.2 licentie. Zie het (`LICENSE.md`)[`LICENSE.md`] bestand in onze GitHub repository voor meer details.

## Contact

Voor meer informatie over OpenServices en hoe u het in uw organisatie kunt implementeren, neem contact met ons op via info@conduction.nl.