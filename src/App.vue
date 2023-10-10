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
                <p>Bienvenuexs sur le site internet du&nbsp;Cinématographe</p>
            </section>
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
                        LOTO DE SOUTIEN 11 H 30 - 16 H 30, SALLE DES FÊTES DU CASINO DE&nbsp;MONTBENON
                        <br>VENEZ JOUER AU LOTO ET MANGER DES GATEAUX
                    </app-date>
                </div>
                <div
                        class="v-app__date_container"
                >
                    <app-date
                            date="15 octobre 2023"
                    >
                        LANCEMENT DE LA CAMPAGNE DE FINANCEMENT PARTICIPATIF <a
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
                                <p>ARTICLE DU 24 HEURES
                                    <br><a href="">LIRE L’ARTICLE </a>
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
                        Ouvert en 1981, le Cinématographe est une salle de cinéma de 102 places située au
                        Casino de Montbenon, au cœur de Lausanne. Propriété de la Ville de Lausanne, son exploitation et
                        sa
                        programmation sont conduites jusqu’à aujourd’hui par la Cinémathèque Suisse. Cette dernière
                        cessera
                        ses projections au Cinématographe à la fin de l’année 2023 pour déplacer ses activités publiques
                        au
                        cinéma Capitole rénové. À partir de 2024, la salle du Cinématographe sera gérée par une nouvelle
                        équipe.
                    </p>

                    <p>
                        Sélectionné par la Ville de Lausanne à la suite d’un appel à projets, le Collectif du
                        nouveau Cinématographe assurera la gestion, la programmation et l’exploitation de la salle dès
                        mars
                        2024. Au centre de notre projet réside l’envie de partager avec tous les publics un cinéma de
                        qualité en dialogue avec des enjeux de société contemporains. À travers un large choix de
                        sorties et de reprises, nous ferons la part belle aux nouveautés et valoriserons un spectre
                        varié
                        de films, réalisés tant par des cinéastes émergent·e·x·s que reconnu·e·x·s. La programmation
                        du
                        Cinématographe proposera également des cycles, des événements, une programmation destinée au
                        jeune
                        public, des actions de médiation et de nombreuses collaborations avec des festivals et des
                        ciné-clubs.
                    </p>

                    <p>
                        Durant l’automne 2023 et l’hiver 2024 le Collectif du nouveau Cinématographe organise
                        divers événements, afin de rencontrer les publics actuels et futurs de la salle. Pour mener à
                        bien
                        ce projet, nous comptons sur différents soutiens. Une collecte de fonds est lancée le 15 octobre
                        2023 pour répondre à nos besoins liés aux frais de reprise. Chaque contribution nous aidera à
                        subvenir aux coûts de rénovation de la salle, à améliorer les espaces d’accueil et à créer une
                        buvette conviviale.
                    </p>

                    <p>
                        Nous souhaitons faire du Cinématographe un lieu central de la vie culturelle
                        lausannoise défendant une culture inclusive et le plaisir du cinéma en salle. Rejoignez-nous
                        dans cette nouvelle&nbsp;aventure&nbsp;!
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
        }
    }

    .v-app__info__container__img {
        display: block;
        max-width: 10rem;
    }
}

</style>
