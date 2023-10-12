<template>
    <main class="v-app">
        <div
                class="v-app__header"
        >
            <AppHeader/>
        </div>

        <div
                class="v-app__content"
        >
            <section
                    class="v-app__section"
            >
                <h2>ACTUALITÉS</h2>

                <div
                        class="v-app__date_container"
                >
                    <app-date
                            date="12 novembre 2023"
                    >
                        Bienvenue dès 11h, Loto de 12h à 15h30 (pause de 14h à 14h30)
                        <br>Carton en vente sur place à 9.- Chf. Lots cumulables sur une même série. 1 série royale.
                        <br>Bar et petite restauration sur place (paiement en espèces)
                        <br>Salle des Fêtes du Casino de Montbenon
                    </app-date>
                </div>
                <div
                        class="v-app__date_container"
                >
                    <app-date
                            date="22 octobre 2023"
                    >
                        Lancement de la campagne de financement participatif wemakeit<a
                            href="/#">WEMAKEIT</a>
                    </app-date>
                </div>

                <div
                    class="v-app__info_container"
                >
                    <section class="v-app__info" >
                        <h3
                            class="v-app__info__title"
                        >Presse</h3>
                        <div
                            class="v-app__info__slot"
                        >
                            <div
                                class="v-app__info__slot__content"
                            >
                                <p>Stéphanie Arboit, «&nbsp;Le Cinématographe va projeter un nouveau chapitre de sa vie&nbsp;», 24 Heures, 11 juillet 2023
                                    <br><a href="https://www.24heures.ch/le-cinematographe-va-projeter-un-nouveau-chapitre-de-sa-vie-466711780457">LIRE L’ARTICLE </a>
                                </p>
                                <img
                                    class="v-app__info__container__img"
                                    alt="article cover"
                                    src="./assets/presse_24_heures_cinematographe.jpeg"
                                >
                            </div>

                            <div
                                class="v-app__info__slot__content"
                            >
                                <p>
                                    Alexandre Ducommun, « Un nouveau départ pour le Cinématographe », Cinébulletin, 11 juillet 2023
                                    <br><a href="https://cinebulletin.ch/fr_CH/news/un-nouveau-depart-pour-le-cinematographe">LIRE L’ARTICLE </a>
                                </p>

                                <img
                                    class="v-app__info__container__img"
                                    alt="article cover"
                                    src="./assets/presse_24_heures_cinematographe.jpeg"
                                >
                            </div>
                        </div>
                    </section>
                </div>

            </section>

            <section
                    class="v-app__section"
            >
                <h2>À PROPOS</h2>

                <div
                        class="v-app__text_content"
                >
                    <h4>Le Cinématographe</h4>

                    <p>
                        Ouvert en 1981, le Cinématographe est une salle de cinéma de 102 places située au Casino de Montbenon, au cœur de Lausanne. Propriété de la Ville de Lausanne, son exploitation et sa programmation sont conduites jusqu’à aujourd’hui par la Cinémathèque Suisse. Cette dernière cessera ses projections au Cinématographe à la fin de l’année 2023 en vue de déplacer ses activités publiques au cinéma Capitole rénové. À partir de 2024, la salle du Cinématographe sera gérée par une nouvelle équipe.
                    </p>
                    <p>
                        Sélectionné par la Ville de Lausanne à la suite d’un appel à projets, le Collectif du nouveau Cinématographe assurera la gestion, la programmation et l’exploitation de la salle dès mars 2024. Au centre de notre projet réside l’envie de partager avec tous les publics un cinéma de qualité en dialogue avec des enjeux de société contemporains. À travers un large choix de sorties et de reprises, nous ferons la part belle aux nouveautés et valoriserons un spectre varié de films, réalisés tant par des cinéastes émergentexs que reconnuexs. La programmation du Cinématographe offrira également des cycles, des événements, une programmation destinée au jeune public, des actions de médiation et de nombreuses collaborations avec des festivals et des ciné-clubs.
                    </p>
                    <p>
                        Durant l’automne 2023 et l’hiver 2024, le Collectif du nouveau Cinématographe organise divers événements afin de rencontrer les publics actuels et futurs de la salle. Pour mener à bien notre projet, nous comptons sur différents soutiens. Une collecte de fonds est lancée le 22 octobre 2023 pour répondre à nos besoins liés aux frais de reprise. Chaque contribution nous aidera à subvenir aux coûts de rénovation de la salle, à améliorer les espaces d'accueil et à créer une buvette conviviale.
                    </p>
                    <p>
                        Nous souhaitons faire du Cinématographe un lieu central de la vie culturelle lausannoise défendant une culture pour touxtes et le plaisir du cinéma en salle. Rejoignez-nous dans cette nouvelle aventure&nbsp;!
                    </p>


                    <h6>
                        Nota bene Si vous cherchez le programme actuel du Cinématographe, rendez&#x2011;vous sur le site
                        internet de la <a href="https://live.cinematheque.ch/" target="_blank">Cinémathèque Suisse.</a>
                    </h6>

                    <h2>L’ÉQUIPE</h2>

                    <p>
                        Nous sommes quatre professionnelle·x·s de la culture, forte·x·s d’expériences dans le domaine
                        cinématographique, allant de l’exploitation de salles, la programmation en festivals, l’enseignement
                        universitaire, à la gestion de projets et la médiation culturelle. Aujourd’hui, nous mettons en
                        commun nos compétences pour assurer un avenir cinéphile, vivant et inclusif au Cinématographe.
                    </p>
                    <p>
                        Meli Boss
                        <br/>Faye Corthésy
                        <br/>Gysèle Giannuzzi
                        <br/>Alice Riva
                    </p>
                </div>
            </section>
        </div>

        <app-footer/>
    </main>
</template>


<script lang="ts" setup>
import AppHeader from "./components/AppHeader.vue";
import AppDate from "./components/AppDate.vue";
import AppFooter from "./components/AppFooter.vue";

</script>


<style lang="scss" scoped>
.v-app {
  overflow: hidden;
  padding-top: var(--lc-header-height);
}

.v-app__header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
}

.v-app__date_container {
  & + & {
    margin-top: 2rem;
  }
}

.v-app__info_container {
    .v-app__info__slot {
        box-sizing: border-box;
        padding-left: 5rem;

        @media (max-width: 900px) {
            padding-left: 0;
        }

        .v-app__info__slot__content {
            border-top: solid 1px white;
            border-bottom: solid 1px white;
            padding-top: 1rem;
            padding-bottom: 1rem;

            > p {
                max-width: 25rem;
            }
        }
    }

    .v-app__info__container__img {
        display: block;
        width: 100%;
        max-width: 10rem;
    }
}

</style>
