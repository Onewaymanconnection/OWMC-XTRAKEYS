
# Intégration OWMC-XTRAKEYS dans Shopify (Thème Dawn)

Ce dossier contient un fichier personnalisé `main-product-owmc.liquid` destiné à être utilisé dans un thème Shopify basé sur **Dawn**.

## Fichier inclus

- `main-product-owmc.liquid`  
  Contient le design visuel du projet OWMC (style techno, image, description) + un **exemple de bouton Buy Button Shopify intégré**.

## Instructions d'intégration

1. Connectez-vous à l’admin Shopify
2. Allez dans **Boutique en ligne > Thèmes > Dawn > Modifier le code**
3. Dans le dossier `sections`, remplacez le fichier `main-product.liquid` par ce fichier :
   - Soit en renommant ce fichier en `main-product.liquid`
   - Soit en créant un nouveau modèle et en l'appelant via une autre page produit
4. Collez votre vrai code de **Buy Button Shopify** à la place du bouton test
5. Enregistrez et prévisualisez le thème

## Personnalisation

Le style est contenu dans une balise `<style>` dans le fichier. Vous pouvez l’adapter directement ou extraire le CSS dans un fichier `assets/style.css`.

## Auteur

Ce fichier est généré pour le projet **OWMC-XTRAKEYS** et ne doit pas être redistribué ou modifié sans autorisation.
