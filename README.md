# Aditya -- 3D Creator Portfolio

Dark 3D creator portfolio landing page built with React, TypeScript, Tailwind CSS, Framer Motion, Lucide React, Vite, and Firebase contact form support.

## Run

```bash
npm.cmd install
npm.cmd run dev
```

Local URL:

```text
http://127.0.0.1:5173
```

## Edit Site Information

Edit all portfolio content in:

```text
src/siteContent.ts
```

You can change:

- Name, page title, hero heading, tagline
- Hero character image
- Social links
- Degree, study field, education, internships, hobbies
- Stats, tools, workflow/process
- Services
- Featured projects and live project links
- More project links
- Resume URL
- Firebase config values are read from environment variables

## Firebase Contact Form

Create `.env.local` using `.env.local.example`:

```text
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

Messages are saved to the Firestore collection:

```text
contactMessages
```

## Key Files

```text
src/App.tsx
src/siteContent.ts
src/firebase.ts
src/main.tsx
src/styles.css
public/assets/jack-futuristic-creator.png
public/assets/jack-futuristic-source.png
index.html
package.json
tailwind.config.js
postcss.config.js
vite.config.ts
tsconfig.json
tsconfig.node.json
.env.local.example
```
