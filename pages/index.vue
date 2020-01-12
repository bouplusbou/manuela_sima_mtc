<template>
  <div class="text-gray-800">
    <header class="p-8">
      <p class="text-blue-600 text-center">
        {{ 'Manuela Sima - Energétique Traditionnelle Chinoise'.toUpperCase() }}
      </p>
    </header>
    <section class="relative">
      <div
        class="flex items-center justify-center"
        style="position: absolute; top: 0; left: 0; height: 100%; width: 100%"
      >
        <p class="text-3xl lg:text-6xl text-white text-center">
          Notre santé est entre nos mains
        </p>
      </div>
      <img src="~/assets/hands.jpg" alt="des mains de moine" />
    </section>
    <section class="p-12 lg:p-32 lg:flex lg:justify-around">
      <img
        style="height: 600px; width: auto; max-width: 400px"
        src="@/assets/manuela_sima.jpeg"
        alt="photo de Manuela Sima"
        class="mb-12 mx-auto lg:mb-0 lg:mr-16"
      />
      <div>
        <p class="text-blue-600 text-2xl">Manuela Sima</p>
        <p>
          A l’aide des outils de la Médecine Traditionnelle Chinoise (MTC), je
          propose un accompagnement non invasif vers le mieux être physique et
          émotionnel de toute personne désirant prendre soin de soi. Si nous
          sommes conscients que notre plus cher trésor est la santé, la
          préserver devient en même temps notre droit et notre devoir.
        </p>
        <br />
        <p>
          Membre du <a href="http://www.siattec.fr/">SIATTEC</a> , j’ai suivi le
          cursus de l’<a href="https://www.imtc.fr/"
            >Institut de Médecine Traditionnelle Chinoise</a
          >
          , proposant un programme d’enseignement approuvé et certifié par
          l’Université de Médecine Traditionnelle Chinoise de SHANGHAI et par
          l’Hôpital Central de Médecine Traditionnelle Chinoise de PEKIN. Des
          stages en hôpital à Shanghai m’ont permis d’observer et d’expérimenter
          les différentes techniques dans leur milieu d’origine.
        </p>
        <br />
        <p>
          Ouverte à d’autres points de vue considérant l’homme dans sa
          globalité, j’ai suivi également une formation en massage Abhyanga,
          approuvée par l’Académie Française d’Ayurveda.
        </p>
        <br />
        <p>
          J'attire l'attention des visiteurs de ce site sur le fait que les
          informations données, les pratiques décrites ou une éventuelle séance
          en énergétique traditionnelle chinoise, ne doivent en aucun cas avoir
          pour effet de retarder ou annuler une consultation auprès d'un médecin
          généraliste ou spécialiste qui seul peut établir un diagnostic,
          déterminer un traitement, prescrire la prise de médicaments ou encore
          décider de l'arrêt d'un traitement. Les séances au cabinet visent à un
          confort global ( corps et esprit ) et une régulation des énergies yin
          / yang , aspect fondamental de la médecine traditionnelle chinoise. Si
          vous êtes concerné par une rééducation auprès de votre
          masseur-kinésithérapeute, il conviendra également de veiller à son
          suivi.
        </p>
      </div>
    </section>
    <section class="lg:relative mb-20">
      <img src="~/assets/bamboos.jpg" alt="une foret de bambous" />
      <div
        style="top: 0; right: 0; width: 100%; height: 100%"
        class="lg:absolute flex items-center justify-end lg:mr-32"
      >
        <div class="boxy lg:p-4 p-12 text-white lg:mb-32">
          <style scoped>
            .boxy {
              width: 700px;
              background-color: #6d8e52;
            }
            @media (max-width: 1024px) {
              .boxy {
                width: 100%;
              }
            }
          </style>
          <p class="text-3xl mb-4">La Médecine Traditionnelle Chinoise</p>
          <p>
            La médecine chinoise est tout d’abord une philosophie de vie
            cherchant à comprendre l’être humain et à garder son équilibre dans
            son environnement.
          </p>
          <br />
          <p>
            Selon la tradition chinoise, l'être vivant est un réseau de
            méridiens énergétiques et une organisation résultant de la
            combinaison d’énergie grossière, proche de la matière, de nature
            yīn, et d'énergie subtile, moins visible, de nature yáng. En
            mouvement continu, l'équilibre harmonieux entre ces deux composantes
            conditionne l'état de santé. Les perturbations de cet équilibre sont
            responsables de la maladie.
          </p>
          <br />
          <p>
            Pour préserver la santé, la médecine chinoise cherche à comprendre
            l’origine du déséquilibre énergétique afin de traiter le mal à la
            racine.
          </p>
        </div>
      </div>
    </section>
    <section class="p-20 lg:px-32 mb-16 lg:mb-32">
      <p class="text-4xl text-blue-600 text-center mb-8">
        Les principaux outils et techniques
      </p>
      <p class="font-bold text-center sm:w-2/3 mx-auto mb-12">
        En fonction de votre état, chaque séance est unique et peut combiner ces
        outils dans l’objectif de rétablir un équilibre énergétique et retrouver
        un mieux être, vitalité et détente.
      </p>
      <div class="tools text-sm">
        <style scoped>
          .tools {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr 1fr;
            grid-gap: 25px;
          }
          @media (max-width: 1280px) {
            .tools {
              grid-template-columns: 1fr 1fr;
              grid-gap: 100px;
            }
          }
          @media (max-width: 640px) {
            .tools {
              grid-template-columns: 1fr;
            }
          }
        </style>
        <div>
          <img
            src="@/assets/tuina.jpg"
            alt="un massage tuina"
            class="mb-4 mx-auto lg:h-48 lg:w-auto w-full"
          />
          <p class="font-bold mb-4 text-center sm:text-left">
            Tuina (massages), normalisations et ventouses
          </p>
          <p>
            Ces techniques agissent principalement sur les méridiens
            énergétiques tendino-musculaires qui se trouvent le plus en surface
            sur le corps et font communiquer les articulations et les tendons
            pour favoriser le mouvement.
          </p>
          <br />
          <p>
            Elles cherchent à rétablir la libre circulation de l’énergie (Qi),
            du sang et des liquides organiques et ont comme principaux effets :
            la réduction de stress et des tensions, la stimulation et le
            renforcement du système immunitaire, l’équilibrage du système
            énergétique, la détente physique et psychique, et donc
            l’amélioration du bien-être.
          </p>
        </div>
        <div>
          <img
            src="@/assets/acupuncture.jpeg"
            alt="des points d'acupuncture"
            class="mb-4 mx-auto lg:h-48 lg:w-auto w-full"
          />
          <p class="font-bold mb-4 text-center sm:text-left">
            Stimulation des points d’Acupuncture Traditionnelle Chinoise
          </p>
          <p>
            Cette technique consiste en une stimulation des points précis de
            l'épiderme et situés sur les méridiens énergétiques. La stimulation
            peut être réalisée avec des aiguilles, moxa (bâton d’armoise
            chauffant), aimants ou tout moyen permettant de réaliser une
            pression ciblée.
          </p>
          <br />
          <p>
            Les points sont choisis en fonction du bilan énergétique réalisé au
            préalable et leur stimulation cherche à rétablir un équilibre
            énergétique et une libre circulation de l’énergie, du sang et des
            liquides organiques.
          </p>
        </div>
        <div>
          <img
            src="@/assets/dietetique.jpg"
            alt="un plat diététique"
            class="mb-4 mx-auto lg:h-48 lg:w-auto w-full"
          />
          <p class="font-bold mb-4 text-center sm:text-left">
            Diététique Traditionnelle Chinoise
          </p>
          <p>
            Il s’agit du premier outil à la main de chacun d’entre nous, la
            nourriture constituant la principale source d’énergie de notre
            corps. Il s’agit donc de favoriser la digestion et de choisir des
            aliments et des boissons en adéquation avec notre nature et avec les
            saisons.
          </p>
          <br />
          <p>
            Dans ce domaine, philosophie chinoise et grecque se rejoignent.
          </p>
          <br />
          <p>
            “Ainsi chaque saison aura des productions particulières, chaque
            terrain des plantes favorites et chaque homme ses mets qui lui
            conviennent. Ce que la saison n’a pas produit, ce que le sol n’a pas
            nourri, un homme sage ne l’offre pas.” (LI JI - Livre du Rituel).
          </p>
          <br />
          <p>
            "Que ta nourriture soit ta médecine, et ta médecine, ta nourriture."
            (Hippocrate 460-370 av J-C)
          </p>
        </div>
        <div>
          <img
            src="@/assets/pharmacopee.jpg"
            alt="pharmacopée chinoise"
            class="mb-4 mx-auto lg:h-48 lg:w-auto w-full"
          />
          <p class="font-bold mb-4 text-center sm:text-left">
            Pharmacopée Traditionnelle Chinoise
          </p>
          <p>
            Comme partout dans le monde et de tout temps, les êtres humains ont
            essayé d’extraire de leur environnement des substances,
            essentiellement des plantes, permettant de se préserver des maladies
            et de recouvrer la santé.
          </p>
          <br />
          <p>
            Les Chinois ont répertorié et classé ces substances selon leurs
            qualités énergétiques : leur nature qui s'exprime à travers un effet
            "thermique", leur saveur qui agit sur le mouvement et la direction
            de circulation de l’énergie et leur tropisme qui permet de polariser
            leur action sur certaines parties de l'organisme et certains
            méridiens énergétiques.
          </p>
          <br />
          <p>
            L’utilisation de ces substances, le plus souvent en décoction,
            favorise le rétablissement de l’équilibre énergétique.
          </p>
        </div>
      </div>
    </section>
    <section class="px-12 mb-32 md:flex md:justify-center">
      <div class="mb-12 text-center md:mt-12 md:mr-12 md:text-left">
        <p class="text-3xl font-medium text-blue-600 mb-8">HARQIMED</p>
        <p class="text-xl">
          5A rue de la Campanule <br />
          Le Clos Sénart <br />
          91270 <strong>VIGNEUX SUR SEINE</strong>
        </p>
      </div>
      <img
        style="height: 400px"
        src="@/assets/map.jpg"
        alt="une carte de vigneux-sur-Seine"
        class="mx-auto md:m-0"
      />
    </section>
    <section class="mb-32">
      <div class="w-2/3 mx-auto text-center">
        <p class="text-3xl font-medium text-blue-600 mb-8">Contactez-moi</p>
        <p>
          Pour prendre rendez-vous, vous pouvez me contacter <br />
          par téléphone ou par email.
          <br />
          <br />
          Téléphone: <strong class="text-xl">07 66 81 01 66</strong>
          <br />
          <br />
          Email: <strong class="text-xl">harqimed@gmail.com</strong>
        </p>
      </div>
    </section>
    <footer class="bg-gray-100 pt-16 pb-8 text-center text-xl">
      <p>
        Manuela Sima, Praticienne en Energétique Traditionnelle Chinoise dans
        l'Essonne 91
      </p>
    </footer>
  </div>
</template>

<script>
export default {}
</script>
