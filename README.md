# Arma 3 Missions

## FR

Depot de missions de test pour *Arma 3*.

Ces missions servent a verifier rapidement les modules OPA dans l'editeur Eden, principalement sur la carte VR.

### Organisation

```text
missions/
  breaching.VR/
  hazmat.VR/
```

Chaque dossier correspond a une mission Arma 3 et peut etre copie directement dans le dossier `missions` du profil Arma.

### Missions

| Mission | Carte | Usage |
| --- | --- | --- |
| `breaching.VR` | VR | Mission de test pour `OPA_breaching` et `OPA_attachment`. |
| `hazmat.VR` | VR | Mission de test pour `OPA_chemical`. |

### Utilisation

1. Copie le dossier d'une mission depuis `missions/`.
2. Colle-le dans le dossier de missions du profil Arma 3.
3. Ouvre la mission dans l'editeur Eden.
4. Charge les mods OPA requis.
5. Lance les tests selon le module concerne.

### Mods testes

| Mission | Mods |
| --- | --- |
| `breaching.VR` | `OPA_breaching`, `OPA_attachment` |
| `hazmat.VR` | `OPA_chemical` |

### Note de patch 0.1

- Premiere version documentee.
- Ajout des missions de test `breaching.VR` et `hazmat.VR`.
- Organisation simple pour copie directe dans le profil Arma 3.

---

## EN

Test mission repository for *Arma 3*.

These missions are used to quickly verify OPA modules in the Eden editor, mainly on the VR map.

### Organization

```text
missions/
  breaching.VR/
  hazmat.VR/
```

Each folder is an Arma 3 mission and can be copied directly into the profile `missions` folder.

### Missions

| Mission | Map | Usage |
| --- | --- | --- |
| `breaching.VR` | VR | Test mission for `OPA_breaching` and `OPA_attachment`. |
| `hazmat.VR` | VR | Test mission for `OPA_chemical`. |

### Usage

1. Copy a mission folder from `missions/`.
2. Paste it into the Arma 3 profile missions folder.
3. Open the mission in the Eden editor.
4. Load the required OPA mods.
5. Run tests for the relevant module.

### Tested Mods

| Mission | Mods |
| --- | --- |
| `breaching.VR` | `OPA_breaching`, `OPA_attachment` |
| `hazmat.VR` | `OPA_chemical` |

### Patch Note 0.1

- First documented release.
- Added `breaching.VR` and `hazmat.VR` test missions.
- Simple organization for direct copy into the Arma 3 profile.

---

## License & Author

Provided by **soraanoir/sundae https://github.com/soraanoir**.  
Free to use and modify, provided that credit is given to the author.
