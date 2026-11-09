BIKE STOCK UPDATED

1. This is a replacement index.html for your existing Netlify site.
2. IMPORTANT: Copy YOUR EXISTING WORKING firebaseConfig and ADMIN_EMAIL from your deployed/working index.html into this file. The uploaded files still contain PASTE_ placeholders. Do not put passwords into code.
3. Keep the same Firebase project, Authentication and Firestore rules. Existing sold records are recognized by their saleDate.
4. Back up your Firestore records before deployment. Export CSV from the old app if possible.
5. Deploy this folder to the SAME Netlify site using Deploys > Deploy manually. Do not create a new site.
6. Add bikes as stock first; sell later. Sale profit = sale price - purchase - expenses.
7. Photos up to 500KB are stored in Firestore records as data URLs; for many photos, Firebase Storage is recommended instead. CSV backup excludes photos.
8. Test with one bike on two devices before using for real records.
