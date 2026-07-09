∞ Kizuna Pro 🌸
Kizuna (絆) signifie les liens ou l'attachement. Musubi (結び) évoque le nœud qui unit les choses. Kizuna Pro est un simulateur et gestionnaire de paie ultra-graphique, construit autour d'un Sankey pour illustrer le lien de confiance entre l'entreprise et ses salariés, et l'assemblage des règles de calcul les plus complexes.

VersionLicenseFormat

Kizuna Pro n'est pas un logiciel de paie classique. Il s'agit d'une application web entièrement encapsulée dans un fichier SVG unique. Aucun backend, aucune base de données externe : tout fonctionne en local dans le navigateur via le localStorage, garantissant une confidentialité absolue des données de simulation.

✨ Fonctionnalités Principales
📊 Tableau de Bord Analytique
KPIs en temps réel : Masse salariale, Net à payer, Charges patronales, Coût Employeur Total.
Graphiques dynamiques : Évolution mensuelle (Brut/Net/Coût), répartition trimestrielle (Donut), Top 5 des salaires.
Analyse de Parité (H/F) : Calcul automatique de l'écart salarial moyen entre hommes et femmes.
⚙️ Moteur de Règles (Rule Engine)
Un vrai moteur de paie modulaire, capable de gérer l'évolution des lois year after year :

Profils de Cotisations : Créez des profils distincts (Cadre, Non-Cadre, Apprenti) et assignez-les à vos salariés.
Duplication de Profils : Dupliquez un profil existant en un clic (ex: "Standard 2024" -> "Standard 2025") pour mettre à jour les plafonds sans perdre l'historique.
Règles Dépendantes : Chaque règle possède un code (ex: MAL, VIEP). Vous pouvez utiliser le code d'une règle comme Base de calcul pour une autre règle (les règles s'évaluent de haut en bas).
Plafonds et PMSS dynamiques : Le SMIC et le PMSS sont attachés à chaque profil.
📄 Générateur de Bulletins de Paie
3 Modèles de mise en page :
Classique : Look administratif formel (police à chasse fixe, bordures strictes).
Moderne : Design SaaS épuré, cartes arrondies, couleurs de surbrillance.
Minimaliste : Typographie suisse, sans bordures, très aéré.
Paramétrage complet : Choix de la police, tailles, marges, couleurs des titres, notes de haut/bas de page.
Impression PDF : Génération de bulletins prêts à l'impression individuellement ou en lot.
🔄 Diagramme de Sankey Interactif
Visualisez en temps réel le flux financier de la paie : comment le Coût Employeur se divise en Brut et Charges Patronales, puis comment le Brut se transforme en Net Imposable et Net à Payer. Modifiez les taux ou le salaire de base avec des curseurs et voyez le diagramme s'animer.

👥 Gestion RH
Gestion des profils salariés (CDI/CDD, temps de travail, taux de PAS personnalisé).
Gestion du statut RQTH (baisse automatique des charges patronales via l'aide Agefiph).
Calcul automatique de la Réduction Fillon.
🚀 Comment l'utiliser ?
Téléchargez le fichier kizuna-pro.svg.
Ouvrez-le simplement avec un navigateur web moderne (Chrome, Firefox, Edge, Safari).
L'application se lance instantanément. Vos données sont sauvegardées automatiquement dans votre navigateur.
🛠️ Stack Technique
Kizuna Pro repose sur une architecture peu commune mais extrêmement robuste et portable :

SVG / XML : Conteneur principal.
HTML5 / XHTML : Interface utilisateur via foreignObject.
CSS3 : Styles, animations, grilles (CSS Grid/Flexbox).
JavaScript (Vanilla) : Aucune dépendance, aucun framework (React, Vue, etc.).
LocalStorage : Persistance des données.
⚠️ Disclaimer
Kizuna Pro est un outil de simulation et de pilotage RH. Bien que son moteur de règles soit puissant et personnalisable, les calculs de paie française étant d'une complexité extrême (multi-tranches, abattements journaliers, régularisations glissantes), cet outil ne remplace pas un logiciel de paie certifié (Silaé, PayFit, Cegid) pour la génération de la DSN légale.

📜 Licence
Distribué sous licence GNU. Voir le fichier LICENSE pour plus d'informations.


