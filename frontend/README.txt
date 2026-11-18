Voice2Gesture Vercel frontend

This folder is a static copy of the existing Django template frontend, adapted for Vercel.
It preserves the existing HTML/CSS and routes API/media requests through Vercel rewrites to:
https://voice2gesture.onrender.com

In the Vercel project settings:
- Root Directory: frontend
- Framework Preset: Other
- Build Command: leave empty / override disabled
- Output Directory: .
- Install Command: leave empty / override disabled

Deploy from the GitHub repository after adding the frontend/ folder to its root.
