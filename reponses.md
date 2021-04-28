Si il y a un nombre de noeuds impairs à un moment donné dans l'arbre de Merkle, le dernier noeud se duplique et s'hash avec lui même

Un nouveau noeud va se connecter a un noeud temporaire avant d'être connecté au réseau le temps d'être vérifié (vérification de tout les noeuds précédents et des hash)et ensuite ajouté au noeud qui lui correspond

Gavin Andersen est une personne qui est directement impliquée dans la mise au point du bitcoin, en effet il a été nommé responsable de l'implémentation de référence par Satoshi Nakamoto durant la conception du Bitcoin. Il était devenu responsable de la direction prise par le Bitcoin. Il a oeuvré pour l'avancement du bitcoin en tant que technologie mais aussi travaillé à la maintenance du projet en réécrivant une partie du code de Satoshi qui n'était pas parfait, bugs, sections redontantes et autres soucis techniques pouvaient mettre en péril la sécurité du projet.

une blockchain créé un lien entre ses différents blocks grâce au header de chaque block qui reprend une partie (le hash) de chaque bloc précédent, et ainsi de suite d'où le terme de blockchain, "chaine de "blocks"

La structure d'une blockchain peut s'apparenter a une "linked list" où chaque donnée influe sur la suivante, donc on peut vérifier l'intégrité d'une donnée grâce à la précédente

Pour faire une opération comme modifier une transaction d'il y a 6 mois il faut modifier le dit block et tout ceux qui ont été fait entretemps dans la période de 6 mois, dans la pure théorie c'est faisable mais en pratique c'est impossible car ça demanderait une puissance de calcul incommensurable pour rattraper le retard et continuer de modifier les blocks en temps réel, comme dit dans le livre blanc, ça s'apparente au phénomène du "Gambler's Ruin" où on part perdant dans une série de paris et pour rattraper son retard il faut calculer des opérations qui vont être de plus en plus difficiles et longues. Ce pour quoi il est largement plus réaliste de simplement continuer à travailler sur les nouveaux blocks de manière "legit"
Donc pour moi (et Satoshi Nakamoto) ce n'est pas possible car la quantité de blocks à modifier pour ce genre d'opération malicieuse devient très rapidement délirant
