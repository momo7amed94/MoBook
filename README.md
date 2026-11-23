# MoBook

### يُسمع الإنسان قبل أن يُعرَف

**Trust first. Identity by choice.**

MoBook is a concept for a human-first social space where ideas, feelings and lived experience come before names and profile pictures. People meet as anonymous "voices", build trust through real conversation, then choose what they want to share about themselves.

> محدّش يعرف عنك حاجة... إلا لو سمحت بنفسك.

**Status:** In progress · Concept and design stage  
**Planned stack:** Flutter + Firebase  
**This repository:** Product documents, visual identity and HTML prototypes. The Flutter app and Firebase backend have not been implemented here.

---

## The idea

Most social platforms introduce the person before the conversation. MoBook reverses that order: listen first, build trust, then let each person decide whether to reveal more.

The public experience is built around anonymous voice IDs such as **صوت #123**, not personal profiles, follower counts or popularity. Short posts, full articles and audio are part of the concept. Photos and videos are not public-feed content.

The design calls for email-only registration, no location tracking, and no access to contacts or phone files. These are product requirements, not claims about a live service.

## Three spaces, one journey

| Space | Purpose | What makes it different |
| --- | --- | --- |
| 🏛️ **المدينة الفاضلة** | One shared public feed | Everyone participates as an equal voice. Comments become public only after the post author approves them. |
| 🔗 **الاقتران** | A private connection between two voices | Mutual posts, comments and comment approvals make a connection eligible. Both people must agree to connect. |
| 🌍 **يوتوبيا** | A private group of three or more voices | Prior interaction and unanimous agreement are required. Adding or removing a member also requires everyone's agreement. |

### Four levels of trust

Within a two-person connection, each person independently controls what they disclose:

1. **اهتمامات وأفكار عامة**: General interests and simple personal thoughts.
2. **تجارب وقصص أعمق**: Deeper stories and lived experience.
3. **محادثة مباشرة**: Direct text and voice conversation.
4. **كشف الهوية**: Optional disclosure of real identity.

No level opens automatically. Disclosure is voluntary and can be withdrawn. Connecting with someone does not automatically reveal personal information.

## Explore the project

- [Final concept, Arabic PDF](docs/MoBoOk_Final_Concept.pdf): The canonical product vision.
- [Application site map, Arabic Markdown](docs/MoBoOk_SiteMap.md): Proposed screens, navigation and user flows.
- [Policy draft, Arabic Markdown](docs/MoBoOk_Policies.md): Early terms, privacy and community guidelines.
- [Visual identity](design/MoBoOk_VisualIdentity.html): The design language across the three spaces.
- [Final screen mockup](design/mobook_mockup_final.html): A visual walkthrough of the core experience.
- [Latest supplied HTML preview](design/previews/MoBoOk-Preview-2.html): A local browser prototype, not the production app.
- [Earlier iterations and alternate exports](archive/README.md): The project's design history, preserved rather than discarded.

The Arabic source documents and prototypes retain their original language and content. Where documents disagree, the **final concept** takes precedence. See [documentation notes](docs/README.md) for decisions still to be reconciled.

## Try the HTML preview

1. Download or clone this repository.
2. Open `design/previews/MoBoOk-Preview-2.html` in a modern browser.
3. Use sample content to explore the proposed experience.

The preview stores demo data locally in your browser and has no production backend. Its demo login stores the entered password in plain text in browser storage. Use a made-up password that you do not use anywhere else. It is not a secure messaging service. Do not enter real personal or sensitive information. Internet access may be needed for the Google Fonts used by the supplied HTML designs.

## Repository map

```text
MoBook/
├── README.md
├── docs/
│   ├── README.md
│   ├── MoBoOk_Final_Concept.pdf
│   ├── MoBoOk_SiteMap.md
│   └── MoBoOk_Policies.md
├── design/
│   ├── MoBoOk_VisualIdentity.html
│   ├── mobook_mockup_final.html
│   └── previews/
│       └── MoBoOk-Preview-2.html
└── archive/
    ├── README.md
    ├── concepts/
    ├── exports/
    ├── mockups/
    └── previews/
```

## Next steps

- [ ] Reconcile the site map and policy draft with the final concept.
- [ ] Finalize reporting, blocking, deletion and sensitive-content rules.
- [ ] Define Firestore data models for voices, connections, consent and groups.
- [ ] Design an access-control model that separates account identity from public voice IDs.
- [ ] Validate the screen flows and accessibility.
- [ ] Begin the Flutter app and Firebase implementation.

Security, encryption, moderation response times and legal terms need design, implementation and review before launch. None should be treated as a shipped guarantee.

---

A project by **Mohamed Hassan**. Built around a simple question: **ماذا يقول؟**, before **من يتحدث؟**
