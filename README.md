#Read me de fin de TP

L’architecture de déploiement

Les secrets utilisés (noms uniquement) :

Les triggers

Le rollback

**Checklist de validation :**

Les secrets CI sont créés et référencés uniquement par nom dans les workflows :

Le build du frontend est produit en CI et uniquement son artefact est déployé sur le VPS :

Le déploiement Render est déclenché depuis la CI (pas de clic manuel) :

PM2 relance le service frontend après synchronisation des artefacts :

Un push sur la branche définie déclenche la mise à jour des deux cibles :

Le README explique comment rejouer un déploiement, consulter les logs, et effectuer un rollback :
