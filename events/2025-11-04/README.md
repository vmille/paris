Soixante-et-unième édition du C++ French User Group (C++Frug) Paris. Cette session sera hybride:

    Algolia nous accueillera proche de Saint Lazare, 3-5 rue de Bucarest 75008 Paris
    Streaming sur Discord

Avant de venir, vous pouvez rejoindre les serveurs Discord (https://discord.gg/tjx9bFpBfC & https://discord.gg/9aU6tZabJV). L'application Discord est plus stable que la version web.

Programme de la soirée (heure de Paris):

    19h00 Welcome
    19h15 News of the C++ ecosystem
    19h20 Lightning talks or TBA talk
    19h50 Snacks & drinks
    20h30 Bertrand Le Mée : sccache + Conan: Réparer les fondations sans tout casser

Si vous êtes intéressé pour présenter, vous pouvez nous joindre via Discord ou MP meetup.

-------------------
Bertrand Le Mée : sccache + Conan: Réparer les fondations sans tout casser
Notre codebase C++ a plus de 10 ans, tourne sur des milliers de serveurs en production, et on continue d'y shipper des features régulièrement. Mais on était confrontés aux deux plaies classiques de l'écosystème : temps de compilation interminables et gestion de dépendances cauchemardesque.

Concrètement : impossible de partager du code entre équipes sans tout réécrire, des dépendances vendorisées dans Git, et des builds qui varient entre machines de dev, CI, et prod.

Dans ce talk, je partagerai notre parcours pour résoudre ces problèmes sur une vraie codebase legacy :

- Compilation : Quels outils nous avons adopté pour éviter des modifications massives de la codebase: runs-on, sccache (Mozilla) pour du cache distribué, après avoir testé d'autres solutions qui nous ont planté en prod
- Dépendances : Notre migration vers Conan pour sortir du vendor hell et enfin partager du code entre projets

Pas de projet greenfield ici : du REX concret sur comment améliorer un système existant, avec les erreurs qu'on a faites et ce qui a vraiment marché.