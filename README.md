# Geneva: law history in git

The law of the canton of Geneva (République et canton de Genève, Switzerland) as a git history: one file per article, one commit per change on the day it took effect. `git blame` and `git log` work line by line; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-ge/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in French, the canton's official language, exactly as published.

## What this repository holds

737 acts with 737 versions so far, starting with the cantonal constitution. SILGENEVE publishes only the current text of each act, so each act has one version: the text in force today, dated by the latest entry into force in the act's own history table. It holds the constitution, the laws (lois) and the règlements in force, in the order of the systematic collection, added in parts; agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `a-2-00-cst-ge/` | Constitution de la République et canton de Genève (A 2 00) | 1 | current text only, in force since 4 July 2026 |
| `a-1-12-loct/` | Loi relative aux organismes de coopération transfrontalière (LOCT) (A 1 12) | 1 | current text only, in force since 24 July 2019 |
| `a-2-04-lrt/` | Loi-cadre sur la répartition des tâches entre les communes et le canton (LRT) (A 2 04) | 1 | current text only, in force since 1 January 2024 |
| `a-2-05-lrt-1/` | Loi sur la répartition des tâches entre les communes et le canton (1er train) (LRT-1) (A 2 05) | 1 | current text only, in force since 1 January 2023 |
| `a-2-07-lrt-3/` | Loi sur la répartition des tâches entre les communes et le canton en matière de sport (3e train) (LRT-3) (A 2 07) | 1 | current text only, in force since 16 May 2026 |
| `a-2-08-lipad/` | Loi sur l’information du public, l’accès aux documents et la protection des données personnelles(2) (LIPAD) (A 2 08) | 1 | current text only, in force since 11 January 2025 |
| `a-2-09-lnip/` | Loi instituant les numéros d’identification personnels communs (LNIP) (A 2 09) | 1 | current text only, in force since 14 May 2019 |
| `a-2-15-lser/` | Loi sur la prestation des serments (LSer) (A 2 15) | 1 | current text only, in force since 21 June 2025 |
| `a-2-20-lcof/` | Loi sur les commissions officielles (LCOf) (A 2 20) | 1 | current text only, in force since 28 January 2023 |
| `a-2-24-loidp/` | Loi sur l’organisation des institutions de droit public (LOIDP) (A 2 24) | 1 | current text only, in force since 21 June 2025 |
| `a-2-40-lrec/` | Loi sur la responsabilité de l’Etat et des communes (LREC) (A 2 40) | 1 | current text only, in force since 1 May 2018 |
| `a-2-55-lietr/` | Loi sur l’intégration des étrangers (LIEtr) (A 2 55) | 1 | current text only, in force since 29 August 2023 |
| `a-2-60-ldd/` | Loi sur l’action publique en vue d’un développement durable (Agenda 21) (LDD) (A 2 60) | 1 | current text only, in force since 25 May 2018 |
| `a-2-65-lgi/` | Loi sur les relations et le développement de la Genève internationale (LGI) (A 2 65) | 1 | current text only, in force since 7 May 2024 |
| `a-2-70-lcsmu/` | Loi relative à la politique de cohésion sociale en milieu urbain (LCSMU) (A 2 70) | 1 | current text only, in force since 29 August 2023 |
| `a-2-75-lle/` | Loi sur la laïcité de l’Etat (LLE) (A 2 75) | 1 | current text only, in force since 23 December 2021 |
| `a-2-80-lteh/` | Loi sur la lutte contre la traite des êtres humains (LTEH) (A 2 80) | 1 | current text only, in force since 18 May 2019 |
| `a-2-90-led/` | Loi générale sur l’égalité et la lutte contre les discriminations (LED) (A 2 90) | 1 | current text only, in force since 1 July 2023 |
| `a-2-91-led-genre/` | Loi sur l’égalité et la lutte contre les discriminations liées au sexe et au genre (LED-Genre) (A 2 91) | 1 | current text only, in force since 1 July 2023 |
| `a-3-01-larm/` | Loi sur la dénomination, les armoiries et les couleurs de l’Etat(1) (LArm) (A 3 01) | 1 | current text only, in force since 1 April 1959 |
| `a-4-05-ldcg/` | Loi sur le droit de cité genevois (LDCG) (A 4 05) | 1 | current text only, in force since 1 June 2025 |
| `a-5-05-ledp/` | Loi sur l’exercice des droits politiques (LEDP) (A 5 05) | 1 | current text only, in force since 4 July 2026 |
| `a-5-10/` | Loi sur l’exercice du droit de pétition (LPétition) (A 5 10) | 1 | current text only, in force since 21 March 2015 |
| `b-1-01-lrgc/` | Loi portant règlement du Grand Conseil de la République et canton de Genève (LRGC) (B 1 01) | 1 | current text only, in force since 16 August 2025 |
| `b-1-15-leco/` | Loi sur l’exercice des compétences du Conseil d’Etat et l’organisation de l’administration (LECO) (B 1 15) | 1 | current text only, in force since 14 March 2020 |
| `b-1-20-ltrce/` | Loi concernant le traitement et la retraite des membres du Conseil d’Etat et de la chancelière ou du chancelier d’Etat (LTRCE) (B 1 20) | 1 | current text only, in force since 1 July 2026 |
| `b-1-25-lprot/` | Loi sur le protocole (LProt) (B 1 25) | 1 | current text only, in force since 1 June 2026 |
| `b-1-40/` | Loi sur la médiation administrative(1) (LMéd-GE) (B 1 40) | 1 | current text only, in force since 1 December 2024 |
| `b-2-05-lfpp/` | Loi sur la forme, la publication et la promulgation des actes officiels (LFPP) (B 2 05) | 1 | current text only, in force since 4 July 2026 |
| `b-2-10-lfao/` | Loi sur la Feuille d’avis officielle de la République et canton de Genève (LFAO) (B 2 10) | 1 | current text only, in force since 4 September 2018 |
| `b-2-15-larch/` | Loi sur les archives publiques (LArch) (B 2 15) | 1 | current text only, in force since 4 September 2018 |
| `b-4-23-lael/` | Loi sur l’administration en ligne (LAeL) (B 4 23) | 1 | current text only, in force since 14 November 2023 |
| `b-4-38-lpbi/` | Loi sur la publicité relative aux biens immobiliers des personnes morales de droit public (LPBI) (B 4 38) | 1 | current text only, in force since 31 August 2010 |
| `b-4-40-lstat/` | Loi sur la statistique publique cantonale (LStat) (B 4 40) | 1 | current text only, in force since 1 May 2018 |
| `b-5-05-lpac/` | Loi générale relative au personnel de l’administration cantonale, du pouvoir judiciaire et des établissements publics médicaux(12) (LPAC) (B 5 05) | 1 | current text only, in force since 5 May 2026 |
| `b-5-07-lpla/` | Loi sur la protection des lanceurs d’alerte au sein de l’Etat (LPLA) (B 5 07) | 1 | current text only, in force since 26 March 2022 |
| `b-5-15-ltrait/` | Loi concernant le traitement et les diverses prestations alloués aux membres du personnel de l'Etat, du pouvoir judiciaire et des établissements hospitaliers(31) (LTrait) (B 5 15) | 1 | current text only, in force since 23 March 2024 |
| `b-5-20-lrp/` | Loi sur la rente-pont AVS (LRP) (B 5 20) | 1 | current text only, in force since 10 December 2022 |
| `b-5-22-lcpeg/` | Loi instituant la Caisse de prévoyance de l'Etat de Genève (LCPEG) (B 5 22) | 1 | current text only, in force since 1 July 2026 |
| `b-5-30-lacvp/` | Loi concernant l’adaptation au coût de la vie des pensions servies aux retraités et pensionnés de l’Etat, des établissements hospitaliers et des caisses de prévoyance (LACVP) (B 5 30) | 1 | current text only, in force since 4 September 2018 |
| `b-5-33-lcpfp/` | Loi sur la Caisse de prévoyance des fonctionnaires de police et des établissements pénitentiaires(1) (LCPFP) (B 5 33) | 1 | current text only, in force since 1 January 2024 |
| `b-5-35-lprcp/` | Loi concernant un pont-retraite en faveur du personnel assuré par la Caisse de prévoyance des fonctionnaires de police et des établissements pénitentiaires(4) (LPRCP) (B 5 35) | 1 | current text only, in force since 1 March 2017 |
| `b-5-40-lfptpg/` | Loi concernant la Fondation de prévoyance en faveur du personnel des Transports publics genevois (LFPTPG) (B 5 40) | 1 | current text only, in force since 29 August 2023 |
| `b-6-05-lac/` | Loi sur l’administration des communes (LAC) (B 6 05) | 1 | current text only, in force since 1 September 2026 |
| `b-6-07-liaci/` | Loi sur les institutions autonomes communales et intercommunales de droit public (LIACI) (B 6 07) | 1 | current text only, in force since 1 September 2026 |
| `b-6-08-lrpfi/` | Loi sur le renforcement de la péréquation financière intercommunale et le développement de l'intercommunalité (LRPFI) (B 6 08) | 1 | current text only, in force since 1 September 2026 |
| `b-6-09-lrcv/` | Loi sur la répartition entre le canton et les communes de la compensation verticale relative à la réforme fiscale et au financement de l’AVS (LRCV) (B 6 09) | 1 | current text only, in force since 1 January 2020 |
| `b-6-12-lfusc/` | Loi sur les fusions de communes (LFusC) (B 6 12) | 1 | current text only, in force since 14 May 2019 |
| `c-1-10-lip/` | Loi sur l’instruction publique (LIP) (C 1 10) | 1 | current text only, in force since 17 August 2026 |
| `c-1-11-lfpcfp/` | Loi sur la création de 2 fonds propres affectés pour chaque centre de formation professionnelle (LFPCFP) (C 1 11) | 1 | current text only, in force since 4 September 2018 |
| `c-1-20-lbpe/` | Loi sur les bourses et prêts d'études (LBPE) (C 1 20) | 1 | current text only, in force since 14 January 2023 |
| `c-1-26-lhes-so-ge/` | Loi sur la Haute école spécialisée de Suisse occidentale – Genève (LHES-SO-GE) (C 1 26) | 1 | current text only, in force since 5 May 2026 |
| `c-1-30-lu/` | Loi sur l'université (LU) (C 1 30) | 1 | current text only, in force since 5 May 2026 |
| `c-1-40-lftp/` | Loi concernant la fondation de la faculté autonome de théologie protestante(3) (LFTP) (C 1 40) | 1 | current text only, in force since 23 March 2013 |
| `c-1-45-lgmnc/` | Loi concernant la création d’un groupe multidisciplinaire chargé de l’étude, de l’enseignement introductif et de l’information sur les médecines non conventionnelles (LGMNC) (C 1 45) | 1 | current text only, in force since 13 June 1992 |
| `c-1-50-lsport/` | Loi sur le sport (LSport) (C 1 50) | 1 | current text only, in force since 16 May 2026 |
| `c-2-05-lfp/` | Loi sur la formation professionnelle (LFP) (C 2 05) | 1 | current text only, in force since 27 February 2026 |
| `c-2-08-lfca/` | Loi sur la formation continue des adultes (LFCA) (C 2 08) | 1 | current text only, in force since 1 January 2023 |
| `c-2-10-liosp/` | Loi sur l'information et l'orientation scolaires et professionnelles (LIOSP) (C 2 10) | 1 | current text only, in force since 4 September 2018 |
| `c-3-05-lpcca/` | Loi pour la promotion de la culture et de la création artistique (LPCCA) (C 3 05) | 1 | current text only, in force since 1 January 2024 |
| `c-3-09-lfcac/` | Loi relative au Fonds cantonal d'art contemporain (LFCAC) (C 3 09) | 1 | current text only, in force since 23 April 2025 |
| `c-3-10-ling/` | Loi sur l’Institut national genevois (LING) (C 3 10) | 1 | current text only, in force since 30 January 1959 |
| `d-1-05-lgaf/` | Loi sur la gestion administrative et financière de l’Etat (LGAF) (D 1 05) | 1 | current text only, in force since 13 September 2025 |
| `d-1-06-lfsi/` | Loi sur le financement de la solidarité internationale (LFSI) (D 1 06) | 1 | current text only, in force since 1 July 2002 |
| `d-1-07-lafong/` | Loi relative aux aides financières extraordinaires de l’Etat destinées aux organisations non gouvernementales à Genève touchées par le gel de l'aide internationale (LAFONG) (D 1 07) | 1 | current text only, in force since 25 April 2025 |
| `d-1-09-lsurv/` | Loi sur la surveillance de l’Etat (LSurv) (D 1 09) | 1 | current text only, in force since 26 March 2022 |
| `d-1-11-liaf/` | Loi sur les indemnités et les aides financières (LIAF) (D 1 11) | 1 | current text only, in force since 1 July 2023 |
| `d-1-13-ltrcc/` | Loi concernant le traitement et la retraite des magistrates et magistrats de la Cour des comptes (LTRCC) (D 1 13) | 1 | current text only, in force since 1 July 2026 |
| `d-1-15-lcce/` | Loi sur la caisse des consignations de l’Etat(3) (LCCE) (D 1 15) | 1 | current text only, in force since 1 April 1959 |
| `d-1-25-lpsu/` | Loi affectant le produit net des successions attribuées à l'Etat par l'article 466 du code civil au désendettement de l'Etat (LPSu) (D 1 25) | 1 | current text only, in force since 1 January 2007 |
| `d-2-05-lbcge/` | Loi sur la Banque cantonale de Genève (LBCGe) (D 2 05) | 1 | current text only, in force since 1 September 2025 |
| `d-2-10-lcppg/` | Loi sur la caisse publique de prêts sur gages (LCPPG) (D 2 10) | 1 | current text only, in force since 1 January 2019 |
| `d-2-20-lgar/` | Loi générale relative à la garantie de l'Etat pour les institutions de prévoyance publiques cantonales (LGar) (D 2 20) | 1 | current text only, in force since 1 January 2020 |
| `d-3-05-lcp/` | Loi générale sur les contributions publiques (LCP) (D 3 05) | 1 | current text only, in force since 1 January 2026 |
| `d-3-06-ldirpp/` | Loi relative à la diminution de l’impôt sur le revenu des personnes physiques (LDIRPP) (D 3 06) | 1 | current text only, in force since 16 October 1999 |
| `d-3-07-lcacant/` | Loi sur les centimes additionnels cantonaux (LCACant) (D 3 07) | 1 | current text only, in force since 9 November 2019 |
| `d-3-08-lipp/` | Loi sur l'imposition des personnes physiques (LIPP) (D 3 08) | 1 | current text only, in force since 1 January 2026 |
| `d-3-10-lefi/` | Loi sur les estimations fiscales de certains immeubles (LEFI) (D 3 10) | 1 | current text only, in force since 28 February 2025 |
| `d-3-15-lipm/` | Loi sur l’imposition des personnes morales (LIPM) (D 3 15) | 1 | current text only, in force since 1 January 2025 |
| `d-3-17-lpfisc/` | Loi de procédure fiscale (LPFisc) (D 3 17) | 1 | current text only, in force since 1 January 2026 |
| `d-3-18-lpgip/` | Loi relative à la perception et aux garanties des impôts des personnes physiques et des personnes morales (LPGIP) (D 3 18) | 1 | current text only, in force since 1 January 2025 |
| `d-3-20-lisp/` | Loi sur l’imposition à la source des personnes physiques et morales (LISP) (D 3 20) | 1 | current text only, in force since 1 January 2026 |
| `d-3-25-lds/` | Loi sur les droits de succession (LDS) (D 3 25) | 1 | current text only, in force since 21 March 2026 |
| `d-3-30-lde/` | Loi sur les droits d’enregistrement (LDE) (D 3 30) | 1 | current text only, in force since 21 March 2026 |
| `d-3-35-ldatp/` | Loi sur la dation en paiement (LDatP) (D 3 35) | 1 | current text only, in force since 29 August 2023 |
| `d-3-40-lmrf/` | Loi sur les mutations au registre foncier(1) (LMRF) (D 3 40) | 1 | current text only, in force since 29 August 2023 |
| `d-3-45-lrcep/` | Loi sur la constitution de réserves de crise par l’économie privée (LRCEP) (D 3 45) | 1 | current text only, in force since 29 August 2023 |
| `d-3-50-lafrc/` | Loi sur les allégements fiscaux pour les réserves de crise (LAFRC) (D 3 50) | 1 | current text only, in force since 1 January 2002 |
| `d-3-70-lbu-2025/` | Loi établissant le budget administratif de l’Etat de Genève pour l’exercice 2025 (LBu-2025) (D 3 70) | 1 | current text only, in force since 1 January 2025 |
| `e-1-05-lacc/` | Loi d'application du code civil suisse et d'autres lois fédérales en matière civile (LaCC) (E 1 05) | 1 | current text only, in force since 4 July 2026 |
| `e-1-13-lec/` | Loi sur l’état civil (LEC) (E 1 13) | 1 | current text only, in force since 1 June 2025 |
| `e-1-16-lsfip/` | Loi sur la surveillance des fondations de droit civil et des institutions de prévoyance (LSFIP) (E 1 16) | 1 | current text only, in force since 1 May 2018 |
| `e-1-25-larpa/` | Loi sur l’avance et le recouvrement des pensions alimentaires (LARPA) (E 1 25) | 1 | current text only, in force since 1 April 2022 |
| `e-1-27-lpart-ge/` | Loi sur le partenariat (LPart-GE) (E 1 27) | 1 | current text only, in force since 29 August 2023 |
| `e-1-40-lvoa/` | Loi concernant la vente d’objets abandonnés sur les terrains de l’Etat (LVOA) (E 1 40) | 1 | current text only, in force since 1 April 1959 |
| `e-1-43-lalfaie/` | Loi d’application de la loi fédérale sur l’acquisition d’immeubles par des personnes à l’étranger (LaLFAIE) (E 1 43) | 1 | current text only, in force since 15 February 2015 |
| `e-1-46/` | Loi sur la géoinformation (LGéo-GE) (E 1 46) | 1 | current text only, in force since 1 February 2025 |
| `e-2-05-loj/` | Loi sur l’organisation judiciaire (LOJ) (E 2 05) | 1 | current text only, in force since 1 June 2026 |
| `e-2-40-ltrpj/` | Loi concernant le traitement et la retraite des magistrats du pouvoir judiciaire (LTRPJ) (E 2 40) | 1 | current text only, in force since 1 July 2025 |
| `e-3-10-ltph/` | Loi sur le Tribunal des prud’hommes (LTPH) (E 3 10) | 1 | current text only, in force since 1 January 2024 |
| `e-3-15-lccbl/` | Loi organisant la commission de conciliation en matière de baux et loyers (LCCBL) (E 3 15) | 1 | current text only, in force since 25 June 2013 |
| `e-3-60-lalp/` | Loi d’application de la loi fédérale sur la poursuite pour dettes et la faillite (LaLP) (E 3 60) | 1 | current text only, in force since 29 August 2023 |
| `e-4-05-lpg/` | Loi pénale genevoise (LPG) (E 4 05) | 1 | current text only, in force since 26 January 2024 |
| `e-4-10-lacp/` | Loi d’application du code pénal suisse et d’autres lois fédérales en matière pénale (LaCP) (E 4 10) | 1 | current text only, in force since 26 January 2024 |
| `e-4-60-lsmp/` | Loi sur les mesures visant à promouvoir la sécurité des minorités ayant un besoin de protection particulier (LSMP) (E 4 60) | 1 | current text only, in force since 20 January 2024 |
| `e-5-10-lpa/` | Loi sur la procédure administrative (LPA) (E 5 10) | 1 | current text only, in force since 1 June 2025 |
| `e-6-05-lnot/` | Loi sur le notariat (LNot) (E 6 05) | 1 | current text only, in force since 1 June 2025 |
| `e-6-10-lpav/` | Loi sur la profession d’avocat (LPAv) (E 6 10) | 1 | current text only, in force since 21 October 2025 |
| `e-6-15-lhj/` | Loi sur la profession d'huissier judiciaire (LHJ) (E 6 15) | 1 | current text only, in force since 29 August 2023 |
| `e-6-25/` | Loi sur la médiation (LMédiation) (E 6 25) | 1 | current text only, in force since 1 January 2024 |
| `f-1-05-lpol/` | Loi sur la police (LPol) (F 1 05) | 1 | current text only, in force since 5 May 2026 |
| `f-1-07-lapm/` | Loi sur les agents de la police municipale, les contrôleurs municipaux du stationnement et les gardes auxiliaires des communes (LAPM) (F 1 07) | 1 | current text only, in force since 1 June 2025 |
| `f-1-25-lcbvm/` | Loi sur les renseignements et les dossiers de police et la délivrance des certificats de bonne vie et mœurs (LCBVM) (F 1 25) | 1 | current text only, in force since 28 February 2025 |
| `f-1-30-lvd/` | Loi sur les violences domestiques (LVD) (F 1 30) | 1 | current text only, in force since 3 September 2019 |
| `f-1-50-lopp/` | Loi sur l’organisation des établissements et le statut du personnel pénitentiaires (LOPP) (F 1 50) | 1 | current text only, in force since 5 May 2026 |
| `f-1-51-lcsd/` | Loi sur le convoyage et la surveillance des détenus hors des établissements pénitentiaires (LCSD) (F 1 51) | 1 | current text only, in force since 20 January 2024 |
| `f-1-52/` | Loi sur la planification pénitentiaire (LPPén) (F 1 52) | 1 | current text only, in force since 20 May 2023 |
| `f-1-53-lapcd/` | Loi sur l’affectation de la prison de Champ-Dollon (LAPCD) (F 1 53) | 1 | current text only, in force since 19 March 2026 |
| `f-2-05-lsec/` | Loi sur le séjour et l’établissement des Confédérés (LSEC) (F 2 05) | 1 | current text only, in force since 29 August 2023 |
| `f-2-10-laletr/` | Loi d'application de la loi fédérale sur les étrangers(13) (LaLEtr) (F 2 10) | 1 | current text only, in force since 31 August 2021 |
| `f-2-15-lalasi/` | Loi d’application de la loi fédérale sur l’asile (LaLAsi) (F 2 15) | 1 | current text only, in force since 1 January 2025 |
| `f-2-25-lalhr/` | Loi d'application de la loi fédérale sur l'harmonisation des registres des habitants et d'autres registres officiels de personnes (LaLHR) (F 2 25) | 1 | current text only, in force since 29 August 2023 |
| `f-3-10-lmdpu/` | Loi sur les manifestations sur le domaine public (LMDPu) (F 3 10) | 1 | current text only, in force since 29 August 2023 |
| `f-3-17-lffsm/` | Loi concernant la facturation des frais de sécurité lors de manifestations (LFFSM) (F 3 17) | 1 | current text only, in force since 1 March 2017 |
| `f-3-20-lpr/` | Loi sur les procédés de réclame (LPR) (F 3 20) | 1 | current text only, in force since 4 November 2023 |
| `f-4-05-lpssp/` | Loi sur la prévention des sinistres, l’organisation et l’intervention des sapeurs-pompiers (LPSSP) (F 4 05) | 1 | current text only, in force since 1 September 2026 |
| `f-4-15-lcssp/` | Loi sur les caisses de secours des sapeurs-pompiers (LCSSP) (F 4 15) | 1 | current text only, in force since 1 January 1923 |
| `g-1-05-late/` | Loi d’application des dispositions fédérales sur la taxe d’exemption de l’obligation de servir(4) (LaTE) (G 1 05) | 1 | current text only, in force since 1 January 2011 |
| `g-1-50-lcsc/` | Loi cantonale sur le service civil (LCSC) (G 1 50) | 1 | current text only, in force since 24 August 2002 |
| `g-2-05-lproci/` | Loi d’application des dispositions fédérales en matière de protection civile (LProCi) (G 2 05) | 1 | current text only, in force since 1 January 2011 |
| `g-3-03-lpropop/` | Loi d'application des dispositions fédérales en matière de protection de la population (LProPop) (G 3 03) | 1 | current text only, in force since 1 January 2014 |
| `g-3-10-lssc/` | Loi sur le service sanitaire coordonné (LSSC) (G 3 10) | 1 | current text only, in force since 1 January 2021 |
| `h-1-05-lalcr/` | Loi d’application de la législation fédérale sur la circulation routière (LaLCR) (H 1 05) | 1 | current text only, in force since 4 July 2026 |
| `h-1-13-lfpark/` | Loi sur la Fondation des parkings(1) (LFPark) (H 1 13) | 1 | current text only, in force since 1 May 2018 |
| `h-1-20-lmob/` | Loi sur la mobilité (LMob) (H 1 20) | 1 | current text only, in force since 1 November 2025 |
| `h-1-21-lmce/` | Loi pour une mobilité cohérente et équilibrée (LMCE) (H 1 21) | 1 | current text only, in force since 17 October 2020 |
| `h-1-31-ltvtc/` | Loi sur les taxis et les voitures de transport avec chauffeur (LTVTC) (H 1 31) | 1 | current text only, in force since 22 November 2025 |
| `h-1-50-lrtp/` | Loi sur le réseau des transports publics (LRTP) (H 1 50) | 1 | current text only, in force since 19 September 2020 |
| `h-1-55-ltpg/` | Loi sur les Transports publics genevois (LTPG) (H 1 55) | 1 | current text only, in force since 1 January 2025 |
| `h-1-60-ldif-ge/` | Loi sur le développement des infrastructures ferroviaires (LDIF-GE) (H 1 60) | 1 | current text only, in force since 29 August 2023 |
| `h-1-70-litagglo/` | Loi sur les infrastructures de transport issues du projet d'agglomération franco-valdo-genevois (LITAgglo) (H 1 70) | 1 | current text only, in force since 29 March 2011 |
| `h-1-80-lmd/` | Loi sur la mobilité douce (LMD) (H 1 80) | 1 | current text only, in force since 1 November 2025 |
| `h-2-05-lnav/` | Loi sur la navigation dans les eaux genevoises (LNav) (H 2 05) | 1 | current text only, in force since 1 January 2026 |
| `h-2-10-lcgn/` | Loi sur la Compagnie générale de navigation sur le Lac Léman (LCGN) (H 2 10) | 1 | current text only, in force since 1 January 2026 |
| `h-3-10-lzsb/` | Loi sur la procédure en matière de zones de sécurité et de bruit (LZSB) (H 3 10) | 1 | current text only, in force since 4 September 2018 |
| `h-3-25-laig/` | Loi sur l’Aéroport international de Genève (LAIG) (H 3 25) | 1 | current text only, in force since 21 June 2025 |
| `i-1-05-lhom/` | Loi sur les heures d’ouverture des magasins(15) (LHOM) (I 1 05) | 1 | current text only, in force since 4 July 2026 |
| `i-1-10-lcdipj/` | Loi sur la concurrence déloyale, l’indication et la surveillance des prix et sur les jeux-concours publicitaires(2) (LCDIPJ) (I 1 10) | 1 | current text only, in force since 29 August 2023 |
| `i-1-25-ltlhm/` | Loi relative à Timelab – Fondation du laboratoire d’horlogerie et de microtechnique de Genève (LTLHM) (I 1 25) | 1 | current text only, in force since 17 November 2018 |
| `i-1-36/` | Loi en faveur du développement de l’économie et de l’emploi (LDévEco) (I 1 36) | 1 | current text only, in force since 27 February 2026 |
| `i-1-37-lae/` | Loi sur l'aide aux entreprises (LAE) (I 1 37) | 1 | current text only, in force since 27 February 2026 |
| `i-1-40-ljedi/` | Loi accordant le statut de « JEDI » aux jeunes entreprises développant des innovations (LJEDI) (I 1 40) | 1 | current text only, in force since 27 February 2026 |
| `i-1-45-lraa/` | Loi sur le renforcement de l’attractivité de l’audiovisuel (LRAA) (I 1 45) | 1 | current text only, in force since 4 July 2026 |
| `i-1-51-lvs/` | Loi sur la vente du sel (LVS) (I 1 51) | 1 | current text only, in force since 1 January 2011 |
| `i-1-60-ltour/` | Loi sur le tourisme (LTour) (I 1 60) | 1 | current text only, in force since 1 June 2024 |
| `i-2-09-lcou/` | Loi sur le commerce d’objets usagés ou de seconde main (LCOU) (I 2 09) | 1 | current text only, in force since 27 February 2026 |
| `i-2-12-laint/` | Loi sur les agentes et agents intermédiaires(19) (LAInt) (I 2 12) | 1 | current text only, in force since 29 August 2023 |
| `i-2-22-lrdbhd/` | Loi sur la restauration, le débit de boissons, l’hébergement et le divertissement (LRDBHD) (I 2 22) | 1 | current text only, in force since 14 October 2026 |
| `i-2-25-ltgveat/` | Loi sur la remise à titre gratuit et la vente à l’emporter de boissons alcooliques, de produits du tabac et de produits assimilés au tabac (LTGVEAT) (I 2 25) | 1 | current text only, in force since 14 October 2026 |
| `i-2-30-lvve/` | Loi sur les ventes volontaires aux enchères publiques (LVVE) (I 2 30) | 1 | current text only, in force since 4 July 2026 |
| `i-2-36-lidl/` | Loi instituant le dépôt légal (LIDL) (I 2 36) | 1 | current text only, in force since 1 January 2019 |
| `i-2-43/` | Loi sur les prêteurs professionnels, les prêts d’argent et l’octroi de crédits (LPrêt) (I 2 43) | 1 | current text only, in force since 21 March 2015 |
| `i-2-46-ltj/` | Loi sur les traducteurs-jurés (LTJ) (I 2 46) | 1 | current text only, in force since 31 August 2013 |
| `i-3-11-laljar/` | Loi d’application de la loi fédérale sur les jeux d’argent (LaLJAr) (I 3 11) | 1 | current text only, in force since 1 January 2021 |
| `i-3-13-lmjeu/` | Loi sur les maisons de jeu (LMJeu) (I 3 13) | 1 | current text only, in force since 1 January 2021 |
| `i-4-05-lgl/` | Loi générale sur le logement et la protection des locataires (LGL) (I 4 05) | 1 | current text only, in force since 14 February 2026 |
| `i-4-07-lalcbl/` | Loi d’application de la loi fédérale sur les contrats-cadres de baux à loyer et leur déclaration de force obligatoire générale (LaLCBL) (I 4 07) | 1 | current text only, in force since 15 November 1997 |
| `i-4-10-lgfl/` | Loi protégeant les garanties fournies par les locataires (LGFL) (I 4 10) | 1 | current text only, in force since 27 January 2007 |
| `i-4-40-lpul/` | Loi pour un plan d’urgence-logements (LPUL) (I 4 40) | 1 | current text only, in force since 17 August 1991 |
| `i-4-53-lapi/` | Loi sur l’aide à la propriété individuelle (LAPI) (I 4 53) | 1 | current text only, in force since 2 November 2024 |
| `i-4-55-laple/` | Loi encourageant l’accession à la propriété du logement par l’épargne-logement (LAPLE) (I 4 55) | 1 | current text only, in force since 1 January 2014 |
| `j-1-05-lirt/` | Loi sur l'inspection et les relations du travail (LIRT) (J 1 05) | 1 | current text only, in force since 8 April 2026 |
| `j-1-15-lcrct/` | Loi concernant la Chambre des relations collectives de travail (LCRCT) (J 1 15) | 1 | current text only, in force since 1 January 2024 |
| `j-1-20-lpgfe/` | Loi protégeant les garanties fournies par les employés (LPGFE) (J 1 20) | 1 | current text only, in force since 27 January 2007 |
| `j-1-45-ljf/` | Loi sur les jours fériés (LJF) (J 1 45) | 1 | current text only, in force since 1 January 1991 |
| `j-2-05-lsels/` | Loi sur le service de l’emploi et la location de services (LSELS) (J 2 05) | 1 | current text only, in force since 18 May 2019 |
| `j-2-20-lmc/` | Loi en matière de chômage (LMC) (J 2 20) | 1 | current text only, in force since 27 February 2026 |
| `j-3-05-lalamal/` | Loi d’application de la loi fédérale sur l’assurance-maladie (LaLAMal) (J 3 05) | 1 | current text only, in force since 2 November 2024 |
| `j-3-20-lalaa/` | Loi d’application de la loi fédérale sur l’assurance-accidents (LaLAA) (J 3 20) | 1 | current text only, in force since 15 May 2004 |
| `j-4-04-laslp/` | Loi sur l’aide sociale et la lutte contre la précarité (LASLP) (J 4 04) | 1 | current text only, in force since 1 January 2025 |
| `j-4-06-lrdu/` | Loi sur le revenu déterminant unifié(7) (LRDU) (J 4 06) | 1 | current text only, in force since 1 January 2025 |
| `j-4-07-lhg/` | Loi sur l'Hospice général (LHG) (J 4 07) | 1 | current text only, in force since 1 January 2025 |
| `j-4-10-lalavi/` | Loi d'application de la loi fédérale sur l'aide aux victimes d'infractions (LaLAVI) (J 4 10) | 1 | current text only, in force since 15 April 2017 |
| `j-4-11-lapsa/` | Loi sur l’aide aux personnes sans abri (LAPSA) (J 4 11) | 1 | current text only, in force since 1 January 2025 |
| `j-4-12-lpls/` | Loi sur la prévention et la lutte contre le surendettement (LPLS) (J 4 12) | 1 | current text only, in force since 1 January 2024 |
| `j-4-18-locas/` | Loi relative à l'office cantonal des assurances sociales(a) (LOCAS) (J 4 18) | 1 | current text only, in force since 21 June 2025 |
| `j-4-20-lpfc/` | Loi sur les prestations fédérales complémentaires à l’assurance-vieillesse et survivants et à l’assurance-invalidité(a) (LPFC) (J 4 20) | 1 | current text only, in force since 6 September 2014 |
| `j-4-25-lpcc/` | Loi sur les prestations complémentaires cantonales(b) (LPCC) (J 4 25) | 1 | current text only, in force since 29 August 2023 |
| `j-5-07-lamat/` | Loi instituant une assurance en cas de maternité et d’adoption (LAMat) (J 5 07) | 1 | current text only, in force since 1 January 2024 |
| `j-5-10-laf/` | Loi sur les allocations familiales (LAF) (J 5 10) | 1 | current text only, in force since 31 August 2021 |
| `j-6-01-lej/` | Loi sur l’enfance et la jeunesse (LEJ) (J 6 01) | 1 | current text only, in force since 25 March 2023 |
| `j-6-11-lclfase/` | Loi relative aux centres de loisirs et de rencontres et à la Fondation genevoise pour l’animation socioculturelle (LCLFASe) (J 6 11) | 1 | current text only, in force since 1 July 2023 |
| `j-6-15-lfoj/` | Loi sur la Fondation officielle de la jeunesse (LFOJ) (J 6 15) | 1 | current text only, in force since 25 March 2023 |
| `j-6-28-lapr/` | Loi sur l’accueil préscolaire (LAPr) (J 6 28) | 1 | current text only, in force since 1 January 2020 |
| `j-6-32-lajc/` | Loi sur l’accueil à journée continue (LAJC) (J 6 32) | 1 | current text only, in force since 1 September 2026 |
| `j-7-20-lgepa/` | Loi sur la gestion des établissements pour personnes âgées (LGEPA) (J 7 20) | 1 | current text only, in force since 28 February 2025 |
| `j-7-35-lrg/` | Loi concernant les Rentes genevoises – Assurance pour la vieillesse (LRG) (J 7 35) | 1 | current text only, in force since 1 May 2018 |
| `k-1-03-ls/` | Loi sur la santé (LS) (K 1 03) | 1 | current text only, in force since 29 August 2026 |
| `k-1-04-lorsdom/` | Loi sur l’organisation du réseau de soins en vue du maintien à domicile (LORSDom) (K 1 04) | 1 | current text only, in force since 27 February 2024 |
| `k-1-07-limad/` | Loi sur l’Institution genevoise de maintien à domicile(5) (LIMAD) (K 1 07) | 1 | current text only, in force since 27 March 2021 |
| `k-1-18-lif/` | Loi sur l'interdiction de fumer dans les lieux publics (LIF) (K 1 18) | 1 | current text only, in force since 9 April 2022 |
| `k-1-21-ltsu/` | Loi sur les transports sanitaires urgents et l’aide sanitaire associée(11) (LTSU) (K 1 21) | 1 | current text only, in force since 1 July 2020 |
| `k-1-36-liph/` | Loi sur l’intégration des personnes handicapées (LIPH) (K 1 36) | 1 | current text only, in force since 3 September 2019 |
| `k-1-65-lcim/` | Loi sur les cimetières (LCim) (K 1 65) | 1 | current text only, in force since 29 August 2023 |
| `k-1-70-lalpe/` | Loi d’application de la loi fédérale sur la protection de l’environnement (LaLPE) (K 1 70) | 1 | current text only, in force since 27 August 2020 |
| `k-1-71-lalsc/` | Loi d'application de la législation fédérale sur les sites contaminés (LaLSC) (K 1 71) | 1 | current text only, in force since 14 March 2020 |
| `k-2-05-lepm/` | Loi sur les établissements publics médicaux(a) (LEPM) (K 2 05) | 1 | current text only, in force since 4 November 2023 |
| `k-2-16-lcrn/` | Loi concernant la création d'un centre romand de neurochirurgie(1) (LCRN) (K 2 16) | 1 | current text only, in force since 19 December 2015 |
| `k-3-03-lcomps/` | Loi sur la commission de surveillance des professions de la santé et des droits des patients (LComPS) (K 3 03) | 1 | current text only, in force since 27 February 2024 |
| `k-3-07-lrcim/` | Loi sur le réseau communautaire d'informatique médicale (e-Toile) (LRCIM) (K 3 07) | 1 | current text only, in force since 27 February 2024 |
| `k-5-02-laldal/` | Loi d’application de la législation fédérale sur les denrées alimentaires et les objets usuels (LaLDAl) (K 5 02) | 1 | current text only, in force since 7 May 2024 |
| `l-1-05-ldpu/` | Loi sur le domaine public (LDPu) (L 1 05) | 1 | current text only, in force since 4 July 2026 |
| `l-1-07-lavmt/` | Loi sur l’arborisation, la végétalisation, la mobilité douce et les transports publics dans l’aire urbaine (LAVMT) (L 1 07) | 1 | current text only, in force since 3 April 2024 |
| `l-1-10-lroutes/` | Loi sur les routes (LRoutes) (L 1 10) | 1 | current text only, in force since 29 August 2023 |
| `l-1-11-lz30/` | Loi sur les zones 30 et les zones de rencontre (LZ30) (L 1 11) | 1 | current text only, in force since 1 January 2019 |
| `l-1-15-lalrn/` | Loi d’application de la loi fédérale sur les routes nationales (LaLRN) (L 1 15) | 1 | current text only, in force since 3 September 2019 |
| `l-1-20-lgd/` | Loi sur la gestion des déchets (LGD) (L 1 20) | 1 | current text only, in force since 13 December 2025 |
| `l-1-30-lalat/` | Loi d’application de la loi fédérale sur l’aménagement du territoire (LaLAT) (L 1 30) | 1 | current text only, in force since 4 July 2026 |
| `l-1-35-lgzd/` | Loi générale sur les zones de développement(8) (LGZD) (L 1 35) | 1 | current text only, in force since 1 September 2026 |
| `l-1-40-lext/` | Loi sur l’extension des voies de communication et l’aménagement des quartiers ou localités (LExt) (L 1 40) | 1 | current text only, in force since 4 July 2026 |
| `l-1-45-lziam/` | Loi générale sur les zones de développement industriel ou d’activités mixtes(12) (LZIAM) (L 1 45) | 1 | current text only, in force since 4 July 2026 |
| `l-1-50-lrfu/` | Loi sur le remembrement foncier urbain(6) (LRFU) (L 1 50) | 1 | current text only, in force since 18 February 2019 |
| `l-1-55-lcua/` | Loi sur les commissions d’urbanisme et d’architecture (LCUA) (L 1 55) | 1 | current text only, in force since 4 September 2018 |
| `l-1-57-lfac/` | Loi sur la fonction d'architecte cantonal (LFAC) (L 1 57) | 1 | current text only, in force since 4 September 2018 |
| `l-1-60-lalcpr/` | Loi sur l’application de la loi fédérale sur les chemins pour piétons et les chemins de randonnée pédestre (LaLCPR) (L 1 60) | 1 | current text only, in force since 3 September 2019 |
| `l-2-05-leaux-ge/` | Loi sur les eaux (LEaux-GE) (L 2 05) | 1 | current text only, in force since 1 September 2026 |
| `l-2-10-loep/` | Loi sur l'occupation des eaux publiques (LOEP) (L 2 10) | 1 | current text only, in force since 4 July 2026 |
| `l-2-30-len/` | Loi sur l’énergie (LEn) (L 2 30) | 1 | current text only, in force since 4 July 2026 |
| `l-2-35-lsig/` | Loi sur l’organisation des Services industriels de Genève (LSIG) (L 2 35) | 1 | current text only, in force since 4 July 2026 |
| `l-2-40-lfder/` | Loi instituant 2 fonds pour le développement des énergies renouvelables et les économies d’énergie (LFDER) (L 2 40) | 1 | current text only, in force since 21 March 2015 |
| `l-2-45-lfaeb/` | Loi sur le financement de projets d’assainissement énergétique des bâtiments et sur l’ouverture de crédits d’investissement (LFAEB) (L 2 45) | 1 | current text only, in force since 1 June 2024 |
| `l-3-05-lrss/` | Loi sur les ressources du sous-sol (LRSS) (L 3 05) | 1 | current text only, in force since 4 July 2026 |
| `l-3-10-lgea/` | Loi sur les gravières et exploitations assimilées (LGEA) (L 3 10) | 1 | current text only, in force since 12 September 2026 |
| `l-4-05-lpmns/` | Loi sur la protection des monuments, de la nature et des sites (LPMNS) (L 4 05) | 1 | current text only, in force since 1 June 2025 |
| `l-4-10-lprlac/` | Loi sur la protection générale des rives du lac (LPRLac) (L 4 10) | 1 | current text only, in force since 4 July 2026 |
| `l-4-13/` | Loi sur la protection générale des rives du Rhône (LPRRhône) (L 4 13) | 1 | current text only, in force since 1 January 2026 |
| `l-4-16-lprarve/` | Loi sur la protection générale et l’aménagement des rives de l’Arve (LPRArve) (L 4 16) | 1 | current text only, in force since 4 July 2026 |
| `l-4-19-lprvers/` | Loi sur la protection générale et l’aménagement des rives de la Versoix (LPRVers) (L 4 19) | 1 | current text only, in force since 4 July 2026 |
| `l-5-05-lci/` | Loi sur les constructions et les installations diverses (LCI) (L 5 05) | 1 | current text only, in force since 22 October 2025 |
| `l-5-11-lplomb/` | Loi sur l’emploi du plomb et de ses composés dans les travaux publics et dans les travaux privés du bâtiment (LPlomb) (L 5 11) | 1 | current text only, in force since 27 January 2007 |
| `l-5-20-ldtr/` | Loi sur les démolitions, transformations et rénovations de maisons d’habitation (mesures de soutien en faveur des locataires et de l’emploi) (LDTR) (L 5 20) | 1 | current text only, in force since 4 September 2018 |
| `l-5-25-lram/` | Loi sur le ramonage et les contrôles spécifiques des émanations de fumées (LRam) (L 5 25) | 1 | current text only, in force since 1 January 2000 |
| `l-5-40-lpai/` | Loi sur l’exercice des professions d’architecte et d’ingénieur (LPAI) (L 5 40) | 1 | current text only, in force since 4 September 2018 |
| `l-7-05-lex-ge/` | Loi sur l’expropriation pour cause d’utilité publique(2) (LEx-GE) (L 7 05) | 1 | current text only, in force since 12 February 2022 |
| `m-1-05-lamf/` | Loi sur les améliorations foncières (LAmF) (M 1 05) | 1 | current text only, in force since 1 June 2025 |
| `m-1-10-laldfr/` | Loi d’application de la loi fédérale sur le droit foncier rural (LaLDFR) (M 1 10) | 1 | current text only, in force since 19 November 2016 |
| `m-1-15-lalbfa/` | Loi d’application de la loi fédérale sur le bail à ferme agricole (LaLBFA) (M 1 15) | 1 | current text only, in force since 4 September 2018 |
| `m-2-05-lpromagr/` | Loi sur la promotion de l'agriculture (LPromAgr) (M 2 05) | 1 | current text only, in force since 4 July 2026 |
| `m-2-25-lprur/` | Loi sur la police rurale (LPRur) (M 2 25) | 1 | current text only, in force since 1 May 2018 |
| `m-2-30-laocea/` | Loi d’application des ordonnances fédérales sur les contributions versées aux exploitants agricoles (LaOCEA) (M 2 30) | 1 | current text only, in force since 1 May 2018 |
| `m-2-40-lsdjf/` | Loi pour la sauvegarde et le développement des jardins familiaux (LSDJF) (M 2 40) | 1 | current text only, in force since 6 January 1961 |
| `m-2-50-lvit/` | Loi sur la viticulture (LVit) (M 2 50) | 1 | current text only, in force since 27 March 2021 |
| `m-3-25-lfce/` | Loi sur le fonds cantonal des épizooties(4) (LFCE) (M 3 25) | 1 | current text only, in force since 16 November 2002 |
| `m-3-45-lchiens/` | Loi sur les chiens (LChiens) (M 3 45) | 1 | current text only, in force since 29 April 2023 |
| `m-4-06/` | Loi sur la pêche (LPêche) (M 4 06) | 1 | current text only, in force since 28 February 2023 |
| `m-5-05-lfaune/` | Loi sur la faune (LFaune) (M 5 05) | 1 | current text only, in force since 23 March 2024 |
| `m-5-10/` | Loi sur les forêts (LForêts) (M 5 10) | 1 | current text only, in force since 23 March 2024 |
| `m-5-15-lbio/` | Loi sur la biodiversité (LBio) (M 5 15) | 1 | current text only, in force since 15 November 2022 |
| `m-5-25-lge/` | Loi sur les gardes de l’environnement et autres agents techniques chargés de fonctions de police (LGE) (M 5 25) | 1 | current text only, in force since 1 May 2018 |
| `m-5-30-lmba/` | Loi visant à promouvoir des mesures en faveur de la biodiversité et de la qualité du paysage en agriculture (LMBA) (M 5 30) | 1 | current text only, in force since 1 May 2018 |
| `m-5-38-lccdb/` | Loi instituant une commission consultative de la diversité biologique (LCCDB) (M 5 38) | 1 | current text only, in force since 4 November 2023 |
| `a-2-04-03-rfrrt/` | Règlement sur le fonds de régulation dans le cadre de la réforme de la répartition des tâches entre les communes et le canton (RFRRT) (A 2 04.03) | 1 | current text only, in force since 29 August 2023 |
| `a-2-05-03-rpspa-lrt-1/` | Règlement sur les prestations de soutien aux personnes âgées délivrées par les communes, en application de la loi sur la répartition des tâches entre les communes et le canton (1er train) (RPSPA-LRT-1) (A 2 05.03) | 1 | current text only, in force since 1 January 2023 |
| `a-2-08-01-ripad/` | Règlement d'application de la loi sur l'information du public, l'accès aux documents et la protection des données personnelles (RIPAD) (A 2 08.01) | 1 | current text only, in force since 1 February 2025 |
| `a-2-20-01-rcof/` | Règlement sur les commissions officielles (RCOf) (A 2 20.01) | 1 | current text only, in force since 4 July 2026 |
| `a-2-24-01-roidp/` | Règlement sur l’organisation des institutions de droit public (ROIDP) (A 2 24.01) | 1 | current text only, in force since 8 July 2026 |
| `a-2-55-01-rietr/` | Règlement d’application de la loi sur l’intégration des étrangers (RIEtr) (A 2 55.01) | 1 | current text only, in force since 29 August 2023 |
| `a-2-70-01-rcsmu/` | Règlement d'application de la loi relative à la politique de cohésion sociale en milieu urbain (RCSMU) (A 2 70.01) | 1 | current text only, in force since 4 September 2018 |
| `a-2-75-01-rle/` | Règlement d'application de la loi sur la laïcité de l'Etat (RLE) (A 2 75.01) | 1 | current text only, in force since 24 June 2020 |
| `a-4-05-01-rdcg/` | Règlement d’application de la loi sur le droit de cité genevois (RDCG) (A 4 05.01) | 1 | current text only, in force since 1 September 2024 |
| `a-4-05-04-rcog/` | Règlement concernant la détermination des communes d’origine des citoyens genevois (RCOG) (A 4 05.04) | 1 | current text only, in force since 29 August 2023 |
| `a-5-05-01-redp/` | Règlement d’application de la loi sur l’exercice des droits politiques (REDP) (A 5 05.01) | 1 | current text only, in force since 11 February 2026 |
| `a-5-05-03-rdaevg/` | Règlement concernant la délimitation des arrondissements électoraux de la Ville de Genève (RDAEVG) (A 5 05.03) | 1 | current text only, in force since 7 July 2011 |
| `b-1-15-03-rce/` | Règlement pour l’organisation du Conseil d’Etat de la République et canton de Genève (RCE) (B 1 15.03) | 1 | current text only, in force since 22 March 2023 |
| `b-1-20-01-rtrcecc/` | Règlement concernant la retraite des membres du Conseil d'Etat, de la chancelière ou du chancelier d'Etat et des magistrates et magistrats de la Cour des comptes (RTRCECC) (B 1 20.01) | 1 | current text only, in force since 1 July 2026 |
| `b-1-20-03-rifce/` | Règlement relatif aux indemnités de représentation et à la prise en charge des frais effectifs des membres du Conseil d’Etat et de la chancelière ou du chancelier d’Etat (RIFCE) (B 1 20.03) | 1 | current text only, in force since 1 June 2023 |
| `b-1-25-01-rprot/` | Règlement sur le protocole (RProt) (B 1 25.01) | 1 | current text only, in force since 1 June 2025 |
| `b-1-30-12-rpepv/` | Règlement pour la promotion de l'égalité et la prévention des violences (RPEPV) (B 1 30.12) | 1 | current text only, in force since 7 June 2023 |
| `b-2-05-01-rfpp/` | Règlement d’exécution de la loi sur la forme, la publication et la promulgation des actes officiels(2) (RFPP) (B 2 05.01) | 1 | current text only, in force since 29 August 2023 |
| `b-2-10-01-rfao/` | Règlement sur la Feuille d'avis officielle de la République et canton de Genève (RFAO) (B 2 10.01) | 1 | current text only, in force since 13 January 2025 |
| `b-2-15-01-rarch/` | Règlement d’application de la loi sur les archives publiques (RArch) (B 2 15.01) | 1 | current text only, in force since 1 June 2025 |
| `b-2-15-03-remarch/` | Règlement fixant les tarifs des émoluments des Archives d’Etat de Genève (REmArch) (B 2 15.03) | 1 | current text only, in force since 27 August 2014 |
| `b-3-05-03-rdid/` | Règlement relatif aux documents d'identité (RDId) (B 3 05.03) | 1 | current text only, in force since 29 August 2023 |
| `b-3-15-04-rls/` | Règlement relatif à la légalisation des signatures (RLS) (B 3 15.04) | 1 | current text only, in force since 29 August 2023 |
| `b-3-20-03-rsaa/` | Règlement relatif à la signature des actes authentiques et autres actes concernant le domaine immobilier (RSAA) (B 3 20.03) | 1 | current text only, in force since 25 January 2023 |
| `b-3-25-04/` | Règlement sur les cartes de légitimation attestant un pouvoir d’autorité (RCLég) (B 3 25.04) | 1 | current text only, in force since 29 August 2023 |
| `b-4-05-14-rsgc/` | Règlement sur les secrétaires généraux de départements et le collège des secrétaires généraux(2) (RSGC) (B 4 05.14) | 1 | current text only, in force since 15 November 2018 |
| `b-4-05-20-robac/` | Règlement sur l’ouverture des bureaux de l’administration cantonale (ROBAC) (B 4 05.20) | 1 | current text only, in force since 1 January 1988 |
| `b-4-05-22-rope/` | Règlement de l’office du personnel de l’Etat(14) (ROPE) (B 4 05.22) | 1 | current text only, in force since 5 May 2026 |
| `b-4-10-03-remac/` | Règlement sur les émoluments de l’administration cantonale (REmAC) (B 4 10.03) | 1 | current text only, in force since 1 September 2021 |
| `b-4-20-03-rcca/` | Règlement de la centrale commune d'achats (RCCA) (B 4 20.03) | 1 | current text only, in force since 29 August 2023 |
| `b-4-23-01-rael/` | Règlement sur l’administration en ligne (RAeL) (B 4 23.01) | 1 | current text only, in force since 3 July 2019 |
| `b-4-23-03-rogsic/` | Règlement sur l'organisation et la gouvernance des systèmes d'information et de communication (ROGSIC) (B 4 23.03) | 1 | current text only, in force since 14 November 2023 |
| `b-4-25-04-rinv/` | Règlement concernant les inventaires et l’assurance-incendie des biens de l’Etat (RInv) (B 4 25.04) | 1 | current text only, in force since 29 August 2023 |
| `b-4-30-08-rpst/` | Règlement concernant la protection de la santé et la sécurité du travail au sein de l’administration cantonale (RPST) (B 4 30.08) | 1 | current text only, in force since 5 May 2026 |
| `b-4-40-01-rstat/` | Règlement d’exécution de la loi sur la statistique publique cantonale (RStat) (B 4 40.01) | 1 | current text only, in force since 7 March 2018 |
| `b-4-40-03-rregbl/` | Règlement relatif à la mise en œuvre de la législation fédérale sur le registre fédéral des bâtiments et des logements (RRegBL) (B 4 40.03) | 1 | current text only, in force since 11 November 2020 |
| `b-4-40-05-remstat/` | Règlement sur les émoluments requis pour les prestations de l’office cantonal de la statistique (REmStat) (B 4 40.05) | 1 | current text only, in force since 29 August 2023 |
| `b-5-05-01-rpac/` | Règlement d’application de la loi générale relative au personnel de l’administration cantonale, du pouvoir judiciaire et des établissements publics médicaux(19) (RPAC) (B 5 05.01) | 1 | current text only, in force since 5 May 2026 |
| `b-5-05-03-rcsac/` | Règlement sur les cadres supérieurs de l’administration cantonale (RCSAC) (B 5 05.03) | 1 | current text only, in force since 24 July 2019 |
| `b-5-05-06-rciac/` | Règlement sur les cadres intermédiaires de l’administration cantonale (RCIAC) (B 5 05.06) | 1 | current text only, in force since 5 May 2026 |
| `b-5-05-09-rppe/` | Règlement concernant les prestations complémentaires aux magistrats et aux membres du personnel de l’Etat en cas d’accidents (RPPE) (B 5 05.09) | 1 | current text only, in force since 5 May 2026 |
| `b-5-05-10-rppers/` | Règlement relatif à la protection de la personnalité à l'Etat de Genève (RPPers) (B 5 05.10) | 1 | current text only, in force since 26 March 2022 |
| `b-5-05-11-regal/` | Règlement pour l'égalité et la prévention des discriminations en raison du sexe, de l'orientation sexuelle et de l'identité de genre (REgal) (B 5 05.11) | 1 | current text only, in force since 28 August 2019 |
| `b-5-05-13-rtac/` | Règlement sur le télétravail dans l'administration cantonale (RTAC) (B 5 05.13) | 1 | current text only, in force since 1 January 2026 |
| `b-5-05-15-rrcs/` | Règlement concernant la responsabilité des caissiers des services de l’administration cantonale (RRCS) (B 5 05.15) | 1 | current text only, in force since 25 March 2026 |
| `b-5-07-01-rpla/` | Règlement d'application de la loi sur la protection des lanceurs d'alerte au sein de l'Etat (RPLA) (B 5 07.01) | 1 | current text only, in force since 26 March 2022 |
| `b-5-10-04-rstce/` | Règlement fixant le statut des membres du corps enseignant primaire, secondaire et tertiaire B(46) (RStCE) (B 5 10.04) | 1 | current text only, in force since 27 May 2026 |
| `b-5-10-17-rstce-hes-mne/` | Règlement fixant le statut du corps enseignant HES de l'unité décentralisée de Neuchâtel de la Haute école de musique – Conservatoire supérieur de musique de Genève (RStCE-HES-MNE) (B 5 10.17) | 1 | current text only, in force since 4 September 2018 |
| `b-5-15-01-rtrait/` | Règlement d’application de la loi concernant le traitement et les diverses prestations alloués aux membres du personnel de l’Etat, du pouvoir judiciaire et des établissements hospitaliers(30) (RTrait) (B 5 15.01) | 1 | current text only, in force since 5 May 2026 |
| `b-5-15-04-rcomef/` | Règlement instituant une commission de réexamen en matière d’évaluation des fonctions (RComEF) (B 5 15.04) | 1 | current text only, in force since 5 May 2026 |
| `b-5-15-10-rtrens/` | Règlement relatif au traitement des membres du personnel enseignant non nommé(15) (RTrEns) (B 5 15.10) | 1 | current text only, in force since 17 September 2025 |
| `b-5-15-13-ricepc/` | Règlement relatif aux indemnités du corps enseignant et des présidents de conférence(1) (RICEPC) (B 5 15.13) | 1 | current text only, in force since 6 September 2017 |
| `b-5-15-20-ratcv/` | Règlement relatif à l’adaptation des traitements au coût de la vie (RATCV) (B 5 15.20) | 1 | current text only, in force since 1 January 2026 |
| `b-5-15-22-rauvc/` | Règlement relatif à l’allocation unique de vie chère (RAUVC) (B 5 15.22) | 1 | current text only, in force since 11 February 2026 |
| `b-5-15-24/` | Règlement fixant les débours, frais de représentation et de déplacement et autres dépenses en faveur du personnel de l'administration cantonale (RDébours) (B 5 15.24) | 1 | current text only, in force since 5 May 2026 |
| `b-5-15-30-rcompers/` | Règlement instituant des commissions du personnel au sein de l’administration cantonale (RComPers) (B 5 15.30) | 1 | current text only, in force since 5 May 2026 |
| `b-5-15-34-rcomprest/` | Règlement instituant une commission paritaire chargée d’examiner l’amélioration générale des prestations offertes aux usagers des établissements publics médicaux (RComPrest) (B 5 15.34) | 1 | current text only, in force since 29 August 2023 |
| `b-5-22-05-rcpeg-23/` | Règlement d’application de l’article 23 de la loi instituant la Caisse de prévoyance de l’Etat de Genève (RCPEG-23) (B 5 22.05) | 1 | current text only, in force since 5 May 2026 |
| `b-6-05-01-rac/` | Règlement d’application de la loi sur l’administration des communes (RAC) (B 6 05.01) | 1 | current text only, in force since 1 September 2026 |
| `b-6-05-06/` | Règlement concernant l'écharpe des membres des conseils administratifs des communes (REchMCA)(2) (B 6 05.06) | 1 | current text only, in force since 1 June 2025 |
| `b-6-07-01-riaci/` | Règlement d'application de la loi sur les institutions autonomes communales et intercommunales de droit public (RIACI) (B 6 07.01) | 1 | current text only, in force since 1 September 2026 |
| `b-6-08-01-rrpfi/` | Règlement d'application de la loi sur le renforcement de la péréquation financière intercommunale et le développement de l'intercommunalité (RRPFI) (B 6 08.01) | 1 | current text only, in force since 1 January 2024 |
| `c-1-10-03-rip/` | Règlement d’application de certaines dispositions de la loi sur l’instruction publique (RIP) (C 1 10.03) | 1 | current text only, in force since 22 November 2023 |
| `c-1-10-04-rip-106/` | Règlement d’application de l’article 106 de la loi sur l’instruction publique(6) (RIP-106) (C 1 10.04) | 1 | current text only, in force since 1 January 2024 |
| `c-1-10-18-rdage/` | Règlement relatif aux dispenses d’âge (RDAge) (C 1 10.18) | 1 | current text only, in force since 26 August 2019 |
| `c-1-10-21-rep/` | Règlement de l’enseignement primaire (REP) (C 1 10.21) | 1 | current text only, in force since 3 June 2026 |
| `c-1-10-26-rco/` | Règlement du cycle d'orientation (RCO) (C 1 10.26) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-28-rco-9tc/` | Règlement du cycle d'orientation – projet d’innovation pédagogique 9e tronc commun (RCO-9TC) (C 1 10.28) | 1 | current text only, in force since 3 June 2026 |
| `c-1-10-31-rest/` | Règlement de l'enseignement secondaire II et tertiaire B (REST) (C 1 10.31) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-32-rdsae/` | Règlement sur le dispositif sport-art-études (RDSAE) (C 1 10.32) | 1 | current text only, in force since 4 December 2024 |
| `c-1-10-33-raes-ii/` | Règlement relatif à l'admission dans l'enseignement secondaire II (RAES-II) (C 1 10.33) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-34-rsads-ii/` | Règlement relatif au service de l'accueil du degré secondaire II(3) (RSADS-II) (C 1 10.34) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-35-rfcss/` | Règlement relatif à la formation complémentaire à un titre du degré secondaire II dans le domaine de la santé (RFCSS) (C 1 10.35) | 1 | current text only, in force since 18 August 2025 |
| `c-1-10-40-rptep/` | Règlement concernant les prestations fournies à des tiers, les ventes et l'octroi de dons par les écoles professionnelles (RPTEP) (C 1 10.40) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-48-rfpq/` | Règlement de la formation préqualifiante (RFPQ) (C 1 10.48) | 1 | current text only, in force since 6 May 2026 |
| `c-1-10-50-rcfpsa/` | Règlement du centre de formation professionnelle santé (RCFPSa) (C 1 10.50) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-51-rcfpc/` | Règlement du centre de formation professionnelle construction (RCFPC) (C 1 10.51) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-52-rcfpt/` | Règlement du centre de formation professionnelle technique (RCFPT) (C 1 10.52) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-53-rcfpso/` | Règlement du centre de formation professionnelle social (RCFPSo) (C 1 10.53) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-54-rcfpshr/` | Règlement du centre de formation professionnelle services et hôtellerie / restauration (RCFPSHR) (C 1 10.54) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-55-rcfpne/` | Règlement du centre de formation professionnelle nature et environnement (RCFPNE) (C 1 10.55) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-57-rcfpa/` | Règlement du centre de formation professionnelle arts (RCFPA) (C 1 10.57) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-58-rcfpcom/` | Règlement du centre de formation professionnelle commerce (RCFPCom) (C 1 10.58) | 1 | current text only, in force since 23 September 2026 |
| `c-1-10-69-recgad/` | Règlement relatif à l'école de culture générale pour adultes (RECGAd) (C 1 10.69) | 1 | current text only, in force since 23 September 2026 |
| `c-1-10-70-recg/` | Règlement relatif à l’école de culture générale (RECG) (C 1 10.70) | 1 | current text only, in force since 17 August 2026 |
| `c-1-10-71-rgymcg/` | Règlement relatif à la formation gymnasiale au collège de Genève (RGymCG) (C 1 10.71) | 1 | current text only, in force since 13 March 2024 |
| `c-1-10-72-rcad/` | Règlement relatif à la formation au collège pour adultes Alice-Rivaz (RCAd) (C 1 10.72) | 1 | current text only, in force since 19 August 2024 |
| `c-1-10-74-rmatupro/` | Règlement relatif à la maturité professionnelle (RMatuPro) (C 1 10.74) | 1 | current text only, in force since 23 September 2026 |
| `c-1-10-83-repriv/` | Règlement relatif à l’enseignement privé (REPriv) (C 1 10.83) | 1 | current text only, in force since 1 January 2025 |
| `c-1-12-05/` | Règlement sur la pédagogie spécialisée (RPSpéc) (C 1 12.05) | 1 | current text only, in force since 6 May 2025 |
| `c-1-20-01-rbpe/` | Règlement d'application de la loi sur les bourses et prêts d'études (RBPE) (C 1 20.01) | 1 | current text only, in force since 1 January 2025 |
| `c-1-20-08-repem/` | Règlement concernant l'exonération partielle des écolages aux élèves des écoles accréditées pour l'enseignement de la musique, de la rythmique, de la danse et du théâtre (REPEM) (C 1 20.08) | 1 | current text only, in force since 1 January 2024 |
| `c-1-26-05-rstcdhes-so-ge/` | Règlement sur le statut des membres du conseil de direction de la Haute école spécialisée de Suisse occidentale – Genève (RStCDHES-SO-GE) (C 1 26.05) | 1 | current text only, in force since 6 February 2019 |
| `c-1-30-10-rru/` | Règlement sur le rectorat de l'Université de Genève (RRU) (C 1 30.10) | 1 | current text only, in force since 6 March 2019 |
| `c-1-30-15-rchu/` | Règlement sur la collaboration hospitalo-universitaire et le statut du corps professoral (RCHU) (C 1 30.15) | 1 | current text only, in force since 5 April 2017 |
| `c-1-50-01-rsport/` | Règlement d'application de la loi sur le sport (RSport) (C 1 50.01) | 1 | current text only, in force since 23 April 2025 |
| `c-1-50-04-rsaps/` | Règlement concernant l'octroi de subventions en faveur de l'activité physique et sportive des populations à besoins spécifiques et des très jeunes enfants (RSAPS) (C 1 50.04) | 1 | current text only, in force since 1 January 2020 |
| `c-2-05-01-rfp/` | Règlement d'application de la loi sur la formation professionnelle (RFP) (C 2 05.01) | 1 | current text only, in force since 1 January 2025 |
| `c-2-05-26-rfcaga/` | Règlement relatif à la formation commerciale pour porteurs de maturité menant au diplôme cantonal d’assistant en gestion et en administration (RFCAGA) (C 2 05.26) | 1 | current text only, in force since 4 September 2018 |
| `c-2-08-01-rfca/` | Règlement d’application de la loi sur la formation continue des adultes(5) (RFCA) (C 2 08.01) | 1 | current text only, in force since 7 October 2026 |
| `c-2-10-01-riosp/` | Règlement d'application de la loi sur l'information et l'orientation scolaires et professionnelles (RIOSP) (C 2 10.01) | 1 | current text only, in force since 4 September 2018 |
| `c-3-05-01-rpcca/` | Règlement d'application de la loi pour la promotion de la culture et de la création artistique (RPCCA) (C 3 05.01) | 1 | current text only, in force since 14 May 2025 |
| `c-3-20-04-robs/` | Règlement sur l’administration de l’observatoire (RObs) (C 3 20.04) | 1 | current text only, in force since 4 September 2018 |
| `c-3-20-08-rdcobs/` | Règlement relatif au dépôt et à la comparaison des chronomètres à l’observatoire de Genève (RDCObs) (C 3 20.08) | 1 | current text only, in force since 4 September 2018 |
| `c-3-20-12-remobs/` | Règlement relatif aux émoluments pour les travaux spéciaux, perçus par l’observatoire (REmObs) (C 3 20.12) | 1 | current text only, in force since 27 August 2014 |
| `d-1-05-04-rpfcb/` | Règlement sur la planification financière et le contrôle budgétaire (RPFCB) (D 1 05.04) | 1 | current text only, in force since 5 May 2026 |
| `d-1-05-06-rpgfi/` | Règlement sur la planification et la gestion financière des investissements (RPGFI) (D 1 05.06) | 1 | current text only, in force since 5 November 2025 |
| `d-1-05-10-rgr/` | Règlement sur la gestion des risques(b) (RGR) (D 1 05.10) | 1 | current text only, in force since 4 September 2019 |
| `d-1-05-12-rrce/` | Règlement sur le recouvrement des créances de l'Etat (RRCE) (D 1 05.12) | 1 | current text only, in force since 1 September 2025 |
| `d-1-05-15-reef/` | Règlement sur l'établissement des états financiers (REEF) (D 1 05.15) | 1 | current text only, in force since 21 January 2026 |
| `d-1-05-20-rte/` | Règlement sur la trésorerie de l'Etat (RTE) (D 1 05.20) | 1 | current text only, in force since 29 August 2023 |
| `d-1-06-01-rfsi/` | Règlement d'application de la loi sur le financement de la solidarité internationale (RFSI) (D 1 06.01) | 1 | current text only, in force since 8 April 2026 |
| `d-1-07-01-rafong/` | Règlement d'application de la loi relative aux aides financières extraordinaires de l'Etat destinées aux organisations non gouvernementales à Genève touchées par le gel de l'aide internationale (RAFONG) (D 1 07.01) | 1 | current text only, in force since 25 April 2025 |
| `d-1-09-01-rsurv/` | Règlement d'application de la loi sur la surveillance de l'Etat (RSurv) (D 1 09.01) | 1 | current text only, in force since 27 October 2021 |
| `d-1-11-01-riaf/` | Règlement d'application de la loi sur les indemnités et les aides financières (RIAF) (D 1 11.01) | 1 | current text only, in force since 15 November 2023 |
| `d-1-15-03-rticc/` | Règlement relatif aux taux d'intérêt de la caisse des consignations (RTICC) (D 1 15.03) | 1 | current text only, in force since 1 January 2026 |
| `d-1-20-04-rceocpf/` | Règlement concernant les rapports de la caisse de l’Etat avec les offices cantonaux des poursuites et des faillites(3) (RCEOCPF) (D 1 20.04) | 1 | current text only, in force since 14 May 2019 |
| `d-1-30-04-rdpauvres/` | Règlement concernant la répartition des produits du monopole de l’alcool et des naturalisations ainsi que de la part de l’Etat au droit des pauvres(2) (RDPauvres) (D 1 30.04) | 1 | current text only, in force since 15 May 2014 |
| `d-3-05-04-rdlcp/` | Règlement d’application de diverses dispositions de la loi générale sur les contributions publiques (RDLCP) (D 3 05.04) | 1 | current text only, in force since 1 January 2026 |
| `d-3-05-12-rcp-110a/` | Règlement d’application de l’article 110A de la loi générale sur les contributions publiques (RCP-110A) (D 3 05.12) | 1 | current text only, in force since 6 March 1964 |
| `d-3-05-16-racv/` | Règlement concernant l’adaptation de certaines contributions au coût de la vie (RACV) (D 3 05.16) | 1 | current text only, in force since 11 September 2019 |
| `d-3-05-20-rcfc/` | Règlement concernant le calcul de la capacité financière des communes (RCFC) (D 3 05.20) | 1 | current text only, in force since 1 January 2024 |
| `d-3-08-01-ripp/` | Règlement d'application de la loi sur l'imposition des personnes physiques (RIPP) (D 3 08.01) | 1 | current text only, in force since 5 November 2025 |
| `d-3-08-05-rcepf/` | Règlement relatif à la compensation des effets de la progression à froid (RCEPF) (D 3 08.05) | 1 | current text only, in force since 1 January 2026 |
| `d-3-08-07/` | Règlement concernant la déduction en cas d'activité des 2 conjoints pour les périodes fiscales 2001 à 2009 (RDAC – 2001-2009) (D 3 08.07) | 1 | current text only, in force since 9 December 2010 |
| `d-3-08-08-rvl/` | Règlement relatif à la valeur locative (RVL) (D 3 08.08) | 1 | current text only, in force since 14 October 2026 |
| `d-3-08-10-rpldd/` | Règlement provisoire relatif à l'imposition d'après la dépense selon le droit fédéral harmonisé (RPLDD) (D 3 08.10) | 1 | current text only, in force since 1 January 2016 |
| `d-3-10-03-rivfi/` | Règlement fixant l'indexation de la valeur fiscale de certains immeubles (RIVFI) (D 3 10.03) | 1 | current text only, in force since 1 January 2026 |
| `d-3-17-05-rpfisc-12/` | Règlement d'application de l'article 12, alinéa 1, lettre k, de la loi de procédure fiscale (RPFisc-12) (D 3 17.05) | 1 | current text only, in force since 24 March 2018 |
| `d-3-17-07-rpfisc-29a/` | Règlement d'application de l'article 29A de la loi de procédure fiscale (RPFisc-29A) (D 3 17.07) | 1 | current text only, in force since 6 March 2024 |
| `d-3-18-01-rpgip/` | Règlement relatif à la perception et aux garanties des impôts des personnes physiques et des personnes morales (RPGIP) (D 3 18.01) | 1 | current text only, in force since 1 January 2025 |
| `d-3-18-03-rrid/` | Règlement concernant la remise en matière d'impôts directs (RRID) (D 3 18.03) | 1 | current text only, in force since 1 January 2024 |
| `d-3-18-04-rpgip-7-28/` | Règlement d'application des articles 7 et 28 de la loi relative à la perception et aux garanties des impôts des personnes physiques et des personnes morales (RPGIP-7-28) (D 3 18.04) | 1 | current text only, in force since 1 January 2026 |
| `d-3-19-03-remafc/` | Règlement fixant les émoluments de l'administration fiscale cantonale (REmAFC) (D 3 19.03) | 1 | current text only, in force since 1 January 2026 |
| `d-3-20-01-risp/` | Règlement d’application de la loi sur l’imposition à la source des personnes physiques et morales (RISP) (D 3 20.01) | 1 | current text only, in force since 1 January 2024 |
| `d-3-20-02/` | Règlement fixant les barèmes d'imposition à la source des personnes physiques et morales (RISP-Barèmes) (D 3 20.02) | 1 | current text only, in force since 1 January 2026 |
| `d-3-20-03-rcis/` | Règlement instituant une commission consultative en matière d'impôt à la source (RCIS) (D 3 20.03) | 1 | current text only, in force since 29 August 2023 |
| `d-3-25-03-rds-6-rde-28/` | Règlement d'application des articles 6, alinéa 2, de la loi sur les droits de succession et 28, alinéa 2, de la loi sur les droits d'enregistrement (RDS-6-RDE-28) (D 3 25.03) | 1 | current text only, in force since 24 December 2025 |
| `d-3-25-05/` | Règlement sur l’inventaire au décès (RInDé) (D 3 25.05) | 1 | current text only, in force since 1 January 1997 |
| `d-3-30-03-rde/` | Règlement d’application de l'article 8A de la loi sur les droits d'enregistrement (RDE) (D 3 30.03) | 1 | current text only, in force since 1 March 2026 |
| `d-3-35-01-rdatp/` | Règlement d’application de la loi sur la dation en paiement (RDatP) (D 3 35.01) | 1 | current text only, in force since 29 August 2023 |
| `d-3-45-01-rrcep/` | Règlement d’exécution de la loi sur la constitution de réserves de crise par l’économie privée (RRCEP) (D 3 45.01) | 1 | current text only, in force since 29 August 2023 |
| `d-3-80-04-rddff/` | Règlement d’application de diverses dispositions fiscales fédérales (RDDFF) (D 3 80.04) | 1 | current text only, in force since 29 August 2023 |
| `e-1-05-10-rtfmc/` | Règlement fixant le tarif des frais en matière civile (RTFMC) (E 1 05.10) | 1 | current text only, in force since 1 July 2025 |
| `e-1-05-15-rrc/` | Règlement fixant la rémunération des curateurs (RRC) (E 1 05.15) | 1 | current text only, in force since 6 March 2013 |
| `e-1-13-03-rec/` | Règlement sur l’état civil (REC) (E 1 13.03) | 1 | current text only, in force since 29 August 2023 |
| `e-1-13-09-remna/` | Règlement fixant le tarif des émoluments en matière de changement de nom et de prononcé d'adoption (REmNA) (E 1 13.09) | 1 | current text only, in force since 1 September 2023 |
| `e-1-21-02-roamcm/` | Règlement d’application de l’ordonnance fédérale sur l’activité à titre professionnel de mandataire visant à la conclusion d’un mariage ou à l’établissement d’un partenariat stable entre des personnes venant de l’étranger ou s’y rendant (ROAMCM) (E 1 21.02) | 1 | current text only, in force since 27 February 2026 |
| `e-1-25-01-rarpa/` | Règlement d’application de la loi sur l’avance et le recouvrement des pensions alimentaires (RARPA) (E 1 25.01) | 1 | current text only, in force since 1 January 2025 |
| `e-1-27-01-rpart-ge/` | Règlement d’application de la loi sur le partenariat (RPart-GE) (E 1 27.01) | 1 | current text only, in force since 29 August 2023 |
| `e-1-40-03-robjt/` | Règlement concernant les objets trouvés (RObjT) (E 1 40.03) | 1 | current text only, in force since 29 August 2023 |
| `e-1-46-01/` | Règlement sur la géoinformation (RGéo-GE) (E 1 46.01) | 1 | current text only, in force since 3 December 2025 |
| `e-1-50-04-rrf/` | Règlement sur le registre foncier (RRF) (E 1 50.04) | 1 | current text only, in force since 1 February 2025 |
| `e-1-50-06-remorfdit/` | Règlement sur le tarif des émoluments de l’office du registre foncier et de la direction de l’information du territoire(4) (REmORFDIT) (E 1 50.06) | 1 | current text only, in force since 24 April 2024 |
| `e-1-50-13-racbp/` | Règlement concernant les autorisations de construire dites « à bien plaire »(1) (RACBP) (E 1 50.13) | 1 | current text only, in force since 1 April 1959 |
| `e-2-05-04-raj/` | Règlement sur l'assistance juridique et l'indemnisation des conseils juridiques et défenseurs d'office en matière civile, administrative et pénale (RAJ) (E 2 05.04) | 1 | current text only, in force since 8 September 2021 |
| `e-2-05-05-rfcas/` | Règlement relatif à la formation spécifique des juges assesseurs de la chambre des assurances sociales de la Cour de justice(3) (RFCAS) (E 2 05.05) | 1 | current text only, in force since 29 August 2023 |
| `e-2-05-07-rntapi/` | Règlement fixant le nombre de juges assesseurs à élire au Tribunal administratif de première instance (RNTAPI) (E 2 05.07) | 1 | current text only, in force since 15 February 2018 |
| `e-2-05-08-rjtpae/` | Règlement relatif aux juges assesseurs et aux juges suppléants du Tribunal de protection de l'adulte et de l'enfant (RJTPAE) (E 2 05.08) | 1 | current text only, in force since 23 December 2017 |
| `e-2-05-09-rntpae/` | Règlement fixant le nombre de juges assesseurs à élire au Tribunal de protection de l'adulte et de l'enfant (RNTPAE) (E 2 05.09) | 1 | current text only, in force since 1 October 2024 |
| `e-2-05-10-rcgpj/` | Règlement de fonctionnement de la commission de gestion du pouvoir judiciaire de la République et canton de Genève (RCGPJ) (E 2 05.10) | 1 | current text only, in force since 27 October 2026 |
| `e-2-05-20-rfcsm/` | Règlement de fonctionnement du conseil supérieur de la magistrature (RFCSM) (E 2 05.20) | 1 | current text only, in force since 1 September 2025 |
| `e-2-05-30-rcpj/` | Règlement de fonctionnement de la conférence des présidents de juridiction (RCPJ) (E 2 05.30) | 1 | current text only, in force since 7 October 2014 |
| `e-2-05-40-rminpub/` | Règlement du Ministère public (RMinPub) (E 2 05.40) | 1 | current text only, in force since 2 December 2016 |
| `e-2-05-41-rtc/` | Règlement du Tribunal civil (RTC) (E 2 05.41) | 1 | current text only, in force since 1 May 2023 |
| `e-2-05-42/` | Règlement du Tribunal pénal (RTPén) (E 2 05.42) | 1 | current text only, in force since 1 October 2024 |
| `e-2-05-43-rtpae/` | Règlement du Tribunal de protection de l’adulte et de l’enfant (RTPAE) (E 2 05.43) | 1 | current text only, in force since 22 August 2014 |
| `e-2-05-44-rtph/` | Règlement du Tribunal des prud’hommes (RTPH) (E 2 05.44) | 1 | current text only, in force since 22 August 2014 |
| `e-2-05-45-rtmin/` | Règlement du Tribunal des mineurs (RTMin) (E 2 05.45) | 1 | current text only, in force since 1 January 2024 |
| `e-2-05-46-rtapi/` | Règlement du Tribunal administratif de première instance (RTAPI) (E 2 05.46) | 1 | current text only, in force since 1 June 2023 |
| `e-2-05-47-rcj/` | Règlement de la Cour de justice (RCJ) (E 2 05.47) | 1 | current text only, in force since 30 January 2015 |
| `e-2-05-48-rcapj/` | Règlement de la Cour d’appel du pouvoir judiciaire (RCAPJ) (E 2 05.48) | 1 | current text only, in force since 5 June 2019 |
| `e-2-05-50-rppj/` | Règlement du personnel du pouvoir judiciaire (RPPJ) (E 2 05.50) | 1 | current text only, in force since 1 January 2025 |
| `e-2-05-52-radpj/` | Règlement du pouvoir judiciaire sur l'accès aux documents et aux données personnelles (RADPJ) (E 2 05.52) | 1 | current text only, in force since 1 October 2024 |
| `e-2-05-53-rcompj/` | Règlement sur la communication du pouvoir judiciaire (RComPJ) (E 2 05.53) | 1 | current text only, in force since 1 December 2018 |
| `e-2-05-54-raipj/` | Règlement sur l'audit interne du pouvoir judiciaire de la République et canton de Genève (RAIPJ) (E 2 05.54) | 1 | current text only, in force since 1 March 2023 |
| `e-2-05-60-ritpj/` | Règlement relatif aux interprètes et traducteurs mis en œuvre par le pouvoir judiciaire (RITPJ) (E 2 05.60) | 1 | current text only, in force since 17 April 2019 |
| `e-2-20-03-remcsm/` | Règlement relatif à l’élection de certains membres du conseil supérieur de la magistrature (REMCSM) (E 2 20.03) | 1 | current text only, in force since 1 January 2011 |
| `e-2-40-03-ripj/` | Règlement concernant les indemnités allouées à divers magistrates et magistrats du pouvoir judiciaire, aux membres du Tribunal arbitral et aux membres du conseil supérieur de la magistrature(6) (RIPJ) (E 2 40.03) | 1 | current text only, in force since 21 February 2024 |
| `e-3-05-17-rsoe/` | Règlement relatif à la surveillance d’objets provenant d’évacuation(1) (RSOE) (E 3 05.17) | 1 | current text only, in force since 29 August 2023 |
| `e-3-10-03-rftph/` | Règlement sur la formation des juges et présidents du Tribunal des prud'hommes (RFTPH) (E 3 10.03) | 1 | current text only, in force since 14 June 2014 |
| `e-3-60-03-rtfacap/` | Règlement fixant le tarif des frais en matière d'assistance des communes pour la notification des actes de poursuite (RTFACAP) (E 3 60.03) | 1 | current text only, in force since 1 November 2022 |
| `e-4-05-03-rstp/` | Règlement sur la salubrité et la tranquillité publiques (RSTP) (E 4 05.03) | 1 | current text only, in force since 22 May 2024 |
| `e-4-10-03-rtfmp/` | Règlement fixant le tarif des frais en matière pénale (RTFMP) (E 4 10.03) | 1 | current text only, in force since 1 January 2025 |
| `e-4-10-04-rcpig/` | Règlement d’exécution du code pénal suisse en matière d'interruption de grossesse non punissable (RCPIG) (E 4 10.04) | 1 | current text only, in force since 27 February 2024 |
| `e-4-10-06-rmsop/` | Règlement concernant les modalités de signature des ordonnances pénales rendues par le service des contraventions (RMSOP) (E 4 10.06) | 1 | current text only, in force since 11 December 2024 |
| `e-4-10-15-rcomed/` | Règlement de fonctionnement de la commission d'évaluation de la dangerosité (RComED) (E 4 10.15) | 1 | current text only, in force since 3 December 2020 |
| `e-4-55-04-rleplp/` | Règlement concernant la liste des établissements pour l'exécution des privations de liberté à caractère pénal (détention avant jugement, peines et mesures, respectivement sanctions pénales en force ou subies à titre anticipé) (règlement sur les établissements)(1) (RLEPLP) (E 4 55.04) | 1 | current text only, in force since 1 January 2018 |
| `e-4-55-05-repm/` | Règlement sur l’exécution des peines et mesures(5) (REPM) (E 4 55.05) | 1 | current text only, in force since 1 July 2025 |
| `e-4-55-07-rsd/` | Règlement sur l'exécution des peines sous la forme de la semi-détention (RSD) (E 4 55.07) | 1 | current text only, in force since 1 July 2025 |
| `e-4-55-09-rtig/` | Règlement sur l'exécution des peines sous la forme du travail d’intérêt général (RTIG) (E 4 55.09) | 1 | current text only, in force since 1 January 2023 |
| `e-4-55-11-rse/` | Règlement sur l'exécution des peines privatives de liberté sous surveillance électronique (RSE) (E 4 55.11) | 1 | current text only, in force since 1 January 2023 |
| `e-4-55-13-rfaep/` | Règlement sur les formes alternatives d'exécution des peines (RFAEP) (E 4 55.13) | 1 | current text only, in force since 31 January 2025 |
| `e-4-55-15-rcs/` | Règlement concernant les sorties (RCS) (E 4 55.15) | 1 | current text only, in force since 1 July 2025 |
| `e-4-55-17-rplesorr/` | Règlement sur le processus latin d’exécution des sanctions orientée vers le risque et les ressources (RPLESORR) (E 4 55.17) | 1 | current text only, in force since 1 January 2025 |
| `e-4-58-01-redpm/` | Règlement concernant le concordat sur l'exécution de la détention pénale des personnes mineures des cantons romands (et partiellement du Tessin) (REDPM) (E 4 58.01) | 1 | current text only, in force since 1 January 2025 |
| `e-4-58-03-rddpdm/` | Règlement sur le droit disciplinaire applicable aux personnes détenues pénalement ou placées dans des établissements fermés pour mineurs (RDDPDM) (E 4 58.03) | 1 | current text only, in force since 16 April 2014 |
| `e-4-58-05-raspcm/` | Règlement concernant l’octroi d’autorisations de sortie aux personnes condamnées mineures (RASPCM) (E 4 58.05) | 1 | current text only, in force since 16 April 2014 |
| `e-5-10-03-rfpa/` | Règlement sur les frais, émoluments et indemnités en procédure administrative (RFPA) (E 5 10.03) | 1 | current text only, in force since 1 January 2025 |
| `e-6-05-01-rnot/` | Règlement d’exécution de la loi sur le notariat (RNot) (E 6 05.01) | 1 | current text only, in force since 29 August 2023 |
| `e-6-05-03-remnot/` | Règlement sur les émoluments des notaires (REmNot) (E 6 05.03) | 1 | current text only, in force since 30 April 2015 |
| `e-6-10-01-rpav/` | Règlement d’application de la loi sur la profession d’avocat (RPAv) (E 6 10.01) | 1 | current text only, in force since 1 January 2021 |
| `e-6-15-04-rhj/` | Règlement sur l’exercice de la profession d’huissier judiciaire (RHJ) (E 6 15.04) | 1 | current text only, in force since 29 August 2023 |
| `e-6-15-06-remhj/` | Règlement fixant le tarif des émoluments des huissiers judiciaires (REmHJ) (E 6 15.06) | 1 | current text only, in force since 6 March 2024 |
| `e-6-25-03-rma/` | Règlement relatif aux médiatrices et médiateurs assermentés (RMA) (E 6 25.03) | 1 | current text only, in force since 1 June 2023 |
| `e-6-25-04-rdem/` | Règlement relatif au dispositif d'encouragement à la médiation (RDEM) (E 6 25.04) | 1 | current text only, in force since 19 January 2024 |
| `f-1-05-01-ropol/` | Règlement sur l’organisation de la police (ROPol) (F 1 05.01) | 1 | current text only, in force since 24 December 2022 |
| `f-1-05-07-rgppol/` | Règlement général sur le personnel de la police (RGPPol) (F 1 05.07) | 1 | current text only, in force since 5 May 2026 |
| `f-1-05-08-rmipp/` | Règlement sur l'organe de médiation indépendante entre la population et la police(7) (RMIPP) (F 1 05.08) | 1 | current text only, in force since 29 May 2024 |
| `f-1-05-15-rempol/` | Règlement sur les émoluments et frais des services de police (REmPol) (F 1 05.15) | 1 | current text only, in force since 1 August 2024 |
| `f-1-05-18-rchpol/` | Règlement concernant les chiens de police (RChPol) (F 1 05.18) | 1 | current text only, in force since 5 May 2026 |
| `f-1-05-24-rsmpp/` | Règlement relatif aux soins médicaux des fonctionnaires de police et de la prison (RSMPP) (F 1 05.24) | 1 | current text only, in force since 5 May 2026 |
| `f-1-07-01-rapm/` | Règlement sur les agents de la police municipale (RAPM) (F 1 07.01) | 1 | current text only, in force since 1 June 2025 |
| `f-1-25-01-rcbvm/` | Règlement d’application de la loi sur les renseignements et les dossiers de police et la délivrance des certificats de bonne vie et mœurs (RCBVM) (F 1 25.01) | 1 | current text only, in force since 15 November 2018 |
| `f-1-50-01-ropp/` | Règlement sur l'organisation des établissements et le statut du personnel pénitentiaires (ROPP) (F 1 50.01) | 1 | current text only, in force since 5 May 2026 |
| `f-1-50-04-rrip/` | Règlement sur le régime intérieur de la prison et le statut des personnes incarcérées (RRIP) (F 1 50.04) | 1 | current text only, in force since 22 January 2026 |
| `f-1-50-06-rid/` | Règlement relatif à l’identification des détenus (RID) (F 1 50.06) | 1 | current text only, in force since 29 August 2023 |
| `f-1-50-08-repsd/` | Règlement relatif aux établissements ouverts ou fermés d’exécution des peines et des sanctions disciplinaires (REPSD) (F 1 50.08) | 1 | current text only, in force since 31 January 2025 |
| `f-1-50-09-ried/` | Règlement fixant les indemnités pour la direction et le personnel de surveillance des établissements de détention (RIED) (F 1 50.09) | 1 | current text only, in force since 29 August 2023 |
| `f-1-50-15-rcurabilis/` | Règlement de l'établissement de Curabilis (RCurabilis) (F 1 50.15) | 1 | current text only, in force since 31 January 2025 |
| `f-1-50-24/` | Règlement du centre éducatif de détention et d'observation de la Clairière (RClairière) (F 1 50.24) | 1 | current text only, in force since 29 November 2023 |
| `f-1-51-03-rbsa/` | Règlement sur la brigade de sécurité et des audiences (RBSA) (F 1 51.03) | 1 | current text only, in force since 28 February 2025 |
| `f-2-05-01-rsec/` | Règlement d’application de la loi sur le séjour et l’établissement des Confédérés (RSEC) (F 2 05.01) | 1 | current text only, in force since 29 August 2023 |
| `f-2-10-01-raletr/` | Règlement d'application de la loi fédérale sur les étrangers (RaLEtr) (F 2 10.01) | 1 | current text only, in force since 7 May 2024 |
| `f-2-10-02-raolcp/` | Règlement d'application de l'ordonnance fédérale sur la libre circulation des personnes(14) (RaOLCP) (F 2 10.02) | 1 | current text only, in force since 17 January 2024 |
| `f-2-12-04-rcrlmc/` | Règlement de la Conférence romande des chefs de département compétents en matière de police des étrangers concernant la Fondation romande de détention LMC (RCRLMC) (F 2 12.04) | 1 | current text only, in force since 2 September 2026 |
| `f-2-12-08-rframbois/` | Règlement de l'établissement concordataire de détention administrative de Frambois (RFrambois) (F 2 12.08) | 1 | current text only, in force since 1 February 2016 |
| `f-2-12-09-rfavra/` | Règlement de l'établissement de détention administrative de Favra (RFavra) (F 2 12.09) | 1 | current text only, in force since 29 August 2023 |
| `f-2-15-04-rrimpm/` | Règlement d'exécution concernant les mesures de réquisition d'immeubles en mains publiques aux fins d'héberger des personnes migrantes (RRIMPM) (F 2 15.04) | 1 | current text only, in force since 5 August 2017 |
| `f-2-20-08-rdrocpmc/` | Règlement relatif à la délivrance de renseignements et de documents, ainsi qu'à la perception de diverses taxes, par l'office cantonal de la population et des migrations(25) et les communes (RDROCPMC) (F 2 20.08) | 1 | current text only, in force since 29 August 2023 |
| `f-3-10-01-rmdpu/` | Règlement d'exécution de la loi sur les manifestations sur le domaine public (RMDPu) (F 3 10.01) | 1 | current text only, in force since 29 August 2023 |
| `f-3-17-01-rffsm/` | Règlement d’application de la loi concernant la facturation des frais de sécurité lors de manifestations (RFFSM) (F 3 17.01) | 1 | current text only, in force since 29 August 2023 |
| `f-3-18-02-r-cmvms/` | Règlement d'application du concordat instituant des mesures contre la violence lors de manifestations sportives (R-CMVMS) (F 3 18.02) | 1 | current text only, in force since 15 April 2017 |
| `f-3-20-01-rpr/` | Règlement d'application de la loi sur les procédés de réclame (RPR) (F 3 20.01) | 1 | current text only, in force since 31 August 2010 |
| `f-3-20-03-rtpr/` | Règlement fixant le tarif des procédés de réclame (RTPR) (F 3 20.03) | 1 | current text only, in force since 20 October 2000 |
| `f-3-30-03-rbains/` | Règlement sur les bains publics (RBains) (F 3 30.03) | 1 | current text only, in force since 29 August 2023 |
| `f-3-30-04-rpev/` | Règlement de la plage publique des Eaux-Vives (RPEV) (F 3 30.04) | 1 | current text only, in force since 19 October 2022 |
| `f-4-05-01-rpssp/` | Règlement d’application de la loi sur la prévention des sinistres, l’organisation et l’intervention des sapeurs-pompiers (RPSSP) (F 4 05.01) | 1 | current text only, in force since 29 August 2023 |
| `f-4-05-08-remfeu/` | Règlement fixant le tarif des émoluments applicables aux interventions effectuées par l’office cantonal de la protection de la population et des affaires militaires et la direction de l’inspectorat de la construction(10) (REmFeu) (F 4 05.08) | 1 | current text only, in force since 29 August 2023 |
| `f-4-15-01-rcssp/` | Règlement sur les caisses de secours et primes d’ancienneté des sapeurs-pompiers des trois arrondissements ruraux du canton de Genève : lac et Arve, Arve et Rhône, Rhône et lac (RCSSP) (F 4 15.01) | 1 | current text only, in force since 29 August 2023 |
| `g-1-05-03-rate/` | Règlement concernant l’application des prescriptions fédérales et cantonales sur la taxe d’exemption de l’obligation de servir (RaTE) (G 1 05.03) | 1 | current text only, in force since 29 August 2023 |
| `g-1-10-02-raths/` | Règlement d’application des prescriptions fédérales sur le tir hors du service (RaTHS) (G 1 10.02) | 1 | current text only, in force since 29 August 2023 |
| `g-1-25-03-rcmo/` | Règlement sur le corps de musique officiel de l'Etat de Genève (RCMO) (G 1 25.03) | 1 | current text only, in force since 1 June 2025 |
| `g-2-05-01-rproci/` | Règlement d’exécution de la loi d’application des dispositions fédérales en matière de protection civile (RProCi) (G 2 05.01) | 1 | current text only, in force since 1 September 2026 |
| `g-2-10-02-rapbc/` | Règlement d’application des dispositions fédérales sur la protection des biens culturels en cas de conflit armé (RaPBC) (G 2 10.02) | 1 | current text only, in force since 29 August 2023 |
| `g-3-02-02-ralaep/` | Règlement d'application de la loi fédérale sur l'approvisionnement économique du pays (RaLAEP) (G 3 02.02) | 1 | current text only, in force since 7 May 2024 |
| `g-3-03-04-rorca-ge/` | Règlement sur l'organisation en cas de catastrophe et de situation exceptionnelle (RORCA-GE) (G 3 03.04) | 1 | current text only, in force since 27 February 2024 |
| `h-1-05-01-ralcr/` | Règlement d’exécution de la loi d’application de la législation fédérale sur la circulation routière (RaLCR) (H 1 05.01) | 1 | current text only, in force since 24 May 2023 |
| `h-1-05-08-remocv/` | Règlement sur les émoluments de l’office cantonal des véhicules(34) (REmOCV) (H 1 05.08) | 1 | current text only, in force since 1 January 2026 |
| `h-1-05-12-rscfv/` | Règlement sur le service cantonal de la fourrière des véhicules(4) (RSCFV) (H 1 05.12) | 1 | current text only, in force since 1 August 2024 |
| `h-1-05-16-rpsa/` | Règlement sur les patrouilleurs et patrouilleuses scolaires adultes (RPSA) (H 1 05.16) | 1 | current text only, in force since 17 December 2025 |
| `h-1-10-03-rcsv/` | Règlement concernant la circulation et le stationnement des véhicules sur les terrains privés (RCSV) (H 1 10.03) | 1 | current text only, in force since 29 August 2023 |
| `h-1-21-03-rpmob/` | Règlement relatif aux plans de mobilité d'entreprises (RPMob) (H 1 21.03) | 1 | current text only, in force since 23 June 2021 |
| `h-1-31-01-rtvtc/` | Règlement d'exécution de la loi sur les taxis et les voitures de transport avec chauffeur (RTVTC) (H 1 31.01) | 1 | current text only, in force since 27 February 2026 |
| `h-1-40-02-raofct/` | Règlement d’application de l’ordonnance fédérale sur les concessions pour le transport des voyageurs (RaOFCT) (H 1 40.02) | 1 | current text only, in force since 29 August 2023 |
| `h-1-50-01-rrtp/` | Règlement d’exécution de la loi sur le réseau des transports publics (RRTP) (H 1 50.01) | 1 | current text only, in force since 15 November 2018 |
| `h-1-55-03-rrunireso/` | Règlement relatif aux conditions d'octroi des rabais sur les abonnements Unireso (RRUnireso) (H 1 55.03) | 1 | current text only, in force since 1 January 2025 |
| `h-1-80-01-rmd/` | Règlement sur la mobilité douce (RMD) (H 1 80.01) | 1 | current text only, in force since 29 August 2023 |
| `h-2-05-01-rnav/` | Règlement d’application de la loi sur la navigation dans les eaux genevoises (RNav) (H 2 05.01) | 1 | current text only, in force since 1 January 2026 |
| `h-3-05-02-rala/` | Règlement concernant l’exécution de la loi fédérale sur l’aviation(7) (RaLA) (H 3 05.02) | 1 | current text only, in force since 11 September 2019 |
| `h-3-15-03-rhydr/` | Règlement interdisant la descente des hydravions commerciaux sur la partie du lac de Genève entre le pont du Mont-Blanc et la Versoix (RHydr) (H 3 15.03) | 1 | current text only, in force since 7 July 2011 |
| `h-3-25-01-raig/` | Règlement d’application de la loi sur l’Aéroport international de Genève (RAIG) (H 3 25.01) | 1 | current text only, in force since 24 August 2022 |
| `i-1-05-01-rhom/` | Règlement d’exécution de la loi sur les heures d’ouverture des magasins(14) (RHOM) (I 1 05.01) | 1 | current text only, in force since 7 May 2024 |
| `i-1-10-03-raprix/` | Règlement d’application des dispositions fédérales sur l'indication des prix (RaPrix) (I 1 10.03) | 1 | current text only, in force since 7 May 2024 |
| `i-1-15-04/` | Règlement d’application de la loi fédérale sur la métrologie (RaLMétr) (I 1 15.04) | 1 | current text only, in force since 25 March 2026 |
| `i-1-35-02-ralfci/` | Règlement d'application de la loi fédérale sur le commerce itinérant (RaLFCI) (I 1 35.02) | 1 | current text only, in force since 27 February 2026 |
| `i-1-36-03-recde/` | Règlement instituant les entités chargées du développement de l'employabilité (RECDE) (I 1 36.03) | 1 | current text only, in force since 21 May 2025 |
| `i-1-37-01-rae/` | Règlement d'application de la loi sur l'aide aux entreprises (RAE) (I 1 37.01) | 1 | current text only, in force since 18 December 2024 |
| `i-1-45-01-rraa/` | Règlement d’application de la loi sur le renforcement de l'attractivité de l'audiovisuel (RRAA) (I 1 45.01) | 1 | current text only, in force since 4 July 2026 |
| `i-1-60-01-rtour/` | Règlement d’application de la loi sur le tourisme (RTour) (I 1 60.01) | 1 | current text only, in force since 27 February 2026 |
| `i-2-03-04-rieca/` | Règlement concernant l’installation, l'exploitation et le contrôle des appareils automatiques(12) (RIECA) (I 2 03.04) | 1 | current text only, in force since 7 May 2024 |
| `i-2-09-01-rcou/` | Règlement d’exécution de la loi sur le commerce d’objets usagés ou de seconde main(9) (RCOU) (I 2 09.01) | 1 | current text only, in force since 27 February 2026 |
| `i-2-12-01-raint/` | Règlement d’exécution de la loi sur les agentes et agents intermédiaires(25) (RAInt) (I 2 12.01) | 1 | current text only, in force since 29 August 2023 |
| `i-2-14-01-rces/` | Règlement concernant le concordat sur les entreprises de sécurité (RCES) (I 2 14.01) | 1 | current text only, in force since 5 May 2021 |
| `i-2-18-02-ralarm/` | Règlement d’application de la loi fédérale sur les armes, les accessoires d’armes et les munitions (RaLArm) (I 2 18.02) | 1 | current text only, in force since 5 May 2021 |
| `i-2-22-01-rrdbhd/` | Règlement d'exécution de la loi sur la restauration, le débit de boissons, l'hébergement et le divertissement (RRDBHD) (I 2 22.01) | 1 | current text only, in force since 14 October 2026 |
| `i-2-25-01-rtgveat/` | Règlement d'exécution de la loi sur la remise à titre gratuit et la vente à l'emporter de boissons alcooliques, de produits du tabac et de produits assimilés au tabac (RTGVEAT) (I 2 25.01) | 1 | current text only, in force since 14 October 2026 |
| `i-2-30-01-rvve/` | Règlement d’exécution de la loi sur les ventes volontaires aux enchères publiques (RVVE) (I 2 30.01) | 1 | current text only, in force since 27 February 2026 |
| `i-2-36-01-ridl/` | Règlement d’application de la loi instituant le dépôt légal (RIDL) (I 2 36.01) | 1 | current text only, in force since 29 August 2023 |
| `i-2-43-01/` | Règlement d'exécution de la loi sur les prêteurs professionnels, les prêts d'argent et l'octroi de crédits (RPrêt) (I 2 43.01) | 1 | current text only, in force since 27 February 2026 |
| `i-2-46-01-rtj/` | Règlement d’application de la loi sur les traducteurs-jurés (RTJ) (I 2 46.01) | 1 | current text only, in force since 29 August 2023 |
| `i-2-49-01-rprost/` | Règlement d'exécution de la loi sur la prostitution (RProst) (I 2 49.01) | 1 | current text only, in force since 27 February 2024 |
| `i-3-11-01-raljar/` | Règlement d'application de la loi d'application de la loi fédérale sur les jeux d'argent (RaLJAr) (I 3 11.01) | 1 | current text only, in force since 21 May 2025 |
| `i-3-15-09-rasport/` | Règlement sur l'aide au sport (RASport) (I 3 15.09) | 1 | current text only, in force since 29 August 2023 |
| `i-3-17-03/` | Règlement sur le Fonds de soutien genevois de la Loterie romande (RLoRo)(3) (I 3 17.03) | 1 | current text only, in force since 1 January 2025 |
| `i-3-20-04-rota/` | Règlement relatif à l’organisation de tirs aux armes à feu, à air comprimé, à traits ou à flèches (ROTA) (I 3 20.04) | 1 | current text only, in force since 29 August 2023 |
| `i-4-05-01-rgl/` | Règlement d’exécution de la loi générale sur le logement et la protection des locataires (RGL) (I 4 05.01) | 1 | current text only, in force since 1 February 2025 |
| `i-4-06-01-rup/` | Règlement d'exécution de la loi pour la construction de logements d'utilité publique (RUP) (I 4 06.01) | 1 | current text only, in force since 14 September 2022 |
| `i-4-10-01-rgfl/` | Règlement d’exécution de la loi protégeant les garanties fournies par les locataires (RGFL) (I 4 10.01) | 1 | current text only, in force since 23 October 1986 |
| `i-4-45-03-rconsign/` | Règlement relatif à la consignation du loyer (RConsign) (I 4 45.03) | 1 | current text only, in force since 1 February 2019 |
| `i-4-45-06-rphlc/` | Règlement relatif à la pénurie en matière d’habitations et de locaux commerciaux (RPHLC) (I 4 45.06) | 1 | current text only, in force since 9 September 2013 |
| `i-4-53-01-rapi/` | Règlement d’application de la loi sur l’aide à la propriété individuelle (RAPI) (I 4 53.01) | 1 | current text only, in force since 6 November 2019 |
| `i-4-55-01-raple/` | Règlement d’application de la loi encourageant l’accession à la propriété du logement par l’épargne-logement (RAPLE) (I 4 55.01) | 1 | current text only, in force since 29 August 2023 |
| `j-1-05-01-rirt/` | Règlement d’application de la loi sur l'inspection et les relations du travail (RIRT) (J 1 05.01) | 1 | current text only, in force since 14 October 2026 |
| `j-1-15-01-rcrct/` | Règlement d’application de la loi concernant la Chambre des relations collectives de travail (RCRCT) (J 1 15.01) | 1 | current text only, in force since 27 February 2026 |
| `j-1-15-03-rijcrct/` | Règlement fixant les indemnités allouées aux juges de la Chambre des relations collectives de travail (RIJCRCT) (J 1 15.03) | 1 | current text only, in force since 15 December 2023 |
| `j-2-05-01-rsels/` | Règlement d’exécution de la loi sur le service de l’emploi et la location de services (RSELS) (J 2 05.01) | 1 | current text only, in force since 27 February 2026 |
| `j-2-20-01-rmc/` | Règlement d’exécution de la loi en matière de chômage (RMC) (J 2 20.01) | 1 | current text only, in force since 27 February 2026 |
| `j-2-20-03-rccgc/` | Règlement relatif à la caisse cantonale genevoise de chômage (RCCGC) (J 2 20.03) | 1 | current text only, in force since 27 February 2026 |
| `j-3-05-01-ralamal/` | Règlement d’exécution de la loi d’application de la loi fédérale sur l’assurance-maladie (RaLAMal) (J 3 05.01) | 1 | current text only, in force since 1 January 2025 |
| `j-3-05-05/` | Règlement fixant les tarifs des prestations fournies par les maisons de naissance en 2012 (RTEH-2012)(a) (J 3 05.05) | 1 | current text only, in force since 1 January 2012 |
| `j-3-05-06-rthug-ssa/` | Règlement fixant les tarifs des prestations fournies par les Hôpitaux universitaires de Genève dans le domaine des soins somatiques aigus (régime sans convention) (RTHUG-SSA) (J 3 05.06) | 1 | current text only, in force since 1 January 2012 |
| `j-3-05-07-rtsna/` | Règlement fixant les tarifs des prestations fournies par les établissements publics médicaux dans le domaine des soins non aigus (régime sans convention) (RTSNA) (J 3 05.07) | 1 | current text only, in force since 1 January 2012 |
| `j-3-05-08-rtarmed/` | Règlement fixant la valeur du point TARMED pour les prestations médicales ambulatoires à charge de l'assurance obligatoire des soins (RTarmed) (J 3 05.08) | 1 | current text only, in force since 1 August 2024 |
| `j-3-05-09-rtjmm/` | Règlement fixant les tarifs des prestations fournies par les cliniques genevoises de Joli&#30;Mont et de Montana dans le domaine des soins non aigus (régime sans convention) (RTJMM) (J 3 05.09) | 1 | current text only, in force since 1 January 2014 |
| `j-3-05-10-rtpsrs-hug/` | Règlement fixant les tarifs provisoires des prestations de soins de réadaptation stationnaire fournies par les Hôpitaux universitaires de Genève, en l'absence de convention tarifaire (RTPSRS-HUG) (J 3 05.10) | 1 | current text only, in force since 1 January 2021 |
| `j-3-05-11-rtmn-2013/` | Règlement fixant le tarif des prestations fournies par les maisons de naissance dans le domaine des soins somatiques aigus pour l'année 2013 (régime sans convention) (RTMN-2013) (J 3 05.11) | 1 | current text only, in force since 1 January 2013 |
| `j-3-05-12-rfpnd/` | Règlement fixant les forfaits journaliers des hospitalisations de jour aux Hôpitaux universitaires de Genève pour les personnes non domiciliées dans le canton de Genève (RFPND) (J 3 05.12) | 1 | current text only, in force since 27 March 2019 |
| `j-3-05-13-rtphug-sp/` | Règlement fixant le tarif provisoire des prestations fournies par les Hôpitaux universitaires de Genève dans le domaine des soins psychiatriques (régime sans convention) (RTPHUG-SP) (J 3 05.13) | 1 | current text only, in force since 1 January 2014 |
| `j-3-05-14-rthp-ssa-2012/` | Règlement fixant les tarifs des prestations fournies par les hôpitaux privés non universitaires de Genève dans le domaine des soins somatiques aigus en 2012 (régime sans convention) (RTHP-SSA-2012) (J 3 05.14) | 1 | current text only, in force since 1 January 2012 |
| `j-3-05-16-rtcac/` | Règlement fixant le tarif-cadre des actes professionnels chiropratiques usuels à la charge de l’assurance obligatoire des soins (RTCAC) (J 3 05.16) | 1 | current text only, in force since 1 January 1998 |
| `j-3-05-17-rtphug-ssa/` | Règlement fixant le tarif provisoire des prestations fournies par les Hôpitaux universitaires de Genève dans le domaine des soins somatiques aigus (régime sans convention) (RTPHUG-SSA) (J 3 05.17) | 1 | current text only, in force since 1 January 2016 |
| `j-3-05-18-rpphysio/` | Règlement fixant la valeur du point des prestations fournies par les physiothérapeutes (RPPhysio) (J 3 05.18) | 1 | current text only, in force since 1 January 1999 |
| `j-3-05-19-rtpeh-tarpsy/` | Règlement fixant les tarifs provisoires des prestations de soins psychiatriques fournies par les établissements hospitaliers selon la structure tarifaire TARPSY (régime sans convention) (RTPEH-TARPSY) (J 3 05.19) | 1 | current text only, in force since 1 January 2018 |
| `j-3-05-20-rtcadom/` | Règlement fixant le tarif-cadre des prestations fournies par l’Institution genevoise de maintien à domicile(2) et Sitex SA en matière de soins aigus et de transition (RTCADom) (J 3 05.20) | 1 | current text only, in force since 27 March 2021 |
| `j-3-05-22-rtcisat/` | Règlement fixant le tarif-cadre des prestations fournies par les infirmières et infirmiers indépendants de la Coopérative de soins infirmiers (CSI), de la section genevoise de l'Association suisse des infirmières et infirmiers (ASI) et des autres organisations d'aide et de soins à domicile en matière de soins aigus et de transition(1) (RTCISAT) (J 3 05.22) | 1 | current text only, in force since 27 March 2021 |
| `j-3-05-23-rfrlamal/` | Règlement fixant les montants destinés à déterminer le financement résiduel selon l’article 25a de la loi fédérale sur l’assurance-maladie (RFRLAMal) (J 3 05.23) | 1 | current text only, in force since 1 January 2025 |
| `j-3-05-24-rtclao/` | Règlement fixant le tarif-cadre des prestations fournies par les logopédistes/orthophonistes à la charge de l’assurance obligatoire des soins (RTCLAO) (J 3 05.24) | 1 | current text only, in force since 1 January 1999 |
| `j-3-05-25-rtcpeh-streha/` | Règlement fixant le tarif-cadre provisoire des prestations de réadaptation stationnaire fournies par les établissements hospitaliers non universitaires selon la structure tarifaire ST Reha (régime sans convention) (RTCPEH-STReha) (J 3 05.25) | 1 | current text only, in force since 1 January 2022 |
| `j-3-05-26-rtppsy/` | Règlement fixant le tarif provisoire des prestations de psychothérapie pratiquées par les psychologues, dans le cadre de l'assurance obligatoire des soins, en l'absence de convention tarifaire, à compter du 1er juillet 2022 (RTPPsy) (J 3 05.26) | 1 | current text only, in force since 1 July 2022 |
| `j-3-05-28-rtcphd/` | Règlement fixant le tarif-cadre des prestations fournies par les pharmacies d’hospitalisation à domicile (RTCPHD) (J 3 05.28) | 1 | current text only, in force since 17 April 1997 |
| `j-3-05-30-rtcprsh/` | Règlement fixant les tarifs-cadres des prestations de réadaptation stationnaire hospitalières (régime sans convention) (RTCPRSH) (J 3 05.30) | 1 | current text only, in force since 7 June 2023 |
| `j-3-05-32-rtcsf/` | Règlement fixant le tarif-cadre des prestations fournies par les sages-femmes (RTCSF) (J 3 05.32) | 1 | current text only, in force since 1 January 1997 |
| `j-3-05-36-rtdo/` | Règlement fixant le tarif des conditions relatives à la prise en charge des traitements en cas de dépendance aux opiacés nécessitant la prescription d’héroïne (RTDO) (J 3 05.36) | 1 | current text only, in force since 1 May 2003 |
| `j-3-05-50-rafaos/` | Règlement sur l'admission des fournisseurs de prestations à pratiquer à la charge de l’assurance obligatoire des soins (RAFAOS) (J 3 05.50) | 1 | current text only, in force since 5 November 2025 |
| `j-3-05-52-rcomplanh/` | Règlement instituant une commission consultative en matière de planification hospitalière (RComPlanH) (J 3 05.52) | 1 | current text only, in force since 27 February 2024 |
| `j-3-20-03-rcna/` | Règlement concernant la caisse nationale suisse d’assurance en cas d’accidents(1) (RCNA) (J 3 20.03) | 1 | current text only, in force since 15 April 2017 |
| `j-3-20-06-rtmcna/` | Règlement fixant le tarif des prestations médicales pour la caisse nationale suisse d’assurance en cas d’accidents (RTMCNA) (J 3 20.06) | 1 | current text only, in force since 29 August 2023 |
| `j-3-25-04-rpeva/` | Règlement concernant les prestations aux élèves victimes d'accidents (RPEVA) (J 3 25.04) | 1 | current text only, in force since 5 May 2026 |
| `j-4-04-01-raslp/` | Règlement d'application de la loi sur l'aide sociale et la lutte contre la précarité (RASLP) (J 4 04.01) | 1 | current text only, in force since 1 March 2026 |
| `j-4-04-04-rcomasi/` | Règlement instituant une commission consultative de la politique d'asile (RComAsi) (J 4 04.04) | 1 | current text only, in force since 29 August 2023 |
| `j-4-06-01-rrdu/` | Règlement d'exécution de la loi sur le revenu déterminant unifié (RRDU) (J 4 06.01) | 1 | current text only, in force since 23 April 2025 |
| `j-4-09-04-ropad/` | Règlement sur l’office de protection de l’adulte(1) (ROPAd) (J 4 09.04) | 1 | current text only, in force since 28 February 2025 |
| `j-4-10-01-ralavi/` | Règlement d'exécution de la loi d'application de la loi fédérale sur l’aide aux victimes d’infractions (RaLAVI) (J 4 10.01) | 1 | current text only, in force since 14 November 2023 |
| `j-4-11-01-rapsa/` | Règlement d'application de la loi sur l’aide aux personnes sans abri (RAPSA) (J 4 11.01) | 1 | current text only, in force since 1 January 2025 |
| `j-4-12-01-rpls/` | Règlement d'application de la loi sur la prévention et la lutte contre le surendettement (RPLS) (J 4 12.01) | 1 | current text only, in force since 4 February 2026 |
| `j-4-15-04-rcollectes/` | Règlement sur les collectes (RCollectes) (J 4 15.04) | 1 | current text only, in force since 27 February 2026 |
| `j-4-18-01-rocas/` | Règlement d'exécution de la loi relative à l'office cantonal des assurances sociales(a) (ROCAS) (J 4 18.01) | 1 | current text only, in force since 24 January 2024 |
| `j-4-20-01-rpfc/` | Règlement d’application de la loi sur les prestations fédérales complémentaires à l’assurance-vieillesse et survivants et à l’assurance-invalidité(a) (RPFC) (J 4 20.01) | 1 | current text only, in force since 1 January 2025 |
| `j-4-20-04-rfmpc/` | Règlement relatif au remboursement des frais de maladie et des frais résultant de l'invalidité en matière de prestations complémentaires à l'assurance-vieillesse et survivants et à l'assurance-invalidité(a) (RFMPC) (J 4 20.04) | 1 | current text only, in force since 1 June 2024 |
| `j-4-25-03/` | Règlement relatif aux prestations cantonales complémentaires à l'assurance-vieillesse et survivants et à l’assurance-invalidité(a) (RPCC-AVS/AI) (J 4 25.03) | 1 | current text only, in force since 1 July 2025 |
| `j-4-25-04-rpcfam/` | Règlement relatif aux prestations complémentaires familiales (RPCFam) (J 4 25.04) | 1 | current text only, in force since 1 July 2025 |
| `j-5-03-06-rcomfam/` | Règlement instituant une commission cantonale de la famille (RComFam) (J 5 03.06) | 1 | current text only, in force since 28 August 2019 |
| `j-5-07-01-ramat/` | Règlement d’application de la loi instituant une assurance en cas de maternité et d’adoption (RAMat) (J 5 07.01) | 1 | current text only, in force since 1 January 2026 |
| `j-5-07-03-rcafcam/` | Règlement du conseil d’administration du fonds cantonal de compensation de l’assurance-maternité(7) (RCAFCAM) (J 5 07.03) | 1 | current text only, in force since 1 January 2026 |
| `j-5-10-01-raf/` | Règlement d’exécution de la loi sur les allocations familiales (RAF) (J 5 10.01) | 1 | current text only, in force since 1 January 2026 |
| `j-5-10-03-rcafaf/` | Règlement du conseil d’administration du fonds cantonal de compensation des allocations familiales (RCAFAF) (J 5 10.03) | 1 | current text only, in force since 1 January 2026 |
| `j-5-25-04-rcfn/` | Règlement instaurant une carte pour familles nombreuses (RCFN) (J 5 25.04) | 1 | current text only, in force since 4 September 2018 |
| `j-6-01-01-rej/` | Règlement d'application de la loi sur l'enfance et la jeunesse (REJ) (J 6 01.01) | 1 | current text only, in force since 1 January 2025 |
| `j-6-25-04-rifah/` | Règlement fixant les indemnités pour les familles d'accueil avec hébergement (RIFAH) (J 6 25.04) | 1 | current text only, in force since 12 November 2024 |
| `j-6-26-04-rpffpm/` | Règlement fixant la participation financière des père et mère aux frais de placement, ainsi qu’aux mesures de soutien et de protection du mineur (RPFFPM) (J 6 26.04) | 1 | current text only, in force since 1 January 2025 |
| `j-6-28-01-rapr/` | Règlement d'application de la loi sur l'accueil préscolaire (RAPr) (J 6 28.01) | 1 | current text only, in force since 17 September 2025 |
| `j-6-32-01-rajc/` | Règlement d’application de la loi sur l'accueil à journée continue (RAJC) (J 6 32.01) | 1 | current text only, in force since 16 September 2026 |
| `j-7-20-01-rgepa/` | Règlement d'application de la loi sur la gestion des établissements pour personnes âgées (RGEPA) (J 7 20.01) | 1 | current text only, in force since 20 May 2026 |
| `j-7-35-01-rrg/` | Règlement d’exécution de la loi concernant les Rentes genevoises – Assurance pour la vieillesse (RRG) (J 7 35.01) | 1 | current text only, in force since 29 August 2023 |
| `k-1-03-04/` | Règlement fixant les émoluments perçus par le département chargé de la santé(21) (REmSanté) (K 1 03.04) | 1 | current text only, in force since 1 January 2025 |
| `k-1-03-07-rreml/` | Règlement relatif à la régulation des équipements médico-techniques lourds (RREML) (K 1 03.07) | 1 | current text only, in force since 18 January 2020 |
| `k-1-04-01-rorsdom/` | Règlement d’application de la loi sur l’organisation du réseau de soins en vue du maintien à domicile (RORSDom) (K 1 04.01) | 1 | current text only, in force since 27 February 2024 |
| `k-1-15-01-ralepid/` | Règlement d’exécution de la loi d’application de la loi fédérale sur la lutte contre les maladies transmissibles de l’homme (loi sur les épidémies) (RaLEpid) (K 1 15.01) | 1 | current text only, in force since 29 August 2023 |
| `k-1-15-04-rfdd/` | Règlement relatif aux frais de désinfection et de désinfestation (RFDD) (K 1 15.04) | 1 | current text only, in force since 12 May 1983 |
| `k-1-15-08-rvof/` | Règlement concernant les vaccinations obligatoires et facultatives (RVOF) (K 1 15.08) | 1 | current text only, in force since 29 August 2023 |
| `k-1-15-12-rrv/` | Règlement relatif au remboursement du prix du vaccin (RRV) (K 1 15.12) | 1 | current text only, in force since 1 January 1984 |
| `k-1-15-16-rdfvg/` | Règlement relatif au décompte des frais pour les vaccinations publiques et gratuites (RDFVG) (K 1 15.16) | 1 | current text only, in force since 13 February 1986 |
| `k-1-15-18-rtrmd/` | Règlement fixant le tarif relatif au remboursement des mammographies de dépistage du cancer du sein (RTRMD) (K 1 15.18) | 1 | current text only, in force since 29 August 2023 |
| `k-1-15-24-rcsbp/` | Règlement relatif au contrôle sanitaire des bains publics (RCSBP) (K 1 15.24) | 1 | current text only, in force since 26 February 2020 |
| `k-1-18-01-rif/` | Règlement d'application relatif à la loi sur l'interdiction de fumer dans les lieux publics (RIF) (K 1 18.01) | 1 | current text only, in force since 7 May 2024 |
| `k-1-19-02-ralptab/` | Règlement d’application de la loi fédérale sur les produits du tabac et les cigarettes électroniques (RaLPTab) (K 1 19.02) | 1 | current text only, in force since 14 October 2026 |
| `k-1-21-01-rtsu/` | Règlement d'application de la loi sur les transports sanitaires urgents et l'aide sanitaire associée (RTSU) (K 1 21.01) | 1 | current text only, in force since 27 February 2024 |
| `k-1-21-03-rtrsa/` | Règlement fixant le tarif relatif au renforcement médical des services d’ambulances effectué par les services mobiles d’urgence et de réanimation de la brigade sanitaire cantonale (RTRSA) (K 1 21.03) | 1 | current text only, in force since 1 January 2005 |
| `k-1-21-04-rucsnp/` | Règlement relatif aux urgences communautaires et aux soins non programmés (RUCSNP) (K 1 21.04) | 1 | current text only, in force since 3 December 2025 |
| `k-1-36-01-riph/` | Règlement d’application de la loi sur l’intégration des personnes handicapées (RIPH) (K 1 36.01) | 1 | current text only, in force since 18 February 2019 |
| `k-1-37-01-raciis/` | Règlement d'exécution de la convention intercantonale relative aux institutions sociales (RaCIIS) (K 1 37.01) | 1 | current text only, in force since 19 August 2025 |
| `k-1-55-04-rcurml/` | Règlement du Centre universitaire romand de médecine légale, site de Genève (RCURML) (K 1 55.04) | 1 | current text only, in force since 29 August 2023 |
| `k-1-55-08/` | Règlement sur le sort du cadavre et la sépulture (RSép) (K 1 55.08) | 1 | current text only, in force since 1 October 2013 |
| `k-1-65-01-rcim/` | Règlement d’exécution de la loi sur les cimetières (RCim) (K 1 65.01) | 1 | current text only, in force since 29 August 2023 |
| `k-1-70-03-rcic/` | Règlement du comité interdépartemental de coordination (RCIC) (K 1 70.03) | 1 | current text only, in force since 18 May 2010 |
| `k-1-70-04-rcdd/` | Règlement du conseil du développement durable (RCDD) (K 1 70.04) | 1 | current text only, in force since 15 May 2024 |
| `k-1-70-05-ree/` | Règlement sur les évaluations environnementales (REE) (K 1 70.05) | 1 | current text only, in force since 29 August 2023 |
| `k-1-70-06-rapam/` | Règlement d’application des dispositions fédérales relatives à la protection contre les accidents majeurs et divers dangers pour la population et l’environnement (RaPAM) (K 1 70.06) | 1 | current text only, in force since 26 February 2025 |
| `k-1-70-07-rprni/` | Règlement sur la protection contre le rayonnement non ionisant des installations stationnaires (RPRNI) (K 1 70.07) | 1 | current text only, in force since 12 October 2023 |
| `k-1-70-08-rpair/` | Règlement sur la protection de l'air (RPAir) (K 1 70.08) | 1 | current text only, in force since 12 November 2025 |
| `k-1-70-09-rpics/` | Règlement régissant le dispositif d'urgence en cas de pics de pollution atmosphérique (RPics) (K 1 70.09) | 1 | current text only, in force since 18 November 2020 |
| `k-1-70-10-rpbv/` | Règlement sur la protection contre le bruit et les vibrations (RPBV) (K 1 70.10) | 1 | current text only, in force since 22 January 2025 |
| `k-1-70-11-rcompase/` | Règlement instituant une commission de protection contre les pollutions atmosphériques, sonores et l'électrosmog (RComPASE) (K 1 70.11) | 1 | current text only, in force since 16 October 2024 |
| `k-1-70-12-raorrchim/` | Règlement d'application de l'ordonnance fédérale sur la réduction des risques liés aux produits chimiques (RaORRChim) (K 1 70.12) | 1 | current text only, in force since 3 April 2024 |
| `k-1-70-13-rsol/` | Règlement sur la protection des sols (RSol) (K 1 70.13) | 1 | current text only, in force since 11 December 2024 |
| `k-1-70-14-rsdeb/` | Règlement sur les substances dangereuses dans l'environnement bâti (RSDEB) (K 1 70.14) | 1 | current text only, in force since 5 May 2026 |
| `k-1-70-20-remair/` | Règlement sur les émoluments du service de l'air, du bruit et des rayonnements non ionisants en matière de protection de l'air (REmAir) (K 1 70.20) | 1 | current text only, in force since 15 January 2020 |
| `k-1-70-21-rembruit/` | Règlement sur les émoluments du service de l'air, du bruit et des rayonnements non ionisants en matière de protection contre le bruit, les vibrations et les rayonnements non ionisants (REmBruit) (K 1 70.21) | 1 | current text only, in force since 8 March 2023 |
| `k-1-70-22-remtox/` | Règlement sur les émoluments du service de l’air, du bruit et des rayonnements non ionisants en matière de toxicologie de l'environnement bâti (REmTox) (K 1 70.22) | 1 | current text only, in force since 19 September 2018 |
| `k-1-71-03/` | Règlement fixant les émoluments pour les prestations du service de géologie, sols et déchets liées à la gestion du cadastre des sites pollués(2) (REmGéol) (K 1 71.03) | 1 | current text only, in force since 1 June 2014 |
| `k-2-05-06/` | Règlement sur les institutions de santé (RISanté) (K 2 05.06) | 1 | current text only, in force since 17 September 2025 |
| `k-3-02-01-rps/` | Règlement sur les professions de la santé (RPS) (K 3 02.01) | 1 | current text only, in force since 17 September 2025 |
| `k-3-02-03-rprc/` | Règlement sur les pratiques complémentaires (RPrC) (K 3 02.03) | 1 | current text only, in force since 2 June 2021 |
| `k-3-02-05-rtd/` | Règlement sur les techniciens-dentistes (RTD) (K 3 02.05) | 1 | current text only, in force since 29 August 2023 |
| `k-3-03-01-rcomps/` | Règlement concernant la constitution et le fonctionnement de la commission de surveillance des professions de la santé et des droits des patients (RComPS) (K 3 03.01) | 1 | current text only, in force since 1 June 2023 |
| `k-3-05-02-ralpma/` | Règlement d'application de la loi fédérale sur la procréation médicalement assistée (RaLPMA) (K 3 05.02) | 1 | current text only, in force since 27 February 2024 |
| `k-3-05-16-rcdps/` | Règlement fixant les compétences des départements en matière de professions de la santé (RCDPS) (K 3 05.16) | 1 | current text only, in force since 3 September 2019 |
| `k-3-07-03-rfiris/` | Règlement d'application de la loi sur le réseau communautaire d'informatique médicale (e-Toile) concernant la Fondation IRIS-GENEVE (RFIRIS) (K 3 07.03) | 1 | current text only, in force since 15 October 2014 |
| `k-3-10-03-ramds/` | Règlement sur les activités pouvant mettre en danger la santé (RAMDS) (K 3 10.03) | 1 | current text only, in force since 27 February 2024 |
| `k-4-05-12-rpth/` | Règlement sur les produits thérapeutiques (RPTh) (K 4 05.12) | 1 | current text only, in force since 17 September 2025 |
| `k-4-06-02-ralrh/` | Règlement d'application de la loi fédérale relative à la recherche sur l'être humain (RaLRH) (K 4 06.02) | 1 | current text only, in force since 2 October 2019 |
| `k-4-20-02-ralstup/` | Règlement relatif à l’application de la loi fédérale sur les stupéfiants et les substances psychotropes (RaLStup) (K 4 20.02) | 1 | current text only, in force since 1 January 2025 |
| `k-4-25-02-ralchim/` | Règlement d’exécution de la loi fédérale sur les produits chimiques (RaLChim) (K 4 25.02) | 1 | current text only, in force since 27 February 2026 |
| `k-5-02-01-raldal/` | Règlement d'exécution de la loi d’application de la législation fédérale sur les denrées alimentaires et les objets usuels (RaLDAl) (K 5 02.01) | 1 | current text only, in force since 7 May 2024 |
| `l-1-10-03-rcvp/` | Règlement concernant la classification des voies publiques (RCVP) (L 1 10.03) | 1 | current text only, in force since 29 August 2012 |
| `l-1-10-04-rorr/` | Règlement portant sur l'organisation du réseau routier (RORR) (L 1 10.04) | 1 | current text only, in force since 29 August 2023 |
| `l-1-10-06-rngab/` | Règlement sur les noms géographiques et l'adressage des bâtiments (RNGAB) (L 1 10.06) | 1 | current text only, in force since 1 March 2025 |
| `l-1-10-12-rudp/` | Règlement concernant l’utilisation du domaine public(2) (RUDP) (L 1 10.12) | 1 | current text only, in force since 3 December 2025 |
| `l-1-10-15-rtedp/` | Règlement fixant le tarif des empiétements sur ou sous le domaine public (RTEDP) (L 1 10.15) | 1 | current text only, in force since 4 September 2018 |
| `l-1-10-18-rlcan/` | Règlement sur la location de canalisations destinées à la télécommunication, propriété de l'Etat de Genève (RLCan) (L 1 10.18) | 1 | current text only, in force since 1 April 2026 |
| `l-1-20-01-rgd/` | Règlement d’application de la loi sur la gestion des déchets (RGD) (L 1 20.01) | 1 | current text only, in force since 1 February 2025 |
| `l-1-30-01-ralat/` | Règlement d’application de la loi d’application de la loi fédérale sur l’aménagement du territoire (RaLAT) (L 1 30.01) | 1 | current text only, in force since 1 July 2026 |
| `l-1-30-02-rtpd/` | Règlement transitoire sur la prime de démolition (RTPD) (L 1 30.02) | 1 | current text only, in force since 1 July 2026 |
| `l-1-30-04-rapav/` | Règlement d'application de la loi 10788 relative à l'aménagement du quartier «&nbsp;Praille-Acacias-Vernets&nbsp;» (RaPAV) (L 1 30.04) | 1 | current text only, in force since 25 June 2014 |
| `l-1-35-01-rgzd/` | Règlement d’application de la loi générale sur les zones de développement (RGZD) (L 1 35.01) | 1 | current text only, in force since 28 May 2025 |
| `l-1-40-01-rext/` | Règlement d’application de la loi sur l’extension des voies de communication et l’aménagement des quartiers ou localités(12) (RExt) (L 1 40.01) | 1 | current text only, in force since 1 February 2025 |
| `l-1-45-05-rziam/` | Règlement sur les zones industrielles et d'activités mixtes (RZIAM) (L 1 45.05) | 1 | current text only, in force since 6 December 2023 |
| `l-1-45-06-rdabzam/` | Règlement concernant la cession et le registre des droits à bâtir dans les zones de développement d'activités mixtes (RDABZAM) (L 1 45.06) | 1 | current text only, in force since 6 December 2023 |
| `l-1-55-03-rcua/` | Règlement sur les commissions d’urbanisme et d’architecture (RCUA) (L 1 55.03) | 1 | current text only, in force since 4 September 2018 |
| `l-2-05-01-reaux-ge/` | Règlement d’exécution de la loi sur les eaux (REaux-GE) (L 2 05.01) | 1 | current text only, in force since 1 February 2025 |
| `l-2-05-04-ruess/` | Règlement sur l'utilisation des eaux superficielles et souterraines (RUESS) (L 2 05.04) | 1 | current text only, in force since 1 January 2025 |
| `l-2-05-21-rtass/` | Règlement relatif aux taxes d'assainissement des eaux (RTAss) (L 2 05.21) | 1 | current text only, in force since 1 January 2025 |
| `l-2-05-27-rrcer/` | Règlement relatif à la renaturation des cours d’eau et des rives (RRCER) (L 2 05.27) | 1 | current text only, in force since 27 February 2024 |
| `l-2-10-01-roep/` | Règlement sur l’occupation des eaux publiques(6) (a) (ROEP) (L 2 10.01) | 1 | current text only, in force since 1 February 2025 |
| `l-2-15-03-rmorn/` | Règlement sur la manœuvre de l’ouvrage de régularisation du niveau du lac Léman à Genève (RMORN) (L 2 15.03) | 1 | current text only, in force since 4 September 2018 |
| `l-2-30-01-ren/` | Règlement d’application de la loi sur l’énergie (REn) (L 2 30.01) | 1 | current text only, in force since 1 November 2025 |
| `l-2-30-08-rccqe/` | Règlement de la commission consultative sur les questions énergétiques (RCCQE) (L 2 30.08) | 1 | current text only, in force since 4 June 2014 |
| `l-2-30-09-rcadiom/` | Règlement relatif à la commission consultative du réseau de distribution de chaleur à partir de l’usine des Cheneviers (RCadiom) (L 2 30.09) | 1 | current text only, in force since 1 June 2014 |
| `l-2-35-06-rcasim/` | Règlement concernant l’élection de 3 membres du conseil d’administration des Services industriels de Genève par les membres des conseils municipaux du canton, à l’exception de ceux de la Ville de Genève(9) (RCASIM) (L 2 35.06) | 1 | current text only, in force since 1 June 2025 |
| `l-2-35-10-rsig-1a/` | Règlement d'application de l'article 1A de la loi sur l'organisation des Services industriels de Genève (RSIG-1A) (L 2 35.10) | 1 | current text only, in force since 1 January 2011 |
| `l-2-40-01-rfder/` | Règlement d’application de la loi instituant 2 fonds pour le développement des énergies renouvelables et les économies d’énergie (RFDER) (L 2 40.01) | 1 | current text only, in force since 15 November 2018 |
| `l-2-45-01-rfaeb/` | Règlement d'application de la loi sur le financement de projets d'assainissement énergétique des bâtiments et sur l'ouverture de crédits d'investissement (RFAEB) (L 2 45.01) | 1 | current text only, in force since 8 July 2026 |
| `l-2-50-01-rdph/` | Règlement d'application de la loi 12936 ouvrant un crédit d'investissement de 10 000 000 de francs en faveur du développement d'un plan hydrogène cantonal (RDPH) (L 2 50.01) | 1 | current text only, in force since 13 November 2024 |
| `l-3-05-01-rmines/` | Règlement d’application de la loi sur les mines (RMines) (L 3 05.01) | 1 | current text only, in force since 1 February 2025 |
| `l-3-10-03-rgea/` | Règlement d’application de la loi sur les gravières et exploitations assimilées (RGEA) (L 3 10.03) | 1 | current text only, in force since 1 February 2025 |
| `l-4-05-01-rpmns/` | Règlement d’application de la loi sur la protection des monuments, de la nature et des sites (RPMNS) (L 4 05.01) | 1 | current text only, in force since 12 July 2023 |
| `l-4-05-04-rcva/` | Règlement sur la conservation de la végétation arborée (RCVA) (L 4 05.04) | 1 | current text only, in force since 1 April 2024 |
| `l-4-05-08-rmabt/` | Règlement relatif à la mise à ban temporaire d’emplacements dignes d’intérêt au titre de la protection de la nature (RMABT) (L 4 05.08) | 1 | current text only, in force since 17 June 2026 |
| `l-4-05-11-rppmf/` | Règlement sur la protection du paysage, des milieux naturels et de la flore (RPPMF) (L 4 05.11) | 1 | current text only, in force since 5 April 2023 |
| `l-5-05-01-rci/` | Règlement d’application de la loi sur les constructions et les installations diverses (RCI) (L 5 05.01) | 1 | current text only, in force since 14 October 2026 |
| `l-5-05-03-rchant/` | Règlement sur les chantiers (RChant) (L 5 05.03) | 1 | current text only, in force since 22 January 2025 |
| `l-5-05-05-recmc/` | Règlement concernant l'empreinte carbone des matériaux de construction (RECMC) (L 5 05.05) | 1 | current text only, in force since 22 October 2025 |
| `l-5-05-06-raci/` | Règlement concernant l'accessibilité des constructions et installations diverses (RACI) (L 5 05.06) | 1 | current text only, in force since 15 May 2024 |
| `l-5-05-08-rasc/` | Règlement concernant les ascenseurs et monte-charges(3) (RAsc) (L 5 05.08) | 1 | current text only, in force since 29 August 2023 |
| `l-5-05-10-rpsfp/` | Règlement relatif aux places de stationnement sur fonds privés (RPSFP) (L 5 05.10) | 1 | current text only, in force since 24 May 2023 |
| `l-5-05-20-rcamp/` | Règlement sur les campings (RCamp) (L 5 05.20) | 1 | current text only, in force since 5 April 2023 |
| `l-5-05-24-rahc/` | Règlement relatif à l’installation et à l’utilisation d’appareils employant comme dissolvant des hydrocarbures chlorés (RAHC) (L 5 05.24) | 1 | current text only, in force since 29 August 2023 |
| `l-5-20-01-rdtr/` | Règlement d’application de la loi sur les démolitions, transformations et rénovations de maisons d’habitation (RDTR) (L 5 20.01) | 1 | current text only, in force since 22 January 2025 |
| `l-5-25-01-rram/` | Règlement d’application de la loi sur le ramonage et les contrôles spécifiques des émanations de fumée (RRam) (L 5 25.01) | 1 | current text only, in force since 12 November 2024 |
| `l-5-30-02-ralexpl/` | Règlement d’application de la loi fédérale sur les substances explosibles (matières explosives et engins pyrotechniques)(5) (RaLExpl) (L 5 30.02) | 1 | current text only, in force since 3 September 2019 |
| `l-5-40-01-rpai/` | Règlement d’application de la loi sur l’exercice des professions d’architecte et d’ingénieur (RPAI) (L 5 40.01) | 1 | current text only, in force since 4 September 2018 |
| `l-6-05-01-rmp/` | Règlement sur la passation des marchés publics (RMP) (L 6 05.01) | 1 | current text only, in force since 29 August 2023 |
| `l-6-10-04-rfl/` | Règlement relatif aux fermes et loyers cantonaux (RFL) (L 6 10.04) | 1 | current text only, in force since 29 August 2023 |
| `m-1-05-01-ramf/` | Règlement d’application de la loi sur les améliorations foncières (RAmF) (M 1 05.01) | 1 | current text only, in force since 22 January 2025 |
| `m-1-10-01-raldfr/` | Règlement d’exécution de la loi d’application de la loi fédérale sur le droit foncier rural (RaLDFR) (M 1 10.01) | 1 | current text only, in force since 18 February 2019 |
| `m-2-05-01-rpromagr/` | Règlement d’application de la loi sur la promotion de l’agriculture (RPromAgr) (M 2 05.01) | 1 | current text only, in force since 11 March 2026 |
| `m-2-25-01-rprur/` | Règlement d'application de la loi sur la police rurale (RPRur) (M 2 25.01) | 1 | current text only, in force since 18 February 2019 |
| `m-2-30-01-raocea/` | Règlement d'exécution de la loi d'application des ordonnances fédérales sur les contributions versées aux exploitants agricoles (RaOCEA) (M 2 30.01) | 1 | current text only, in force since 18 February 2019 |
| `m-2-50-05-rvv/` | Règlement sur la vigne et les vins de Genève (RVV) (M 2 50.05) | 1 | current text only, in force since 1 April 2026 |
| `m-3-10-03-repaep/` | Règlement relatif à l'encouragement de la production animale et de l'estivage de proximité (REPAEP) (M 3 10.03) | 1 | current text only, in force since 6 November 2008 |
| `m-3-15-06-restiv/` | Règlement concernant l’estivage (REstiv) (M 3 15.06) | 1 | current text only, in force since 29 August 2023 |
| `m-3-20-02-ralfe/` | Règlement d’application de la loi fédérale sur les épizooties (RaLFE) (M 3 20.02) | 1 | current text only, in force since 18 November 2020 |
| `m-3-25-03-rfce/` | Règlement relatif au fonds cantonal des épizooties (RFCE) (M 3 25.03) | 1 | current text only, in force since 29 August 2023 |
| `m-3-45-01-rchiens/` | Règlement d'application de la loi sur les chiens (RChiens) (M 3 45.01) | 1 | current text only, in force since 29 August 2023 |
| `m-3-45-03-remca/` | Règlement relatif à l'examen pour moniteur canin agréé (REMCA) (M 3 45.03) | 1 | current text only, in force since 29 August 2023 |
| `m-3-50-02-ralpa/` | Règlement d'application de la loi fédérale sur la protection des animaux (RaLPA) (M 3 50.02) | 1 | current text only, in force since 27 February 2024 |
| `m-3-50-07-rfour/` | Règlement de la fourrière cantonale (RFour) (M 3 50.07) | 1 | current text only, in force since 12 December 2012 |
| `m-4-03-01-rcpl/` | Règlement d’exécution du concordat intercantonal sur la pêche dans le lac Léman (RCPL) (M 4 03.01) | 1 | current text only, in force since 1 January 2001 |
| `m-4-06-01/` | Règlement d’application de la loi sur la pêche (RPêche) (M 4 06.01) | 1 | current text only, in force since 27 February 2024 |
| `m-5-05-01-rfaune/` | Règlement d’application de la loi sur la faune (RFaune) (M 5 05.01) | 1 | current text only, in force since 1 January 2024 |
| `m-5-10-01/` | Règlement d’application de la loi sur les forêts (RForêts) (M 5 10.01) | 1 | current text only, in force since 1 February 2025 |
| `m-5-10-08-rcvf/` | Règlement concernant la circulation des véhicules automobiles et des cyclomoteurs dans les forêts, sites protégés, secteurs mis à ban et les cultures (RCVF) (M 5 10.08) | 1 | current text only, in force since 18 February 2019 |
| `m-5-15-01-rbio/` | Règlement d'application de la loi sur la biodiversité (RBio) (M 5 15.01) | 1 | current text only, in force since 8 April 2026 |
| `m-5-25-03-rocane/` | Règlement sur l'organisation des offices cantonaux chargés de l’agriculture, de la nature et de l’eau(2) (ROCANE) (M 5 25.03) | 1 | current text only, in force since 24 June 2026 |
| `m-5-30-01-rmba/` | Règlement d'application de la loi visant à promouvoir des mesures en faveur de la biodiversité et de la qualité du paysage en agriculture (RMBA) (M 5 30.01) | 1 | current text only, in force since 18 February 2019 |

## Source

SILGENEVE, the systematic collection of Geneva law (recueil systématique genevois, rsGE), published by the Chancellerie d'Etat, Service de la législation, at <https://silgeneve.ch/legis/>. Each act's page holds its consolidated text and a history table (adoption date and entry into force of every amendment).

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**.
- Each act's single version is dated by the latest entry into force in its history table on or before the retrieval day; it is the "oldest version available" and is credited to the publisher. Earlier wording is not held.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5, `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the headings of titles, chapters and sections. One paragraph or list item per line. Footnote markers are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the source document, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of each act's first commit is the publisher (SILGENEVE), because the text is the current consolidation rather than the act as adopted, with an e-mail address that cannot exist. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the Feuille d'avis officielle and the Recueil officiel. Only the current wording is held: the history of each act is not reconstructed yet. Only the acts listed above are included.
