# FT_PRINTF

Printf est un projet de programmation informatique développé dans le cadre de l'école 42. Il s'agit d'une recréation de la fonction printf de la bibliothèque standard du langage C.

### Installation

Pour installer le programme Printf, vous devez d'abord cloner le dépôt GitHub sur votre machine locale :

````bash
git clone https://github.com/votre-nom-dutilisateur/printf.git
````

Ensuite, vous devez vous rendre dans le répertoire printf et exécuter la commande make pour compiler le programme :

````bash
cd printf
make
````

Le programme sera alors compilé et prêt à être utilisé.

### Utilisation

Pour utiliser la fonction printf recréée, vous devez inclure le fichier d'en-tête ft_printf.h dans votre programme C, et appeler la fonction ft_printf comme vous le feriez avec la fonction printf de la bibliothèque standard.

La fonction ft_printf prend une chaîne de formatage en premier argument, suivie des arguments à afficher. Voici quelques exemples d'utilisations :

````c
#include "ft_printf.h"

int main(void)
{
    int i = 42;
    char *s = "Hello, world!";
    
    ft_printf("Un entier : %d\n", i);
    ft_printf("Une chaîne de caractères : %s\n", s);
    ft_printf("Un caractère : %c\n", 'X');
    ft_printf("Un pourcentage : %%\n");
    
    return (0);
}
````

La sortie de ce programme sera :

````yaml
Un entier : 42
Une chaîne de caractères : Hello, world!
Un caractère : X
Un pourcentage : %
````

### Auteurs

Ce programme a été développé par "Vkanate" dans le cadre du projet Printf de l'école 42.
