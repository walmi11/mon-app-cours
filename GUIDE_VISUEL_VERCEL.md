# ✅ Guide Visuel: Fixer le 404 sur Vercel

## 📍 Tu es ici: Page 404 sur https://nsnwpyup.vercel.app

C'est parce que les variables Firebase ne sont pas dans Vercel. Pas de panique! C'est facile à fixer.

---

## 🎯 Plan en 4 étapes (10 minutes)

### ✅ ÉTAPE 1: Ouvrir les settings de Vercel
**Clique sur ce lien:**
```
https://vercel.com/walmi11/nsnwpyup/settings/environment-variables
```

**Tu devrais voir:**
- Un formulaire avec "Key" et "Value"
- Un bouton "+ Add New" ou "Add..."
- Peut-être une liste vide ou quelques variables existantes

**✓ Checkpoint:** Je vois la page des variables

---

### ✅ ÉTAPE 2: Ajouter les 6 variables une par une

**Clique "+ Add New"** pour chaque variable:

#### Variable #1
- **Key:** `NEXT_PUBLIC_FIREBASE_API_KEY`
- **Value:** `AIzaSyCzdq81WVpuczl28Rv6EMuZK8bpXHuhj-Q`
- Clique "Save"

#### Variable #2
- **Key:** `NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN`
- **Value:** `mon-app-cours.firebaseapp.com`
- Clique "Save"

#### Variable #3
- **Key:** `NEXT_PUBLIC_FIREBASE_PROJECT_ID`
- **Value:** `mon-app-cours`
- Clique "Save"

#### Variable #4
- **Key:** `NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET`
- **Value:** `mon-app-cours.firebasestorage.app`
- Clique "Save"

#### Variable #5
- **Key:** `NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID`
- **Value:** `246473751652`
- Clique "Save"

#### Variable #6
- **Key:** `NEXT_PUBLIC_FIREBASE_APP_ID`
- **Value:** `1:246473751652:web:a7b8b465fd6ade31313371`
- Clique "Save"

**✓ Checkpoint:** J'ai vu 6 variables dans la liste

---

### ✅ ÉTAPE 3: Redéployer

**Va ici:**
```
https://vercel.com/walmi11/nsnwpyup/deployments
```

**Tu devrais voir:**
- Une liste de déploiements
- Le dernier avec un ❌ rouge (FAILED)

**Clique dessus** pour l'ouvrir, puis:
- Cherche le bouton **"Redeploy"**
- Clique sur "Redeploy"

**Tu verras:**
- La page rechargera
- Le build va recommencer
- Ça prendra 2-3 minutes

**✓ Checkpoint:** J'ai cliqué "Redeploy" et le build a recommencé

---

### ✅ ÉTAPE 4: Attendre et tester

**Attends que le déploiement devienne VERT ✅**

Une fois que tu vois un ✅ vert à côté du déploiement:

**Visite ton app:**
```
https://nsnwpyup.vercel.app
```

**Tu devrais voir:**
- La page d'accueil (pas 404!)
- Peut-être un formulaire de connexion
- Tes cours affichés

**✓ Checkpoint:** J'ai une page vraie! Pas 404!

---

## 🚨 Si tu es bloqué

### Problème: Je ne vois pas le bouton "+ Add New"
→ Réessaye de charger la page

### Problème: J'ai ajouté les variables mais ça dit "Production" ou "Preview"
→ S'assure que "Production" est coché ✓

### Problème: Le redéploiement échoue encore
→ Va dans "Logs" et copie l'erreur, envoie-la moi

### Problème: Ça affiche toujours 404
→ Fais Ctrl+Shift+Del pour vider le cache et actualise

---

## ⏱️ Temps estimé
- Ajouter 6 variables: 5 minutes
- Redéploiement: 2-3 minutes
- **TOTAL: 10 minutes max!**

---

**Dis-moi quand tu as fini! 🎉**
