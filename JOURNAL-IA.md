| Pertinente ici                                                                    | Non pertinente ici                            |
| --------------------------------------------------------------------------------- | --------------------------------------------- |
| `rememberNavController()` est correct — **navigation**                            | Routes typées — **hors périmètre**            |
| Navigation vers le détail                                                         |                                               |
|l'identifiant du produit est transmis dans l'URL de navigation.                    | ViewModel — **hors périmètre**                |
| `navigate("detail/$produitId")` est correct — **navigation**                      | Animations de transition — **hors périmètre** |
| `"detail/{produitId}"` correspond à la route — **cohérence**                      |        |
| Récupération de `produitId` avec `?.` et `toIntOrNull()` — **null-safety**        | Gestion d'un état global — **hors périmètre** |
|Gestion du produit inexistant, Cela évite une erreur, mais si le produit n'existe  |                                               |
|pas,aucun écran ni message n'est affiché.                                          |                                               |

