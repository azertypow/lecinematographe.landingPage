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
            <div
                class="v-app__newsletter-container"
            >
                <form
                    method="post"
                    action="https://newsletter.infomaniak.com/external/submit"
                    class="v-app__newsletter-container__form"
                    target="_blank"
                >
                    <input
                        type="email"
                        name="email"
                        style="display:none"
                    />
                    <input type="hidden"
                           name="key"
                           value="eyJpdiI6ImxEQmYwMU52ZkM0OGl4TlBVQWs4YmJtb1wvZ2Q0MkpIcGlZY3RPblZGeUxZPSIsInZhbHVlIjoiVEpHXC93ZVwvcCtPMTFnMGNTclpuU1RRMzNLZ1pKdUV2dVF4bjVnV05HUW1JPSIsIm1hYyI6IjE4NjNiNjNhYzY2MTE4YmFlNmQ0NmQ2ZDg3MWE1ZmY0YTEyYzFhZDU4NTQzZjNiMzdjY2I5ZGUzMTVkYTk3MWMifQ=="
                    >
                    <input
                        type="hidden"
                        name="webform_id"
                        value="15422"
                    >

                    <div class="inf-main_76f376382a50bd4859e50a81e701da10">
                        <h4>Newsletter</h4>
                        <div class="inf-success" style="display:none"><h4>C'est tout bon, merci !</h4>
                            <p><a href="#" class="inf-btn">&laquo;</a></p>
                        </div>
                        <div class="inf-content">
                            <input
                                type="email"
                                name="inf[1]"
                                data-inf-meta="1"
                                data-inf-error="Merci de renseigner une adresse email"
                                required
                                placeholder="Votre Email"
                            >
                            <input type="submit"
                                   name=""
                                   value="Envoyer"
                            >
                        </div>
                    </div>
                </form>
            </div>
            <section
                    class="v-app__section"
            >
                <div style="padding-top: 2rem; padding-bottom: 1rem;">
                    L'équipe du Cinématographe vous souhaite une très bonne année et se réjouit de vous retrouver <span style="color: var(--lc-color)">le&nbsp;20&nbsp;mars 2024</span> pour l’ouverture officielle de la&nbsp;salle.
                </div>

                <h2>ACTUALITÉS</h2>

                <app-date date="Levée de fonds Wemakeit">
                    Un grand merci pour tous vos partages et soutiens. Grâce à votre aide, nous allons pouvoir démarrer les travaux de mise en place de notre buvette en février. On a hâte de vous y&nbsp;accueillir!
                </app-date>

                <h3 style="padding-top: 1rem; color: var(--lc-color); text-transform: uppercase">Évènements passés</h3>

                <div
                        class="v-app__date_container"
                >
                    <app-date
                            date="12 novembre 2023"
                            src="./instagram_loto.jpeg"
                    >
                        Loto de soutien
                        <br>Bienvenue dès 11h, Loto de 12h à 15h30 (pause de 14h à 14h30)
                        <br>Cartons à usages multiples. Lots cumulables sur une même série. 1 série royale.
                        <br>Bar et petite restauration sur place (paiement en espèces)
                        <br>Salle des Fêtes du Casino de Montbenon
                    </app-date>
                </div>
                <div
                        class="v-app__date_container"
                >
                    <app-date
                            date="29 octobre 2023"
                    >
                        Lancement de la campagne de financement participatif wemakeit<a
                            target="_blank"
                            href="https://wemakeit.com/projects/le-nouveau-cinematographe">WEMAKEIT</a>
                    </app-date>
                </div>

                <div
                    class="v-app__info_container"
                >
                    <section class="v-app__info" >
                        <h2
                            class="v-app__info__title"
                        >Presse</h2>
                        <div
                            class="v-app__info__slot"
                        >
                            <div
                                class="v-app__info__slot__content"
                            >
                                <p>Stéphanie Arboit, «&nbsp;Le Cinématographe va projeter un nouveau chapitre de sa vie&nbsp;», 24 Heures, 11 juillet 2023
                                    <br><a
                                            target="_blank"
                                            href="https://www.24heures.ch/le-cinematographe-va-projeter-un-nouveau-chapitre-de-sa-vie-466711780457"
                                        >LIRE L’ARTICLE </a>
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
                                    <br><a
                                        target="_blank"
                                        href="https://cinebulletin.ch/fr_CH/news/un-nouveau-depart-pour-le-cinematographe"
                                    >LIRE L’ARTICLE </a>
                                </p>

                                <img
                                    class="v-app__info__container__img"
                                    alt="article cover"
                                    src="./assets/article_2.jpeg"
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
                        Durant l’automne 2023 et l’hiver 2024, le Collectif du nouveau Cinématographe organise divers événements afin de rencontrer les publics actuels et futurs de la salle. Pour mener à bien notre projet, nous comptons sur différents soutiens. Une collecte de fonds est lancée le 29 octobre 2023 pour répondre à nos besoins liés aux frais de reprise. Chaque contribution nous aidera à subvenir aux coûts de rénovation de la salle, à améliorer les espaces d'accueil et à créer une buvette conviviale.
                    </p>
                    <p>
                        Nous souhaitons faire du Cinématographe un lieu central de la vie culturelle lausannoise défendant une culture pour touxtes et le plaisir du cinéma en salle. Rejoignez-nous dans cette nouvelle aventure&nbsp;!
                    </p>


                    <h6>
                        <strong>Nota bene</strong>&nbsp;: Si vous cherchez le programme actuel du Cinématographe, rendez&#x2011;vous sur le site
                        internet de la <a href="https://live.cinematheque.ch/" target="_blank">Cinémathèque Suisse.</a>
                    </h6>

                    <h2>L’ÉQUIPE</h2>

                    <p>
                        Nous sommes quatre professionnellexs de la culture, fortexs d'expériences dans le domaine
                        cinématographique, allant de l'exploitation de salles, la programmation en festivals, l’enseignement
                        universitaire, à la gestion de projets et la médiation culturelle. Aujourd'hui, nous mettons en
                        commun nos compétences pour assurer un avenir cinéphile, vivant et inclusif au Cinématographe.
                    </p>
                    <p>
                        Meli Boss
                        <br/>Faye Corthésy
                        <br/>Gysèle Giannuzzi
                        <br/>Alice Riva
                    </p>
                    <p>Nous contacter
                        <br><a target="_blank" href="mailto:nouveau-cinematographe@proton.me" >nouveau-cinematographe@proton.me</a>
                    </p>

                    <h2>Nous soutenir</h2>
                    <div style="display: grid; grid-template-columns: repeat(1, 1fr) repeat(1, 10fr); gap: .5rem" >
                        <div>
                            <div>iban:</div>
                            <div>BIC:</div>
                            <div>Nom:</div>
                        </div>
                        <div>
                            <div>CH52 0900 0000 1624 8177 6</div>
                            <div>POFICHBEXXX</div>
                            <div>Collectif du nouveau Cinématographe Lausanne</div>
                        </div>
                    </div>
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

.v-app__newsletter-container {
    background: var(--lc-color);
    margin-top: 4rem;
    margin-bottom: 2rem;
}

.inf-main_76f376382a50bd4859e50a81e701da10 {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    padding: .5rem .5rem;
    box-sizing: border-box;

    h4 {
        margin: 0;
    }

    @media (max-width: 1100px) {
        flex-direction: column;
    }
}

.inf-content {
    display: flex;
    align-items: center;
    box-sizing: border-box;

    @media (max-width: 1100px) {
        width: 100%;
        flex-direction: column;
    }

    > input {
        font-family: "DIN Dong", Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
        box-sizing: border-box;
        border: none;
        display: block;
        font-size: inherit;
        line-height: inherit;
        height: 1rem;
        max-width: 100%;

        @media (max-width: 1100px) {
            margin-top: .5rem;
            margin-bottom: .5rem;
        }
    }

    [type="email"] {
        background: transparent;
        border-bottom: solid 2px white;
        color: white;

        &::placeholder {
            color: white;
        }

        &:focus-visible {
            outline: none;
        }

        @media (max-width: 1100px) {
            margin-top: 1rem;
        }
    }

    > input[type="submit"] {
        font-size: .5rem;
        margin-left: .5rem;
    }
}

</style>
