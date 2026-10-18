# Murmur: versions publicades

Murmur és una app de Mac que transcriu reunions en català en directe, tot en local.

Aquest repositori només conté el que Murmur descarrega per actualitzar-se:

- **Releases**: cada versió de l'app (`Murmur-<versió>.dmg` per instal·lar-la i `Murmur.app.tar.gz` + `latest.json`, signats, per a les actualitzacions automàtiques).
- **`models.json`**: el catàleg de models (transcripció, parlants, llenguatge), amb la versió, la mida i la suma SHA-256 de cada fitxer. L'app el consulta en obrir-se i només actualitza els models que ja té instal·lats.

Murmur no envia res més: comprovar si hi ha versions noves és l'única connexió que fa per iniciativa pròpia, i es pot desactivar a Configuració › General › Actualitzacions.
