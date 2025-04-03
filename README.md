# Gomoku-AI-Game
Gomoku : A rontement entre IA
 Le Gomoku est un jeu de plateau a deux joueurs en tour par tour (joueur1 avec les pions noir, joueur2
 avec les pions blanc). Le joueur noir joue en premier. Chaque joueur a 60 pions. La taille du plateau est de
 15 cases sur 15 cases. Les lignes sont numerotees de A a O et les colonnes sont numerotees de 0 a 14.
 Un joueur peut placer un pion sur toute case libre.
 Le premier reussissant a aligner 5 pions consecutifs (horizontalement,verticalement ou en diagonale) a
 gagne. Autrement, la partie est declaree nulle sil ny a plus de pions.
 Dans le jeu de Gomoku (comme pour le morpion), le premier joueur est avantage. Nous nous interessons
 a une variante permettant de reduire cet e et tout en restant simple a coder. Il sagit de la variante long pro:
 le joueur1 (noir) place un pion au centre du plateau (H7),
 le joueur2 (blanc) peut placer un pion nimporte ou
 puis le joueur1 peut placer un pion nimporte ou excepte dans un carre de taille 7 cases sur 7 cases de
 centre H7.
 Ensuite la partie suis son cours normalement...
 Votre IA doit partir de celle developpee pour le morpion: cest a dire un minimax avec un elagage alpha
beta. Si vous trouvez des heuristiques permettant den ameliorer les resultats vous etes encourages a le faire.
 Pour les plus curieux, vous pouvez lire cet article:
 http://ai.csie.ndhu.edu.tw/paper/200612071659502.pdf
 Votre programme doit etre pense a n quun etre humain puisse la ronter. Ainsi on pourra se faire
 a ronter deux IA sur di erentes machines entre elles (par humains interposes a n de renseigner les coups de
 lautre IA). Lorsque ce sera au tour du joueur humain de jouer, il devra renseigner la ligne puis la colonne
 ou il veut placer un pion. LIA a chera a lecran son choix (par exemple: D7 ). Le plateau a chera tous
 les choix des joueurs(humain et machine). Cette a chage sera fait simplement en mode texte.
 Le joueur humain pourra choisir en debut de partie sil a les pions noir (ce qui implique de commencer la
 partie) ou les blancs.
 LIA de Gomoku est a realiser par groupe de 3/4 etudiants (du meme groupe de TP). LIA devra repondre
 en 5 secondes maximum.
 Nous reviendrons sur les details du deroulement de cette seance ulterieurement. Votre IA devra tourner
 sur Google Colab1, il sagit dun environnement de developpement dans le cloud (necessite davoir une adresse
 gmail).
 Les IA sa ronteront a votre derniere seance de TP respective. A cette occasion, un compte rendu
 expliquant vos choix et detaillant votre implementation ainsi que votre code seront a deposer sur DVO.
 Levaluation dependra principalement de limplementation du minimax avec elagage alpha-beta ainsi
 quun fonctionnement correct (possibilite de jouer plusieurs parties sans bugs)
