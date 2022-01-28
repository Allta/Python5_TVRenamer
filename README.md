# TP Guess The Number - Ynov Python B1

:see_no_evil: _**Il s'agit d'un travail autonomne.**_ :speak_no_evil:

:sparkles: Une fois le TP et le rendu terminé commitez et pushez le dans le repo. :sparkles:
  
### Tips   

:raising_hand: Si vous avez des soucis n'hésitez pas à m'appeler. 
 
 ## Exercice 1: TV Show Renamer
 
Dans ce projet, dans le fichier `main.py` vous devez réaliser un programme pour renommer les épisodes d'une série téléchargée depuis des sources différentes.
Dans cet exercice vous devrez utilisé le fichier `episode_liste` fourni dans le repo.

**Vous devez préalablement créer un fichier (Peu importe le type ! ) ayant le nom de l'épisode dans le fichier `episode_liste`. **
 
 Il faudra : 
- Detecter le numéro de l'épisode
- Renommer le fichier sans modifier l'extension en suivant le pattern suivant : 
  - **The Big Bang Theory [SEASON_NUMBERxEPISODE_NUMBER] - EPISODE_NAME.EXTENSION** 
- Les noms des épisodes sont fournis à la fin de ce Readme.


>The Big Bang Theory [6x22] - The Proton Resurgence.flv
>The Big Bang Theory [6x5] - The Holographic Excitation.mkv
>The Big Bang Theory [6x21] - The Closure Alternative.flv
>The Big Bang Theory [6x15] - The Spoiler Alert Segmentation.mp4
>The Big Bang Theory [6x24] - The Bon Voyage Reaction.flv
>The Big Bang Theory [6x3] - The Higgs Boson Observation.mkv
>The Big Bang Theory [6x18] - The Contractual Obligation Implementation.flv
>The Big Bang Theory [6x9] - The Parking Spot Escalation.mkv
>The Big Bang Theory [6x11] - The Santa Simulation.mkv
>The Big Bang Theory [6x14] - The CooperKripke Inversion.mp4
>The Big Bang Theory [6x20] - The Tenure Turbulence.flv
>The Big Bang Theory [6x1] - The Date Night Variable.mkv
>The Big Bang Theory [6x23] - The Love Spell Potential.flv
>The Big Bang Theory [6x8] - The 43 Peculiarity.mkv
>The Big Bang Theory [6x4] - The Re-Entry Minimization.mkv
>The Big Bang Theory [6x19] - The Closet Reconfiguration.flv
>The Big Bang Theory [6x12] - The Egg Salad Equivalency.mkv
>The Big Bang Theory [6x7] - The Habitation Configuration.mkv
>The Big Bang Theory [6x2] - The Decoupling Fluctuation.mkv
>The Big Bang Theory [6x16] - The Tangible Affection Proof.mp4
>The Big Bang Theory [6x10] - The Fish Guts Displacement.mkv
>The Big Bang Theory [6x13] - The Bakersfield Expedition.mp4
>The Big Bang Theory [6x17] - The Monster Isolation.mp4
>The Big Bang Theory [6x6] - The Extract Obliteration.mkv


## Exercice BONUS : 

- Ne pas utiliser la liste des épisodes ci-dessus.
- Le programme doit detecter le nom de la série en comptant le nombre d'occurence des noms de fichier présents dans le dossier.
- Le programme doit detecter le numéro de la saison de l'épisode, si des saisons différentes sont dans le même dossier il faudra alors séparer les épisodes dans des dossiers différents comportant le numéro de la saison.
- A l'aide du site : https://thetvdb.com/series/the-big-bang-theory/seasons/official/6 et de la librairie `request` (ou de la librairie `tvdb-api`) récupérer les noms des épisodes et renommer en concordance.




