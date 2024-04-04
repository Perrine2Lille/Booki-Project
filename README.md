# **BOOKI**

Page d'un site responsive internet qui mixe AirBnb et GetYourguide en proposant des logements
dans des villes françaises mais aussi des activités.
Le site est développé en html et css only
Ajout perso d'un fichier prettier pour le formatage et d'un fichier normalize pour retirer les marges automatiques des navigateurs.

# **Architecture de l'application**

On enveloppe le code avec les balises html et body

## Header

            <header>

            <img> logo Booki

            <nav>

            <a href #hebergements> ancre qui mène à la section
            <a href #activités> ancre qui mène à la section

            </nav>

        </header>

        <main>

## Main

Le main comporte 4 sections : Recherche & Filtres / Hébergements / Les plus populaires / Activités

### Recherche et filtres (Slogan, barre de recherche, filtres)

            <section "recherche et Filtres">

                <div>

                    <h1> title = Trouvez votre hébergement (...)
                    <p> title = En plein centre-ville (...)

                </div>

                <form>

                    <i> icon
                    <input> txt recherche "Marseille, France" par défaut
                    <button> "Rechercher" en desktop
                    ||
                    <button> icon loupe en mobile

                </form>

                <div> Filtres - hover bleu

                    <button><i> icon + txt eco
                    <button><i> icon + txt familial
                    <button><i> icon + txt romantique
                    <button><i> icon + txt pépites

                </div>

            </section>

### Hébergements (6 cards)

            <section hebergements>

                <h2> Hebergement Marseille </h2>

                <a href#> cards cliquables X 6
                <article>

                    <img> position horizontal et objectfit
                    <h3> title
                    <p> subtitle
                    <i> rating

                </article>
                </a>

            </section>

### Les plus populaires (3 cards)

            <section populaires>

                <h2> Les plus populaires </h2>

                    <a href#> cards cliquables X 3
                    <article>

                        <img>position verticale et objectfit
                        <h3> title
                        <p> subtitle
                        <i> rating

                    </article>
                    </a>

### Activités ( 4 cards)

            <section activities> (en vertical) X 4

                <h3> title

                    <a href#>
                    <article>

                        <img>
                        <p> subtitle

                    </article>
                    </a>

            </section>

    </main>

## Footer

3 colonnes / 3 listes Ul

    <footer>

        <nav>
            <ul> A propos - Nos Hébergements - Assistance
                <li> XXXXX
                <li> YYYYY
                <li> ZZZZZ
            </ul>
        </nav>

    </footer>
