# Fix Vercel 404 Deployment Error

## Problem
Vercel showing: `404: NOT_FOUND - DEPLOYMENT_NOT_FOUND`

## Root Cause
Vercel build likely failed because Firebase environment variables were not set in Vercel Project Settings.

## Solution

### Step 1: Go to Vercel Project Settings
1. Open: https://vercel.com/walmi11/nsnwpyup/settings/environment-variables
2. Login with your Vercel account

### Step 2: Add Environment Variables
Add these 6 variables in Vercel Project Settings:

```
NEXT_PUBLIC_FIREBASE_API_KEY=AIzaSyCzdq81WVpuczl28Rv6EMuZK8bpXHuhj-Q
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=mon-app-cours.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=mon-app-cours
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=mon-app-cours.firebasestorage.app
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=246473751652
NEXT_PUBLIC_FIREBASE_APP_ID=1:246473751652:web:a7b8b465fd6ade31313371
```

### Step 3: Trigger Redeployment
1. Go to: https://vercel.com/walmi11/nsnwpyup/deployments
2. Click on the latest failed deployment
3. Click "Redeploy" button
4. Wait for build to complete (2-3 minutes)

### Step 4: Verify
Once deployment shows green checkmark, visit:
- https://nsnwpyup.vercel.app

The app should now load without 404 error!

## If Still Not Working
1. Check Vercel Build Logs for errors
2. Verify all 6 Firebase variables are in Project Settings
3. Make sure variables are set for Production environment
4. Click "Redeploy" again after adding variables
