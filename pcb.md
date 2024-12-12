> [Table des matières](/README.md)

# PCB

> Accéder au [répertoire](https://github.com/samucapte/UWBase)

Les détails de la conception du circuit électrique sont contenus dans le répertoire ci-haut.

### Outils

- [KiCad](https://www.kicad.org/)

### Schéma

Consulter le [schéma électrique](/pcb/schematic_v1_2.pdf) avant d'effectuer une manipulation.

### Utilisation

Les LEDs J31, J35, J36 et J37 servent à valider l'alimentation.

En mission, connecter les batteries aux connecteurs J1, J5 et/ou J6. Ne pas utiliser de convertisseur USB vers UART.

Le PCB contient 2 circuits:

- Le circuit principal (1V8) alimentant le MCU;
- Le circuit secondaire (3V3) alimentant les capteurs. Celui-ci est activé (ou non) par le circuit principal.

### Développement

Au cours du développement, il est plus simple d'utiliser un convertisseur USB vers UART dans le connecteur LPUART. Les broches sont positionnées pour accueillir le convertisseur directement. **Il faut connecteur la broche 3V3 du convertisseur au connecteur central de J10** pour l'alimenter.
