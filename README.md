# 🇮🇳 Sarkari Yojana Sahayak

**AWS x WeMakeDevs — First Commit Hackathon | Build It Track**
**Team:** Alpha (Team Code: GGFH47)
**Members:** Arjun Mishra (Leader), Karunanidhi Tiwari, Rohan Pandey

---

## 🧩 Problem Statement

India has hundreds of government welfare schemes — for farmers, widows, students, senior citizens, and more — but most people don't know which schemes they're actually eligible for. Information is scattered across dozens of government websites, often in English or complicated legal language, and application processes are unclear.

We wanted to solve a real, everyday problem: **helping ordinary people discover the government schemes they're eligible for, explained simply, in Hindi.**

## 💡 Our Solution

**Sarkari Yojana Sahayak** is an AI-powered app where a user enters basic details — age, occupation, annual income, state, and any additional context (like widowhood, disability, etc.) — and instantly receives:

- A list of **Central and State government schemes** they may be eligible for
- Plain-language explanations of what each scheme offers, in **Hindi**
- Step-by-step application guidance (where to go, what documents are needed, official portal links)
- A **WhatsApp-ready shareable summary message**, so users can copy-paste and forward the information directly to family members — because in India, that's how information actually spreads.

The app doesn't just list schemes randomly — it reasons through eligibility. For example, when tested with a 60-year-old widow, it correctly recognized that Atal Pension Yojana (age 18–40 only) didn't apply, and instead suggested the Senior Citizen Savings Scheme.

## 🛠️ Built On

- **AWS PartyRock** — a no-code AI app builder, part of AWS's open-source AI tooling (listed under the Build It track's "Agents and AI" category)
- Prompt-engineered AI instructions to generate structured, personalized, Hindi-language output

## ✅ Track

**Build It** — built entirely on PartyRock, no AWS account, card, or bill required.

## 🔗 Links

- **Live App (PartyRock):** https://partyrock.aws/u/Arjun18/X0El0odQz/Sarkari-Yojna-Sahaayak
- **Demo Video (3 min):** https://youtu.be/SriGjjqZWb0

> Note: To interact with the app yourself, PartyRock requires a free sign-in (via Amazon account, ~30 seconds) — this is standard for all PartyRock apps and not specific to ours. The demo video shows the full working output without needing to sign in.

## 🧪 Tested Scenarios

| Persona | Age | State | Key Result |
|---|---|---|---|
| Farmer | 24 | Bihar | PM-KISAN, PMFBY, KCC, Bihar Fasal Sahayata |
| Widow | 59–60 | Bihar | Widow Pension, PMAY-G, correctly excluded Atal Pension Yojana on age grounds and suggested SCSS instead |
| BTech Student | 18–19 | UP | PM Scholarship, Skill India, Startup India Seed Fund |

## 📚 What We Learned

This was our team's first time working with AI prompt engineering and PartyRock. We learned how to design multi-field input flows, structure prompts so AI reasons through eligibility logic instead of just listing information, and think about real-world usability (like the WhatsApp-sharing feature) rather than just building a technically working app.

## 📸 Screenshots

[Add screenshots here]

---

*Built with ❤️ for the AWS x WeMakeDevs Bharat Builds Tour — First Commit Hackathon, September 2026.*
