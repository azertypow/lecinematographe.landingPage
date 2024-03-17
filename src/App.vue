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
                <h2 style="background: var(--lc-color--secondary)" >Pré-ouverture</h2>

                <app-date date="19.03.24 - RIPPLES OF LIFE">
                    <p>
                        Surprise! Le Cinématographe vous invite à sa *Pré-ouverture* le 19 mars 2024 20h
                        <br/>Ripples of Life (2021), en présence du réalisateur Wei Shujun
                    </p>

                    <h4>Synopsis</h4>
                    <p>
                        Un tournage a lieu dans la petite ville reculée de Yong’an. La venue de l’équipe du film bouleverse Gu, la patronne d’un petit restaurant. Elle rêve d’une autre vie et se fraie une place sur le tournage. Chen, devenue star de cinéma, revient dans sa ville natale où elle espère retrouver ses amie.x.s d'enfance et de bons souvenirs. Un débat sans fin persiste entre le réalisateur et le scénariste. Le tournage doit commencer, bien que le consensus ne soit jamais atteint
                    </p>
                    <p>
                        Né à Pékin, Wei Shujun a commencé sa carrière dans le cinéma en tant qu’acteur à l’âge de 14 ans. Il est diplômé de l'Université de la Communication de Pékin. Son court métrage On the Border a reçu une mention spéciale à Cannes en 2018 ; son film Striding into the Wind était sélectionné en compétition en 2020, et son dernier long métrage Only the River Flows en séléction Un Certain Regard à Cannes l’année dernière.
                    </p>

                    <a
                        class="v-app__inscription-container"
                        target="_blank"
                        href="mailto:billetterie@lecinematographe.ch?subject=R%C3%A9servation%20billet%20-%20site&body=Bonjour%2C%0D%0A%0D%0AJ'aimerais%20r%C3%A9server%20pour%20la%20pr%C3%A9-ouverture%20du%2019%20mars%20ou%20l'ouverture%20du%2020%20mars.%0D%0A%0D%0A%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%0D%0A%0D%0ADate%20ou%20Titre%20du%20film%3A%0D%0A%0D%0ANombre%20de%20places%20(indiquer%20pr%C3%A9cis%C3%A9ment%20tarif%3A%20(normal%2015.%E2%80%94%20%2F%20soutien%2020.%E2%80%94%20%2F%20AVS%2C%20AI%2C%20en%20formation%2C%20ch%C3%B4mage%2012.%E2%80%94)%0D%0A%0D%0ANom%20et%20pr%C3%A9nom%20(1%20par%20r%C3%A9servation)%3A%0D%0A%0D%0ANum%C3%A9ro%20de%20t%C3%A9l%C3%A9phone%3A%0D%0A%0D%0A%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%0D%0A%0D%0A%0D%0AMerci!"
                    >
                        <h4>S'inscrire pour la Pré-ouverture</h4>
                    </a>

                    <img src="/images/Ripples_of_Life.jpeg"
                         alt="image pour le film RIPPLES OF LIFE"
                    >

                    <h4>🍇 Infos billetterie</h4>
                    <p>
                        Réservation via <a target="_blank"
                                           href="mailto:billetterie@lecinematographe.ch?subject=R%C3%A9servation%20billet%20-%20site&body=Bonjour%2C%0D%0A%0D%0AJ'aimerais%20r%C3%A9server%20pour%20la%20pr%C3%A9-ouverture%20du%2019%20mars%20ou%20l'ouverture%20du%2020%20mars.%0D%0A%0D%0A%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%0D%0A%0D%0ADate%20ou%20Titre%20du%20film%3A%0D%0A%0D%0ANombre%20de%20places%20(indiquer%20pr%C3%A9cis%C3%A9ment%20tarif%3A%20(normal%2015.%E2%80%94%20%2F%20soutien%2020.%E2%80%94%20%2F%20AVS%2C%20AI%2C%20en%20formation%2C%20ch%C3%B4mage%2012.%E2%80%94)%0D%0A%0D%0ANom%20et%20pr%C3%A9nom%20(1%20par%20r%C3%A9servation)%3A%0D%0A%0D%0ANum%C3%A9ro%20de%20t%C3%A9l%C3%A9phone%3A%0D%0A%0D%0A%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%C2%B7%0D%0A%0D%0A%0D%0AMerci!"
                    >billetterie@lecinematographe.ch</a>
                    </p>
                    <p>Merci d'indiquer clairement:</p>
                    <ul>
                        <li>la séance choisie (titre du film et date),</li>
                        <li>le nombre de billets et tarifs (20 CHF soutien,</li>
                        <li>15 CHF plein, 12 CHF réduit),</li>
                        <li>ainsi que Nom/Prénom/Numero de téléphone par réservation.</li>
                    </ul>

                    <p>Paiement (cash, carte, twint) au moment du retrait au Cinématographe.</p>


                </app-date>


                <h2 style="background: var(--lc-color--ternary);" >OUVERTURE</h2>

                <app-date date="20 mars 2024 - SOIREE D'OUVERTURE (FILM COMPLET - bienvenuexs à l’apéritif)">
                    <p>
                        18h : apéritif et mot de bienvenue
                        <br>20h : Blackbird Blackbird Blackberry (2023), avant-première en présence de lae réalisateurice Elene Naveriani, suivi d’un q&a
                    </p>

                    <h4>Synopsis</h4>
                    <p>Etero,48 ans, vit dans un petit village de Géorgie. Elle n'a jamais voulu de mari. Elle chérit sa liberté, mais son choix de vivre seule fait l’objet de nombreux commérages de la part du voisinage. Lorsqu’elle tombe passionnément amoureuse d'un homme, elle se retrouve contrainte de faire un choix - poursuivre cette relation ou continuer à mener une vie indépendante. Etero doit faire face à ses sentiments et tenter de trouver son propre chemin vers le bonheur.</p>

                    <h4>Lae cinéaste</h4>
                    <p>
                        Elene Naveriani a étudié la peinture à la State Academy of Art de Tbilissi. En 2011, iel a obtenu son master en études critiques curatoriales cybermédias, en 2014 son bachelor en cinéma à la Haute école d’art et de design de Genève. Son premier long métrage I Am Truly a Drop of Sun on Earth a été présenté en première à l’IFFR et primé aux festivals Entrevues de Belfort et à Valladolid. Wet Sand a été présenté en première à Locarno où il a remporté le Pardo du meilleur acteur.
                    </p>

                    <img src="/images/blackbird.jpeg"
                         alt="image pour le film Blackbird Blackbird Blackberry"
                    >
                </app-date>


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
                        <br><a target="_blank" href="mailto:contact@lecinematographe.ch" >contact@lecinematographe.ch</a>
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

.v-app__inscription-container {
    display: block;
    background: var(--lc-color--secondary);
    padding: .5rem;
    color: inherit;
    text-decoration: inherit;

    &:before, &:after {
        content: '';
    }

    > *:first-child {
        margin-top: 0 !important;
    }

    > *:last-child {
        margin-bottom: 0 !important;
    }
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
