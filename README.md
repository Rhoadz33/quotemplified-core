📦 Quotemplified Core

A minimal, reusable MicroSaaS starter template for building AI-powered service business applications.
This template is designed to help you stop rebuilding the same infrastructure every time and instead focus on building real product logic faster.

🚀 What this is

quotemplified-core is a production-ready SaaS foundation that includes only the essential building blocks needed for modern MicroSaaS apps:

Authentication
Database layer
Payments
Email system
UI system
AI workflow modules (optional)

It is intentionally minimal, modular, and reusable.

🧠 Philosophy

This template follows a simple rule:

Only include what you will reuse across every SaaS project.
No unnecessary dashboards.
No bloated enterprise features.
No over-engineering.
Just the core system you actually need.

⚙️ Tech Stack

Frontend: Next.js (App Router)
UI: shadcn/ui + Tailwind CSS
Auth & DB: Supabase
Payments: Lemon Squeezy
Email: Resend
AI Workflow Layer: OpenCode Skills (optional structure)


📁 Project Structure

quotemplified-core/
│
├── app/                  # Next.js routes (landing, dashboard, auth)
├── components/          # UI components (shadcn/ui)
├── lib/                 # Core integrations (Supabase, email, payments)
├── modules/             # Business logic (AI workflows)
│   ├── lead-intake/
│   ├── quote-engine/
│   └── follow-up/
│
├── .opencode/           # AI skills (workflow definitions)
├── .env.local           # Environment variables
└── README.md
🧩 Core Modules

This template includes optional business modules:

🟢 Lead Intake

Collects and structures customer inquiries.

🟡 Quote Engine

Generates service estimates and pricing logic.

🔵 Follow-up System

Handles reminders, email sequences, and customer engagement.

These are designed to be reusable across all service-based SaaS apps.

🔐 Environment Setup

Create a .env.local file:

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
RESEND_API_KEY=your_resend_key
LEMONSQUEEZY_API_KEY=your_lemonsqueezy_key

🧪 Getting Started

1. Install dependencies
npm install

2. Run development server
npm run dev

3. Open in browser
http://localhost:3000
🧱 Usage Workflow

This template is meant to be reused:

Step 1
Copy the repo:
cp -r quotemplified-core new-saas-project

Step 2
Rename and customize

Step 3
Connect new Supabase + payments + email

Step 4
Build your SaaS on top of the base system

🤖 AI Workflow Layer (Optional)

This template supports AI workflow definitions via:

.opencode/skills/

Each skill represents a reusable AI behavior such as:

Lead intake
Customer classification
Quote generation
Follow-up messaging

This enables future integration with AI agents and automation tools.

🎯 Ideal Use Cases

This template is best suited for:

AI receptionist systems
Service business SaaS tools
Lead generation platforms
Appointment-based businesses
Internal automation tools

⚠️ Important Notes
This is a starter template, not a full SaaS product
Keep it minimal and extend only when needed
Each new project should be a fresh copy of this base

🔄 Vision

This project is designed to evolve into a personal SaaS foundation system:

“Build once. Reuse forever.”

Over time, it becomes the core engine behind all MicroSaaS products.

📌 License

MIT License — free to use, modify, and distribute.

👤 Author

Built as a personal SaaS foundation system for rapid MicroSaaS development and AI workflow automation.
