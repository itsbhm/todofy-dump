## **Setup Instructions**

### **Step 1: Obtain Convex Credentials**

1. Run the following command to get Convex credentials:
   ```bash
   npx convex dev
   ```

2. Store the output in your `.env` file:
   ```bash
   CONVEX_DEPLOYMENT=dev:XXXX-XXXX-XXXX
   NEXT_PUBLIC_CONVEX_URL=https://XXXX-XXXXX-XXXX.convex.cloud
   ```

### **Step 2: Obtain Auth Secret**

1. Run the following command to get the auth secret:
   ```bash
   npx auth secret
   ```

2. Store the output in your `.env` file:
   ```bash
   AUTH_SECRET="XXXX-XXXX-XXXX"
   ```

### **Step 3: Obtain Google OAuth Credentials**

1. Go to [Google API Console](https://console.developers.google.com/) and create a project.
2. Enable OAuth 2.0 credentials.
3. Store the OAuth credentials in your `.env` file:
   ```bash
   AUTH_GOOGLE_ID=XXXX-XXXX.apps.googleusercontent.com
   AUTH_GOOGLE_SECRET=XXXX-XXXX-XXXX
   ```

### **Step 4: Run the App**

1. To run your Next.js app:
   ```bash
   npm run dev
   ```

2. To run Convex service:
   ```bash
   npx convex dev
   ```

--- 

Just make sure to replace the `XXXX` placeholders with your actual values.