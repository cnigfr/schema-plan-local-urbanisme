# Plan local d'urbanisme (PLU)

## Description

Le [géostandard CNIG PLU](https://cnig.gouv.fr/ressources-dematerialisation-documents-d-urbanisme-a2732.html) définit le contenu et la structure des informations de description des PLU et PLU intercommunaux (PLUi).

Il vise à assurer l'interopérabilité des données géographiques et littérales des documents d’urbanisme vis à vis des infrastructures de données géographiques et notamment du [Géoportail de l’urbanisme](https://www.geoportail-urbanisme.gouv.fr/).

Il s’appuie sur le Code de l'urbanisme recodifié par l’ordonnance n° 2015-1174 du 23 sept. 2015.

Elaboré par le groupe de travail CNIG pour la dématérialisation des document d'urbanisme ([GT CNIG DDU](https://cnig.gouv.fr/gt-ddu-a2918.html)), il s'intègre dans une gamme de différents géostandards du domaine de l'urbanisme : standards carte communale, SCOT, Plan de sauvegarde et de mise en valeur (PSMV) et servitudes d’utilité publique (SUP).

Ce standard détermine, entre autres :
- le modèle conceptuel des données, le catalogue d’objets et son implémentation
- les règles d’organisation et de codification des données (notamment le format, l’organisation et le nommage des fichiers)
- les règles de topologie (la structuration des données spatiales)
- le système de géoréférencement (l’attribution de coordonnées géographiques)

Le périmètre du modèle conceptuel de données englobe les notions relatives aux zones d’urbanisme, prescriptions d'urbanisme, annexes informatives et habillage graphique.

## Objectif

- disposer du document d'urbanisme sous forme numérique et le publier sur le Géoportail de l’urbanisme
  - répondre aux obligations réglementaires de publication du document pour le rendre exécutoire
  - simplifier l'accès au document
  - faciliter l’échange d’informations entre collectivités territoriales et services de l'Etat, par exemple pour le contôle de légalité
- communiquer l'information aux citoyens via le Géoportail de l’urbanisme
  - viser à terme la mise en ligne des possibilités de construire permettant à tout citoyen de connaître, pour une parcelle de terrain, les contraintes réglementaires susceptibles de s’appliquer.
- faciliter l’échange d’informations entre l’administration, les professionnels et les citoyens, avec rapidité et en toute transparence
- faciliter l’instruction des actes d’urbanisme (permis de construire, permis d’aménager, etc.)
- construire une mémoire collective et pérenne
  - retracer l'historique des procédures d'urbanisme successives
  - faciliter la gestion et le suivi des PLU par les autorités compétentes
- alimenter tous types de systèmes d'information (aménagement du territoitre, artificialisation des sols, sobriété foncière, etc.) exploitant les informations d'urbanisme.

Afin d’optimiser les processus de production et de minimiser les écarts géométriques et descriptifs entre versions « papier » et dématérialisée du PLU, le CNIG recommande que la production de la version dématérialisée par numérisation des documents papier soit désormais remplacée par une élaboration directement sous forme numérique, permettant ensuite l’impression papier à partir de ces éléments numériques.

## GT CNIG Dématérialisation des documents d'urbanisme ([GT CNIG DDU](https://cnig.gouv.fr/gt-ddu-a2918.html#H_Groupe-de-travail-DDU))

Le Groupe de travail "Dématérialisation des documents d’urbanisme" (GT CNIG DDU) vise à standardiser la dématérialisation, l'exploitation et la publication des documents d'urbanisme juridiquement opposables.

Son fonctionnement est régi par ce [mandat du CNIG](https://cnig.gouv.fr/IMG/pdf/180702_mandat_gt_ddu_cnig.pdf).

Il est piloté par la Direction générale à l'aménagement le logement et la nature (DGALN) du Ministère de la transition écologique. Il est animé par le CEREMA, par **@GT-CNIG-DDU**

Le GT CNIG DDU est réparti en sous-groupes oeuvrant chacun sur une thématique spécifique :
- **SG1 : Suivi et prise en compte des évolutions de l'urbanisme. Relations avec le projet GPU.** Sous-goupe est animé par DGALN/DHUP/QV/QV3 : Bureau de la planification urbaine et rurale et du cadre de vie
- SG2 : Dématérialisation des Plans de sauvegarde et de mise en valeur (PSMV)
- SG3 : Servitude d'utilité publique (SUP). Ce sous-goupe est animé par DGALN/DHUP/QV/QV4 : Bureau de la législation de l'urbanisme
- SG4 : Prescriptions sur les Métadonnées
- **SG5 : Recommandations pour la symbolisation des documents d'urbanisme**
- **SG6 : Structuration du règlement d'urbanisme (ou : SG6 SRU)**

## Liens utiles
- [GT CNIG DDU sur le site du CNIG](https://cnig.gouv.fr/gt-ddu-a2918.html#H_Groupe-de-travail-DDU)
- [Ressources du GT CNIG DDU](https://cnig.gouv.fr/ressources-dematerialisation-documents-d-urbanisme-a2732.html) sur le site du CNIG : page de diffusion des standards et des ressources afférentes
- [Compte-rendus de réunions du GT CNIG DDU](https://cnig.gouv.fr/gt-ddu-a2918.html#H_Reunions) sur le site du CNIG, et [dans ce répertoire](https://github.com/cnigfr/schema-plan-local-urbanisme/tree/main/r%C3%A9unions).
- Historique du GT CNIG DDU : [article de A. Clozel paru en 2017 dans le blog SIG & Urba](https://blog.georezo.net/sigurba/2017/05/10/12-ans-deja/#more-1901)
- Accès au [Github du sous-groupe 5 "Symbolisation"](https://github.com/cnigfr/DDU-SG5-SYMBOLISATION)
- Accès au [Github du sous-groupe 6 "Structuration du règlement d'urbanisme"](https://github.com/cnigfr/structuration-reglement-urbanisme)
- Accès à la page ["Structuration du règlement d'urbanisme"](http://cnig.gouv.fr/structuration-des-reglements-d-urbanisme-a25890.html) sur le site du CNIG
- [Géoportail de l’urbanisme](https://www.geoportail-urbanisme.gouv.fr/)

## Organisation du Github

* Le répertoire [standard](https://github.com/cnigfr/schema-plan-local-urbanisme/tree/main/standard) contient la version courante du standard CNIG PLU
* Le répertoire [réunions](https://github.com/cnigfr/schema-plan-local-urbanisme/tree/main/r%C3%A9unions) contient les compte-rendus et présentations des réunions du GT CNIG DDU
* Le répertoire [documentation](https://github.com/cnigfr/schema-plan-local-urbanisme/tree/main/documentation) contient les documents utiles au groupe de travail.

## Actualisation et contributions

Le standard CNIG PLU évolue en fonction des évolutions réglementaires et de l'expression des besoins des communautés d'utilisateurs.

N'hésitez pas à utiliser la rubrique [Issues](https://github.com/cnigfr/schema-plan-local-urbanisme/issues) pour toute expression de besoin, proposition d'amélioration du projet de standard Friches, retour utilisateur, etc.

## Versions
- v2022 - octobre 2022 : 2.0.0
- v2017d - février 2021 : 1.3.0
- v2017c - novembre 2019 : 1.2.0
- v2017b : 1.1.0
- v2017-12 : 1.0.0

## Licence - OpenData

Les travaux du GT CNIG DDU sont réalisés sous [Licence Ouverte Etalab 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/)

Les données d’urbanisme sont ouvertes et publiées sur le [Géoportail de l’urbanisme](https://www.geoportail-urbanisme.gouv.fr/). <div align="right"> <img src="https://www.etalab.gouv.fr/wp-content/uploads/2011/10/licence-ouverte-open-licence.gif" width="300"> </div>

## Contacts
- Pour contacter le CNIG ou le GT CNIG DDU : [Page de contact du CNIG](https://cnig.gouv.fr/ressources-dematerialisation-documents-d-urbanisme-a2732.html?page=contact)

- Pour une demande d'information sur les **aspects métier urbanisme** : DGALN/DHUP/QV/QV3 Bureau de la planification urbaine et rurale et du cadre de vie :
<div align="right"> <img src="https://cnig.gouv.fr/IMG/png/230125_mail_qv3.png" width="400"> </div>

- Pour une demande **concernant le Géoportail de l'urbanisme** : [Page de contact du GPU](https://www.geoportail-urbanisme.gouv.fr/contact/)

- Pour être tenu au courant et/ou participer aux échanges du GT CNIG DDU : [Page de contact du CNIG](https://cnig.gouv.fr/ressources-dematerialisation-documents-d-urbanisme-a2732.html?page=contact)

- Pour une demande à la communauté d'utilisateurs des standards d'urbanisme : [Forum dédié sur Géorezo](https://georezo.net/forum/viewtopic.php?id=73022)

- Il est également possible de s'abonner à la [lettre d'information du CNIG](https://cnig.gouv.fr/info-cnig-la-lettre-d-information-du-cnig-a25957.html).

