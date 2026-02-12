# PawFriend

**Built by Team PawPatrol in under 48 hours** for CS Girlies’ “Make Learning Cool Again” global hackathon. PawFriend won the **$500 Best GitBook Documentation prize**.

PawFriend is a **multi-language gamified learning app** where you adopt a **magical companion** (fox or puppy) that grows and learns as you study and complete quizzes. Consistency rewards your companion with XP, level progression, and motivational messages.

**Languages:** English, French, Spanish, German, Arabic (with RTL support)

**Winning GitBook:** [https://csgirlies.gitbook.io/pawfriend/pawfriend-guide](https://csgirlies.gitbook.io/pawfriend/pawfriend-guide)
**Devpost project link:** [https://devpost.com/software/pawpatrol-hq6o0j](https://devpost.com/software/pawpatrol-hq6o0j)

## Features

* **Multi-Language Support:** Instant switching, complete translation, context-aware companion messages.
* **Smart Study Sessions:** Pomodoro technique, AI-generated study plans from uploaded documents, progress tracking, XP rewards.
* **AI-Powered Quizzes:** Topic-based multiple-choice quizzes with instant feedback, Wolfram integration for math explanations.
* **Companion System:** Choose fox or puppy, level progression (baby → adolescent → adult), visual evolution, motivational messages.
* **Hydration & Streaks:** Daily streaks to keep companion “hydrated”, personal record tracking.
* **Learning Analytics:** Track study sessions, quiz scores, total study time, and receive performance-based recommendations.
* **Authentication & Profiles:** Supabase integration with persistent profiles.
* **Document Processing:** Upload PDF/DOCX/images, AI generates personalized study plans.
* **Gamification & Rewards:** XP system, achievement tracking, companion care, and in-app economy.

## Tech Stack

* **Frontend:** React + TypeScript, i18next, Supabase client, custom CSS.
* **Backend:** Node.js + Express, Mistral AI for quizzes and study plans, Wolfram Alpha API, AI agents for document ingestion, quiz generation, and study coaching.
* **Database:** Supabase (PostgreSQL) with real-time sync and row-level security.

## Acknowledgments

* **Mistral AI** for open-source LLM
* **Wolfram Alpha** for computations
* **Supabase** for backend services
* **React** for frontend framework
* CSGirlies for hosting the hackathon
