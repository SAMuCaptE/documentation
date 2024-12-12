> [Table des matières](/README.md)

# Pigeon

> Accéder au [répertoire](https://github.com/samucapte/pigeon)

Pigeon est le protocole de communication utilisé pour transférer des données entre [Loch](https://github.com/samucapte/loch) et [Atlanta](https://github.com/samucapte/atlanta).
Il est également prévu pour la communication entre Loch et Ness.

### Définition du protocole

Pigeon s'attend à une liste d'opcodes connue à l'avance. Elle est définie dans un fichier `.toml`.
<br/>
La [version 0](https://github.com/SAMuCaptE/pigeon/blob/main/protocol/v0.toml) en est un exemple.

Le répertoire contient un [outil CLI](https://github.com/SAMuCaptE/pigeon/blob/main/docs/cli.md) convertissant la définition en code embarqué (en C) et en code pour le logiciel (en Go).
<br/>
Le répertoire contient aussi les implémentations de la librairie de communication pour les deux interfacs (C et Go).

### Liens externes

La documentation plus technique quant au fonctionnement de Pigeon est disponible dans son [répertoire](https://github.com/samucapte/pigeon).

Pigeon CLI ainsi que la librairie (libpigeon) son disponibles les [publications du projet](https://github.com/SAMuCaptE/pigeon/releases).

> Note: le préfixe "lib" est nécessaire pour que STM32CubeIDE détecte la librairie.
