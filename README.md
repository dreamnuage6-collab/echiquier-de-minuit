# Échiquier de Minuit

Jeu d'échecs pédagogique en français, en un seul fichier HTML (aucune dépendance, fonctionne hors ligne).

## Contenu
- 9 chapitres × 10 niveaux : Italienne, Noirs, Mats, Tactique, Finales, **Pièges de l'Italienne**, **Les Noirs face à 1.d4 / 1.Cf3**, **Plans du milieu de partie**, **Écarts de l'Italienne**
- Moteur **Stockfish 19** (celui de chess.com) pour la barre d'avantage, les indices, le bot et le bilan ; coups étiquetés comme sur chess.com (Brillant, Très bon coup, Meilleur, Excellent, Bon, Théorie, Imprécision, Erreur, Gaffe)
- Problème du jour (364 problèmes) avec rattrapage
- Bot « le Croque-mort » à 5 niveaux (Débutant → Expert), qui n'abandonne jamais : mat ou nulle
- **Bilan de fin de partie** : revue coup par coup (graphique d'évaluation, classification meilleur / bon / imprécision / erreur / gaffe, coup suggéré, « Analyse plus profonde »)
- **Révision espacée** des positions ratées (1 / 3 / 7 / 14 / 30 / 60 jours)
- **Mode Répertoire** : s'entraîner sur ses lignes d'ouverture
- **Import** de parties chess.com (pseudo) ou PGN collé, puis bilan
- **Statistiques** et progression ; export/import de la sauvegarde (code ou fichier)
- **PWA** : installable sur téléphone, fonctionne hors ligne

## Notes
- Stockfish tourne dans le navigateur (WebAssembly) ; si le navigateur ne le permet pas, un petit moteur maison prend le relais (moins fort). Les étiquettes sont proches de celles de chess.com sans être identiques à chaque coup.
- L'import chess.com nécessite une connexion internet.
- La progression est stockée localement (localStorage) : pensez à l'export.

## Jouer
https://dreamnuage6-collab.github.io/echiquier-de-minuit/
