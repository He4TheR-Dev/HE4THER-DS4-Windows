# HE4THER DS4 Windows

Distribution HE4THER de **DS4Windows** — outil Windows pour utiliser des manettes DualShock 4 / DualSense comme manette Xbox (via ViGEm).

## Contenu du dépôt

Ce dépôt publie le **build applicatif** (exécutable + dépendances + profils), pas le code source upstream.

| Élément | Détail |
|--------|--------|
| Application | `DS4Windows.exe` |
| Version | **3.3.3** |
| Runtime | .NET 8 |
| Profil inclus | `Profiles/@HE4THERSERVICES.xml` |

## Prérequis

- Windows 10 / 11 (64-bit)
- [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0)
- Pilote [ViGEmBus](https://github.com/ViGEm/ViGEmBus/releases) (requis pour l’émulation Xbox)

## Utilisation

1. Installe ViGEmBus si ce n’est pas déjà fait  
2. Lance `DS4Windows.exe`  
3. Connecte ta manette (USB ou Bluetooth)  
4. Choisis / ajuste un profil dans l’onglet Profiles  

## Crédits & upstream

Basé sur **DS4Windows** par la communauté open source :

- Projet historique : Scarlet.Crush, Jays2Kings, **Ryochan7**, et contributeurs  
- Copyright upstream : Scarlet.Crush Productions ; InhexSTER, HecticSeptic, electrobrains ; Jays2Kings ; Ryochan7  

HE4THER fournit cette distribution / packaging. Pour le **code source** et l’historique complet, se référer aux dépôts DS4Windows upstream.

## Licence

Voir le fichier [LICENSE](LICENSE) (Apache License 2.0, alignée sur DS4Windows).

## Auteur

**HE4THER DEV** — [@He4TheR-Dev](https://github.com/He4TheR-Dev)
