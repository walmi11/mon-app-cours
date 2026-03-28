# ✅ ÉTAPES EXACTES - Ajouter les variables dans Vercel

Tu vois le menu Vercel. Voici exactement quoi faire:

## ÉTAPE 1: Clique "Environment Variables"

Dans le menu de gauche, tu vois:
```
Settings
General
Build and Deployment
Environments
Environment Variables  ← CLIQUE ICI
Git
...
```

---

## ÉTAPE 2: Tu devrais voir une page avec:
- Un bouton **"+ Add New"** (bleu, en haut)
- Peut-être une liste vide ou quelques variables existantes

---

## ÉTAPE 3: Clique "+ Add New"

Un formulaire va apparaître avec deux champs:
- **Key** (le nom)
- **Value** (la valeur)

---

## ÉTAPE 4: Ajoute chaque variable (6 fois)

### Variable 1:
- **Key:** `NEXT_PUBLIC_FIREBASE_API_KEY`
- **Value:** `AIzaSyCzdq81WVpuczl28Rv6EMuZK8bpXHuhj-Q`
- Clique "Save"

### Variable 2:
- **Key:** `NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN`
- **Value:** `mon-app-cours.firebaseapp.com`
- Clique "Save"

### Variable 3:
- **Key:** `NEXT_PUBLIC_FIREBASE_PROJECT_ID`
- **Value:** `mon-app-cours`
- Clique "Save"

### Variable 4:
- **Key:** `NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET`
- **Value:** `mon-app-cours.firebasestorage.app`
- Clique "Save"

### Variable 5:
- **Key:** `NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID`
- **Value:** `246473751652`
- Clique "Save"

### Variable 6:
- **Key:** `NEXT_PUBLIC_FIREBASE_APP_ID`
- **Value:** `1:246473751652:web:a7b8b465fd6ade31313371`
- Clique "Save"

---

## ÉTAPE 5: Redéploie

Va ici: https://vercel.com/walmi11/nsnwpyup/deployments

Clique sur le dernier déploiement → Clique "Redeploy"

Attends 2-3 minutes (spinner bleu).

Quand c'est vert ✅, visite: https://nsnwpyup.vercel.app

---

## 🚨 Problèmes courants:

**"Je ne vois pas le bouton + Add New"**
→ Refresh la page (Ctrl+R)

**"Où je colle le nom et la valeur?"**
→ Dans les champs du formulaire (Key = nom, Value = valeur)

**"Faut cocher Production?"**
→ Généralement c'est automatique. Si tu vois un dropdown, sélectionne "Production"

---

**Dis-moi quand tu as ajouté la PREMIÈRE variable!** ✅
