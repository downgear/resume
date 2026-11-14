# Lingriser

**Try it:** https://meowlish-fe.vercel.app (no signup: "Dùng thử bằng tài khoản demo")

**What it does.** IELTS and TOEIC practice focused on accessibility and community, with AI scoring for Speaking and Writing (paused for now). My capstone project, team of 4.

**Why.** Most English study apps are basic exam websites, and studying online means juggling tabs for a dictionary, a translator and more. I wanted one place where learners share their resources and have every tool they need.

**How it helps.** In a mock test you can highlight, live-translate a word, save it as a flashcard, and annotate questions. Flashcard decks can be shared, copied or improved via proposals (like git forks and pull requests), and a review mode makes memorizing fun. Forums and blogs let learners help each other. Badges, streaks and goals keep them motivated.

**My decisions:**
- Feature direction: in-test tools, community-focused features and gamification.
- Database design: learned tree models to fit each feature: closure table for exam structures (IELTS, TOEIC), nested set for tags, materialized path for comment threads; optimistic locking for concurrent edits.
- Architecture under a deadline: kept it simple but scalable, with a database per service, RabbitMQ events, and chat scaled out via Redis pub/sub.

I'm looking for an internship or a fresher position where I can gain more real-world experience and grow my skill set. Thank you for your time.
