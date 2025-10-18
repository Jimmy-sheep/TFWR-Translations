# Arrosage
Les plantes poussent plus vite lorsqu'elles sont arrosées. Le sol a un niveau d'eau allant de `0` à `1`.
La fonction `get_water()` renvoie le niveau d'eau du sol sur lequel il se trouve.

La vitesse de croissance d'une plante évolue linéairement de 1x à un niveau d'eau de 0 à 5x à un niveau d'eau de 1.

Le sol s'assèche avec le temps : en moyenne, il perd 1% de son eau actuelle par seconde, mais il y a une certaine variance aléatoire. Maintenir un niveau d'eau élevé consommera beaucoup plus d'eau que de maintenir un niveau d'eau bas.

Tu peux utiliser de l'eau sur tes plantes. Un réservoir d'eau est automatiquement ajouté à ton inventaire toutes les 10 secondes.
Améliorer `Unlocks.Watering` doublera la quantité d'eau que tu obtiens toutes les 10 secondes.

Un réservoir contient `0.25` d'eau.

Appelle `use_item(Items.Water)` sur n'importe quel sol pour l'arroser.
