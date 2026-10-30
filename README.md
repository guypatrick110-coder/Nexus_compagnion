🌿 Nexus Vie

> **Un havre de paix numérique dans ta poche.** Un compagnon de bien-être intime, humain et sans fioritures artificielles, conçu pour t'aider à respirer, t'organiser et prendre soin de ta santé mentale au quotidien.

---

## La Philosophie du Projet
Nexus Vie n'a pas été créé dans les bureaux froids de la Silicon Valley, mais avec le cœur, la rage de réussir et une connexion internet depuis une chambre d'étudiant. 

Ici, on oublie les dégradés agressifs de l'IA et les notifications stressantes. L'application adopte une approche **"Soft Tech"** : des couleurs unies inspirées de la terre (Sable, Vert Sauge, Terracotta), des angles doux et une interface épurée qui respecte ton attention et ton énergie.

---

## 🛠️ L'Architecture Technique
L'application est construite sur des fondations solides, modernes et ultra-rapides :
* **Frontend** : React + TypeScript + Vite (Interface fluide et légère)
* **Mise en page & Design** : Tailwind CSS + Framer Motion (Animations tactiles organiques)
* **Routage & State** : TanStack Router + TanStack Query (Gestion d'état asynchrone d'élite)
* **Backend & Base de données** : Supabase (Authentification sécurisée et tables relationnelles)
* **Intelligence Artificielle** : Supabase Edge Functions (Génération de conseils quotidiens sur-mesure)

---

## Fonctionnalités Clés
* **Mood Tracker Tactile** : Note ton humeur en un geste grâce à des boutons élastiques satisfaisants et un fond d'écran dynamique qui s'adapte à tes émotions.
* **Bento Dashboard** : Une vue d'ensemble claire sous forme de blocs comprenant ton plan de journée personnalisé, ton calendrier et le suivi de tes objectifs.
* **Compagnon IA Intime** : Un espace d'échange sécurisé avec ton avatar pour libérer ta charge mentale.
* **Conseil du Jour Viral** : Un boost de sagesse quotidienne personnalisée par l'IA, partageable sur tes statuts WhatsApp en un clic pour inspirer tes proches.

---

## Le Rythme de Développement (Mode "Anti-Burnout")
Parce qu'on ne bâtit pas un empire en détruisant sa propre santé ou ses études, ce projet avance selon une règle d'or : **Le calme et la régularité.**

* 📚 **Priorité n°1** : L'école, la famille et la vraie vie.
* ⏳ **Régularité > Vitesse** : 30 minutes de code tranquille par jour ou une seule session le week-end suffisent amplement. 
* 🤝 **Distribution Humaine** : Pas de budget publicitaire. L'application grandit grâce au bouche-à-oreille, au partage de conseils utiles sur WhatsApp et au soutien de notre communauté.

---

## Installation locale

1. **Cloner le projet** :
   ```bash
   git clone https://github.com/ton-username/nexus-vie.git
   cd nexus-vie
   ```

2. **Installer les dépendances** :
   ```bash
   npm install
   ```

3. **Lancer le serveur de développement** :
   ```bash
   npm run dev
   ```

## Déploiement sur Vercel

1. **Via l'interface Vercel (Recommandé) :**
   - Connectez votre dépôt GitHub sur [Vercel](https://vercel.com/new).
   - Vercel détecte automatiquement le framework **TanStack Start**.
   - Configurez les variables d'environnement listées dans `.env.example` :
     - `VITE_SUPABASE_URL`
     - `VITE_SUPABASE_PUBLISHABLE_KEY`
     - `VITE_SUPABASE_PROJECT_ID`
     - `SUPABASE_URL`
     - `SUPABASE_SERVICE_ROLE_KEY`
     - `ONESIGNAL_REST_API_KEY`
     - `AI_API_KEY`
     - `APP_URL`
   - Cliquez sur **Deploy**.

2. **Via le CLI Vercel :**
   ```bash
   npx vercel
   ```

---

*Fait avec passion pour un web plus humain.* 🕊️
