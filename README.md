# final-learning-deploy
Key Features:
- 🌐 Next.js 14 & server actions
- 🗣 AI Voices using Elevenlabs AI
- 🎨 Beautiful component system using Shadcn UI
- 🎭 Used KenneyNL Amazing characters
- 🔐 Authentication using Clerk
- 🔊 Sound effects
- ❤️ Hearts system
- 🌟 Points / XP system
- 💔 No hearts left popup
- 🚪 Exit confirmation popup
- 🔄 Practice old lessons to regain hearts
- 🏆 Leaderboard
- 🗺 Quests milestones
- 🛍 Shop system to exchange points with hearts
- 💳 Pro tier for unlimited hearts using Stripe
- 🏠 Landing page
- 📊 Admin dashboard React Admin
- 🌧 ORM - DrizzleORM
- 💾 PostgresDB using NeonDB
- 🚀 Deployment on Vercel
- 📱 Mobile responsiveness
# folder-structure
final deploy
  |- actions/
    |- challenge-progress.ts
    |- user-progress.ts
    |- user-subscription.ts
  |- app/
    |-- (main)/
        |--- courses/
        |--- leaderboard/
        |--- learn/
        |--- quests/
        |--- shop/
        |--- layout.tsx
    |-- (marketing)/
        |--- footer.tsx
        |--- header.tsx
        |--- layout.tsx
        |--- page.tsx
    |-- admin/
        |--- challenge/
        |--- challengeOption/
        |--- course/
        |--- lesson/
        |--- unit/
        |--- app.tsx
        |--- page.tsx
    |-- api/
        |--- challengeOptions/
        |--- challenges/
        |--- courses/
        |--- lessons/
        |--- units/
        |--- webhooks/stripe/
    |-- lesson/
        |--- [lessonId]/
        |--- card.tsx
        |--- challenge.tsx
        |--- footer.tsx
        |--- header.tsx
        |--- layout.tsx
        |--- page.tsx
        |--- question-bubble.tsx
        |--- quiz.tsx
        |--- result-card.tsx
    |-- favicon.ico
    |-- globals.css
    |-- layout.tsx
  |- components/
    |-- modals/
    |-- ui/
    |-- feed-wrapper.tsx
    |-- mobile-wrapper.tsx
    |-- mobile-sidebar.tsx
    |-- promo.tsx
    |-- quests.tsx
    |-- sidebar-item.tsx
    |-- sidebar.tsx
    |-- sticky-wrapper.tsx
    |-- user-progress.tsx
  |- db/
    |-- drizzle.ts
    |-- queries.ts
    |-- schema.ts
  |- lib/
    |-- admin.ts
    |-- stripe.ts
    |-- utils.ts
  |- public/
  |- scripts/
    |-- prod.ts
    |-- reset.ts
    |-- seed.ts
  |- store/
    |-- use-exit-modal.ts
    |-- use-hearts-modal.ts
    |-- use-practice-modal.ts
  |- .env
  |- .env.example
  |- .eslintrc.js
  |- .gitignore
  |- .prettierrc.json
  |- components.json
  |- constants.ts
  |- drizzle.config.ts
  |- environment.d.ts
  |- middleware.ts
  |- next.config.mjs
  |- package-lock.json
  |- package.json
  |- postcss.config.js
  |- tailwind.config.ts
  |- tsconfig.json

# majorproject
