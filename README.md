# dm
A public Direct Messaging Boundaries App

DM Boundary Builder 🛡️
A lightweight, client-side static web application designed for everyone: content creators, developers, and online professionals who want to set clear, customizable direct messaging boundaries.
Inspired by classic tools like ⁠no-dm.me⁠, this application runs entirely in the browser with no backend, no database, and no accounts required. All configuration states are encoded directly into the shareable URL using Base64, making it 100% free and easy to host anywhere (such as GitHub Pages).
✨ Features
￼ Editor-First Home Page: The main root acts as an intuitive builder where you can toggle rules, customize profile details, and generate your link instantly.
￼ Structured Categories:
￼ 🌐 Demographics & Age Limits (e.g., 18+, Peers only, Language/Region)
￼ 🎯 Purpose of Outreach (e.g., Friendships, Dating/Flirting ban, Professional/Tech queries, LFG)
￼ 🚫 Content & Media Bans (e.g., NSFW zero-tolerance, Spam/Self-promo ban, Voice message restrictions)
￼ 💬 Communication Etiquette (e.g., "No Hello" rule, Trauma dumping ban, Response times)
￼ 🛡️ Account Requirements (e.g., No empty/egg profiles, Mutual servers/connections)
￼ Custom Rules: Add your own bespoke rules on top of pre-set guidelines.
￼ Zero Backend: Built using pure HTML, JavaScript, and Tailwind CSS.
￼ Short & Shareable URLs: State persistence is handled via URL hash fragments (⁠#⁠), keeping your generated link neat and ready for your Instagram, TikTok, X (Twitter), or Discord bio.
🚀 Quick Start / Local Development
Since this project consists of a single file (⁠index.html⁠), getting it running locally takes seconds:
1 Clone or download this repository.
2 Open the ⁠index.html⁠ file in any modern web browser.
3 Start configuring your DM boundaries and copy your generated bio link!
🌐 Deploying to GitHub Pages (Free Hosting)
You can host your own version of DM Boundary Builder in less than a minute:
1 Create a new public repository on GitHub (e.g., ⁠dm-boundary-builder⁠).
2 Upload the ⁠index.html⁠ file to the root of your repository.
3 Go to your repository's Settings -> Pages.
4 Under Build and deployment, select the ⁠main⁠ branch (or ⁠master⁠) and set the folder to ⁠/ (root)⁠, then click Save.
5 Your app will be live at ⁠https://<your-username>.github.io/<repository-name>/⁠!
📄 License
This project is open-source. Choose a license that fits your goals (such as the MIT License for maximum freedom, or GPLv3 for strict copyleft protection) and add it to your repository as a ⁠LICENSE⁠ file. See the open-source licensing guide in the repository for details.