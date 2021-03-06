<i18n>
  {

  "en": {

  "page-title": "The Cause of Health",

  "health-heading": "What is Health?",
  "health-text-1": "The UN World Health Organization notes in its <a href='https://www.who.int/about/who-we-are/constitution' target='_blank'>constitution</a> that “Health is a state of complete physical, mental and social well-being and not merely the absence of disease or infirmity”. Health is hence much more than just a biomedical condition.",
  "health-subheading": "The «Cause of Health»",
  "health-text-2": "The Swiss Cause of Health Cohort initiative is built on the premise that an individual's health is determined by the Health Triangle, a complex interplay between a unique individual (genome), the environment, and the individual’s behaviour in the environment.",
  "health-text-3": "To understand this complexity we need standardized longitudinal sets of health data from millions of people. Such data sets form the basis of precision health or P4 (personalized, predictive, preventive and participatory) health.",

  "understanding-heading": "Understanding the «Cause of Health» with Citizen Science",
  "understanding-text-1": "Switzerland has a long tradition in classical health cohorts (CoLaus, Sapladia, AIDS, Swiss Transplant). However, these cohorts are small (< 10’000 participants) and solely based on examinations in hospitals, thus expensive to maintain.",
  "understanding-text-2": "The development of smartphone-based sensors, the increasing use of health related apps and wearables, and the rapidly decreasing costs in genome sequencing, give hope for the establishment of much larger digital health cohorts (>100’000), that rely on the active participation of citizens (citizen science).",

  "cohcoh-heading": "The Swiss «Cause of Health» Cohort (COHCOH)",
  "cohcoh-text-1": "The “Swiss Cause of Health Cohort” is initiated by swiss scientists, who make their personal data available to pave the way for superior personalized medicine in Switzerland. A secure database with unique governance structure (non-profit citizen-controlled MIDATA cooperative) allows individuals to control their own data.",
  "cohcoh-text-2": "The cohort is open for everyone to join, and scalable within Europe.",
  "cohcoh-button": "Learn more"


  },
  "de": {

  "page-title": "The Cause of Health",

  "health-heading": "Was ist Gesundheit?",
  "health-text-1": "Die UN Weltgesundheitsorganisation hält in ihrer <a href='https://www.who.int/about/who-we-are/constitution' target='_blank'>Verfassung</a> fest: “Gesundheit ist ein Zustand des vollständigen körperlichen, geistigen und sozialen Wohlergehens und nicht nur das Fehlen von Krankheit oder Gebrechen.“ Gesundheit ist so gesehen viel mehr als nur ein biomedizinischer Zustand.",
  "health-subheading": "«Cause of Health»",
  "health-text-2": "Die Schweizerische “Cause of Health” Initiative ist auf das “Gesundheitsdreieck” ausgerichtet, der komplexen Wechselbeziehung zwischen einzigartigem Individuum (Genom), dessen Umwelt und Verhalten darin.",
  "health-text-3": "Nur über das Studium von standardisierten longitudinalen Gesundheitsdaten von millionen von Menschen können wir hoffen in nicht zu ferner Zukunft die Komplexität des Gesundheitsdreiecks zu verstehen. Damit werden diese Daten zur Basis der personalisierten Präzisionsmedizin (P4 - personalized, predictive, preventive, and participatory).",

  "understanding-heading": "Citizen Science hilft bei der Entschlüsselung des Gesundheitsdreiecks",
  "understanding-text-1": "Die Schweiz hat eine lange Tradition in der Durchführung klassischer Gesundheitskohorten (CoLaus, Sapladia, AIDS, Swiss Transplant). Allerdings sind diese Kohorten bei weitem nicht gross genug (< 10’000 Teilnehmer) und sie stützen sich ausschliesslich auf Untersuchungsergebnis in Spitälern ab; ihre Durchführung verursacht ausserdem hohe Kosten.",
  "understanding-text-2": "Mit der Integration von mobilen Sensoren in Smartphonen und Smartwatches, der Entwicklung und Verbreitung von Gesundheits/Fitness Apps, schnell sinkenden Kosten der Genomanalyse, wird es möglich viel grössere (> 100’000) digitale Gesundheitskohorten zu etablieren, unter aktiver Beteiligung der Bevölkerung (Citizen Science).",

  "cohcoh-heading": "Die Schweizerische “Cause of Health Kohorte” (Swiss COHCOH)",
  "cohcoh-text-1": "Die Schweizerische “Cause of Health Kohorte” wird von Wissenschaftlern in der Schweiz mit Ihren eigenen Gesundheitsdaten gestartet um die Personalisierte Medizin der Zukunft zu ermöglichen.",
  "cohcoh-text-2": "Alle persönlichen Gesundheitsdaten werden auf einer einzigartigen Datenplattform gespeichert. Diese garantiert sichere Aufbewahrung in einem verschlüsselten persönlichen Datenkonto der Teilnehmer (nicht Gewinnorientierte und von Bürgern kontrollierte <a href='https://www.midata.coop' target='_blank'>MIDATA Genossenschaft</a>).",
  "cohcoh-button": "Mehr erfahren"


  }

  }
</i18n>

<template>
  <div>

    <app-content-section class="overflow-hidden">
      <div class="background-wrapper background-wrapper-move-right scroll-effect scroll-effect-delayed-1">
        <div class="content-wrapper">
          <div class="row row-centered">
            <div class="col col-tablet-portrait-10 col-large-6 col-wrapping">
              <div class="extra-padding">
                <img src="/img/graphic-intro.png"/>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="content-wrapper">
        <div class="row row-wrapping">
          <div class="col col-tablet-portrait-7 col-large-6 col-large-before-1 col-wrapping scroll-effect">
            <h2 class="heading centered left-aligned-large">{{ $t('health-heading') }}</h2>
            <p v-html="$t('health-text-1')"></p>
            <h2 class="subheading centered left-aligned-large">{{ $t('health-subheading') }}</h2>
            <p v-html="$t('health-text-2')"></p>
            <p v-html="$t('health-text-3')"></p>
          </div>
        </div>
      </div>
    </app-content-section>

    <app-content-section class="overflow-hidden" color="light-greyish">
      <div class="background-wrapper background-wrapper-move-left scroll-effect scroll-effect-delayed-1">
        <div class="content-wrapper">
          <div class="row row-centered">
            <div class="col col-tablet-portrait-10 col-large-6 col-wrapping">
              <div class="extra-padding">
                <img src="/img/graphic-data-sources.png"/>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="content-wrapper">
        <div class="row row-wrapping">
          <div class="col col-tablet-portrait-7 col-large-6 col-large-before-5 col-wrapping scroll-effect">
            <h2 class="heading centered left-aligned-large">{{ $t('understanding-heading') }}</h2>
            <p v-html="$t('understanding-text-1')"></p>
            <p v-html="$t('understanding-text-2')"></p>
          </div>
        </div>
      </div>
    </app-content-section>

    <app-content-section>
      <div class="content-wrapper">
        <div class="row row-centered row-middle row-reverse-large row-wrapping">

          <div class="col col-10 col-tablet-portrait-8 col-large-6 col-wrapping scroll-effect">
            <div>
              <div class="extra-padding-large-h">
                <img src="/img/graphic-cohcoh.png"/>
              </div>
            </div>
          </div>

          <div class="col col-large-5 col-large-before-1 col-wrapping scroll-effect scroll-effect-delayed-1">
            <div>
              <h2 class="heading centered left-aligned-large">{{ $t('cohcoh-heading') }}</h2>
              <p v-html="$t('cohcoh-text-1')" class="reduced-bottom-margin"></p>
              <p v-html="$t('cohcoh-text-2')" class="reduced-bottom-margin"></p>
              <div class="button-group centered left-aligned-large">
                <router-link tag="button" to="/swiss-cohcoh" class="button button-secondary">{{ $t('cohcoh-button') }}</router-link>
              </div>
            </div>
          </div>

        </div>
      </div>
    </app-content-section>

    <section-feedback email="cohcoh@citizenscience.ch" color="light-greyish" ></section-feedback>

    <app-footer></app-footer>

  </div>
</template>

<script>

    import {mapState} from 'vuex'

    import ContentSection from '@/components/shared/ContentSection.vue';
    import Footer from '@/components/shared/Footer.vue';
    import SectionNewsletterSignup from "@/components/shared/SectionNewsletterSignup";
    import SectionFeedback from "../components/shared/SectionFeedback";

    export default {
        components: {
            SectionFeedback,
            SectionNewsletterSignup,
            'app-content-section': ContentSection,
            'app-footer': Footer
        },
        metaInfo: function() {
            return {
                title: this.$t('page-title'),
                meta: [
                    {
                        property: 'og:title',
                        content: this.$t('page-title'),
                        template: '%s | '+this.$t('site-title')
                    }
                ]
            }
        },
        computed: {
            ...mapState({
                user: state => state.c3s.user
            })
        }
    }

</script>

<style lang="scss">

</style>
