# Site de prÃ©sentation Bataillon

Site statique servi par GitHub Pages Ã  partir de `site/`. Le workflow `../.github/workflows/pages.yml` publie ce dossier lors d'un changement sur `master`.

Une fois GitHub Pages activÃ© pour le dÃ©pÃ´t (`Settings â†’ Pages â†’ Build and deployment â†’ GitHub Actions`) et le dÃ©ploiement Actions terminÃ©, les URL Ã  dÃ©clarer dans App Store Connect sont :

- URL marketing : `https://omgprod.github.io/bataillon-site/`
- URL d'assistance : `https://omgprod.github.io/bataillon-site/assistance/`
- URL de politique de confidentialitÃ© : `https://omgprod.github.io/bataillon-site/confidentialite/`

Les deux derniÃ¨res pages sont conÃ§ues comme des documents autonomes, accessibles aussi depuis le pied de page. La page de confidentialitÃ© reflÃ¨te l'Ã©tat de l'application dÃ©crit dans `docs/ASC.md` : aucun service Game Center ni paiement rÃ©el n'est actuellement intÃ©grÃ©.

## Ã€ finaliser avant soumission

- Confirmer que Pages a Ã©tÃ© activÃ© et que les trois URL chargent en HTTPS aprÃ¨s le dÃ©ploiement.
- VÃ©rifier que `contact@babapp.fr` reÃ§oit bien les demandes avant soumission.
- Si Game Center, paiements ou analytique sont ajoutÃ©s, rÃ©viser la politique et les dÃ©clarations App Store avant de publier cette nouvelle version.
