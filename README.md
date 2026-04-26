📦 Quotemplified Core

A minimal, reusable SaaS starter template for building AI-powered service business applications.

⚡ Stack
Next.js (App Router)
Supabase (Auth + DB)
Tailwind CSS + shadcn/ui
Lemon Squeezy (Payments)
Resend (Email)
OpenCode Skills (AI workflows)
🚀 Quick Start
git clone https://github.com/YOUR_USERNAME/quotemplified-core.git
cd quotemplified-core
npm install
npm run dev

Open:

http://localhost:3000
📁 Project Structure
quotemplified-core/
│
├── app/                # Pages (Next.js App Router)
│   ├── page.tsx        # Landing page
│   ├── dashboard/      # App dashboard
│   └── auth/           # Login / signup
│
├── components/         # UI components (shadcn/ui)
│
├── lib/                # Core integrations
│   ├── supabase.ts
│   ├── email.ts
│   └── payments.ts
│
├── modules/            # Business logic layer
│   ├── lead-intake/
│   ├── quote-engine/
│   └── follow-up/
│
├── .opencode/          # AI workflow skills
│   └── skills/
│
├── .env.local
└── README.md
🧩 Core Modules
Lead Intake

Handles customer inquiries and lead capture.

Quote Engine

Generates pricing and service estimates.

Follow-up System

Automates reminders and customer engagement.

🔐 Environment Variables

Create .env.local:

NEXT_PUBLIC_SUPABASE_URL=your_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key

RESEND_API_KEY=your_key
LEMONSQUEEZY_API_KEY=your_key
🧱 How to Use This Template
1. Copy the project
cp -r quotemplified-core new-saas-project
cd new-saas-project
2. Reset Git
rm -rf .git
git init
3. Connect new GitHub repo
git remote add origin YOUR_NEW_REPO_URL
🤖 AI Workflow Layer (Optional)
.opencode/skills/

Each skill defines reusable AI behavior such as:

Lead intake logic
Quote generation
Follow-up messaging
🎯 Philosophy

This template is built for:

Fast SaaS creation without rebuilding infrastructure every time.

No bloat. No enterprise complexity. Just reusable core systems.

📌 License

MIT — use freely.

🧠 Why this version is better

Compared to your previous README, this one:

✔ Has:
strong visual hierarchy
quick start at top
clean project tree block
modular sections
minimal reading effort
❌ Removes:
long explanations upfront
repetitive descriptions
“essay-style” formatting
🔥 Pro tip (this is what OSS devs actually do)

The best READMEs follow this order:

1. What is this?
2. How to run it (fast)
3. Structure
4. Features
5. Env setup

Everything else is optional.