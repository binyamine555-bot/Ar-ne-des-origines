# Episodes de l'histoire -- Arene des Origines

Branche de telechargement lue par le jeu (v15.1+). Ne contient que des medias du jeu :
plans animes et voix des etages 6 a 100, en paquets de 10 etages coupes en parties.

- `packs.json` : le manifeste (etages, tailles, sha256 de chaque paquet et de chaque partie)
- `p/` : les parties
Le jeu verifie chaque partie et chaque paquet (sha256) avant de l'utiliser.
Mise a jour : `v15/run/make_packs.py` puis `v15/run/publish_packs.py`.
