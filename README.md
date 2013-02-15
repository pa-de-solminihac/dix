[dix : recherches rapides de paquets Debian ou Ubuntu](http://www.nocturne-jdr.fr/blog/equivalent-eix-pour-debian-ubuntu/)
===

Recherches par expressions régulières, affiche les versions disponibles, les versions installées...

Equivalent pour Debian ou Ubuntu de la commande eix de Gentoo.
---

Avec bash_completion.

Utilisation
---

    Usage : dix [options] <motif>

        Pour afficher l'aide : dix --help

    Recherche les versions disponibles ou installees des paquets 

    Options :
        -h, --help            affiche cette aide
        -e, --exact           limite les resultats aux paquets dont le nom
                                correspond exactement au motif
        --normal (defaut)     limite les resultats aux paquets dont le nom
                                contient le motif
        -s, --search          limite les resultats aux paquets dont le nom
                                ou la description courte correspondent au motif
        -f, --fullsearch      limite les resultats aux paquets dont le nom,
                                la description courte ou la description longue 
                                correspondent au motif
        -i, --installed       limite les resultats aux paquets installes
        -I, --not-installed   limite les resultats aux paquets non installes
        -n, --nocolor         desactive les couleurs

En savoir plus
---
[Page de description](http://www.nocturne-jdr.fr/blog/equivalent-eix-pour-debian-ubuntu/)
