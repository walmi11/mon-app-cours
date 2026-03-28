# URGENT: Missing Environment Variable (5/6)

## The Problem:
Your Vercel dashboard shows **"Status 5/6"** - you have 5 variables set but **1 is missing**.

---

## SOLUTION - Add the Missing Variable:

### Step 1: Go to Project Settings
1. In Vercel, click your project **"mon-app-cours"**
2. Go to **Settings** tab (top right)
3. Scroll down to **"Environment Variables"**

### Step 2: Check Which One is Missing
Look at your list. You should see all 6:

```
✓ NEXT_PUBLIC_FIREBASE_API_KEY
✓ NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN
✓ NEXT_PUBLIC_FIREBASE_PROJECT_ID
✓ NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET
✓ NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID
? NEXT_PUBLIC_FIREBASE_APP_ID ← LIKELY MISSING
```

### Step 3: Add the Missing One

If `NEXT_PUBLIC_FIREBASE_APP_ID` is missing:

**Name:** `NEXT_PUBLIC_FIREBASE_APP_ID`
**Value:** `1:246473751652:web:a7b8b465fd6ade31313371`

**Then click "Save"**

### Step 4: Redeploy
Once saved:
1. Go to **Deployments**
2. Find the latest failed deployment
3. Click the **... menu** → **Redeploy** (or just push to GitHub)
4. Wait for it to complete ✅

---

## All 6 Variables Reference:
```
NEXT_PUBLIC_FIREBASE_API_KEY = AIzaSyCzdq81WVpuczl28Rv6EMuZK8bpXHuhj-Q
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN = mon-app-cours.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID = mon-app-cours
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET = mon-app-cours.firebasestorage.app
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID = 246473751652
NEXT_PUBLIC_FIREBASE_APP_ID = 1:246473751652:web:a7b8b465fd6ade31313371
```

Check if all 6 are in Vercel Settings!
