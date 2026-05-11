# OXV — Patch V1.1 léger

Objectif : conserver le design et l'organisation actuelle du site, tout en clarifiant le rôle central de l'application mobile, du paiement sécurisé et du parcours pilote.

## Ligne validée

OXV ne lance pas seulement une journée circuit. OXV lance un parcours pilote complet.

Le lancement officiel d'OXV se fera avec :

- application mobile ;
- pré-réservation ;
- dossier pilote ;
- documents véhicule ;
- paiement sécurisé ;
- informations de session ;
- contenus média centralisés.

---

## 1. Badge application

Remplacer les formulations de type :

```html
En développement
```

ou :

```html
Bientôt disponible
```

par :

```html
Parcours digital intégré
```

Pour le paiement, utiliser :

```html
Paiement sécurisé intégré au lancement
```

---

## 2. Bloc application mobile

Remplacer le bloc qui présente l'application mobile comme une fonctionnalité secondaire ou future par :

```html
<div class="app-note">
  <span class="status-badge">Parcours digital intégré</span>

  <h3>Avant la piste, le parcours pilote.</h3>

  <p>
    L'application OXV centralisera l'expérience dès le lancement :
    pré-réservation, dossier pilote, documents véhicule, paiement sécurisé,
    informations de session et contenus média.
  </p>
</div>
```

---

## 3. Texte réservation

Remplacer toute phrase qui laisse entendre que la réservation se fait hors application par :

```html
<p>
  La réservation sera confirmée depuis l'application OXV, après validation du dossier
  pilote et paiement sécurisé.
</p>
```

---

## 4. Texte paiement

Remplacer les formulations de type :

```html
Paiement bientôt disponible
```

ou les formulations contradictoires entre carte bancaire, virement et paiement différé par :

```html
<p>
  Le paiement sécurisé sera intégré au parcours OXV dès le lancement.
  La place sera confirmée après validation du dossier pilote et règlement
  depuis l'espace dédié.
</p>
```

---

## 5. Phrase courte pour la page d'accueil

À ajouter dans le hero ou dans une section parcours pilote existante :

```html
<p>
  Les premières sessions OXV ouvriront avec un parcours digital complet :
  application mobile, validation du dossier pilote et paiement sécurisé.
</p>
```

---

## 6. CTA recommandés

Remplacer :

```html
Réserver
```

par :

```html
Pré-réserver ma place
```

Conserver ou ajouter pour le B2B :

```html
Organiser une journée entreprise
```

---

## 7. Règle éditoriale

- L'application mobile n'est pas une option future.
- Le paiement sécurisé fait partie du lancement.
- Le lancement ne se fait pas sans le parcours digital.
- Le design actuel reste conservé.
- Les modifications sont principalement textuelles.
