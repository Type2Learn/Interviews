# Type2Learn

Type2Learn is an accessibility-first learning platform built around a simple idea: students should be able to learn through the conditions, tools, and pace that help them think best.

This repository contains the interview evidence behind that idea. It includes **13 interview scripts from 9 interviewees**, student pre-product interviews, student product reviews, professor interviews, a professional interview, source recordings, and analytics snapshots from the live Type2Learn site.

The interviews are not being treated as decoration or as a collection of generic testimonials. They are the research record behind product decisions: what learners struggle with, what teachers see every day, what professionals caution us about, what participants liked, and where the product still needs work.

## What the research taught us

### Students before the product

| Participant | What we learned | Product implication |
| --- | --- | --- |
| **Hiba** — student, under 18 | Long lectures make sustained focus difficult. Competition can motivate her to finish work and prepare well. Lofi works better for her than white noise, and heavy animations feel childish. | Keep focus support optional, avoid assuming that one sound or visual style works for everyone, and make encouragement age-appropriate. Her transcript also records consent for clips with face blurring and a future interview. |
| **Maheen** — student with reading difficulties | She mixes up letters such as **b/d** and **i/l**, reads slowly, and struggles with pronunciation. Audiobooks, white noise, visuals, and a dyslexic-friendly font help; typing can help but can also reproduce the same letter confusion. | Support dyslexic fonts, audio, visual alternatives, manageable text, and typing without presenting typing as a universal solution. |
| **Tooba** — student | She usually prefers typing, but needs people to pause when she gets stuck. Speaking in unfamiliar settings can cause nervousness and shaking. She studies with notes, LLM-generated flashcards, and quiz questions; silence and restrained visuals work better than background noise or heavy animation. | Make pacing humane, keep the interface calm and controllable, and use active recall and generated practice without forcing a single response mode. Offline access matters because connectivity is unreliable. |
| **Hassaan** — student | Distractions make reading harder, and smaller chapters are much better than one large block. White noise, animated elements, and a constantly active mascot divert his attention. He prefers straightforward quizzes, progress visibility, and identifying specific mistakes. | Break content into smaller units, make motion and mascot behavior opt-in, and make assessment feedback specific rather than merely pass/fail. |
| **Arham** — student | Procrastination and last-minute study increase academic pressure. He uses YouTube and GPT for preparation and believes repeated typing helps information stay in memory. Pink noise works better for him than white noise. He prefers a mascot to be quiet during study, but appreciates a clear “well done” after success. | Combine active recall with repetition, allow sound preferences, separate learning focus from celebration, and test the MVP with real students before scaling it. |

### What the product reviews reassured us about

The product reviews provide a second layer of evidence: not only what students say they need in theory, but what they noticed while using Type2Learn.

- **Hiba** found the landing page well organized, liked the fonts, labelled navigation, language option, colored information boxes, and the overall idea of tailored typing. She suggested adding visual or interactive activities beyond typing.
- **Maheen** liked the landing page, palette and language controls, guest mode, course settings, text-to-speech, and the typing activity. She described the experience as comfortable and said she would use it for studying.
- **Tooba** liked the minimalist theme, customization controls, and typing flow. Her main concerns were repeated scrolling and whether the platform would work offline.
- **Hassaan** said the overall system, UI, text, and color scheme were well made. He also identified concrete fixes: repair the repeating text-to-speech behavior, add dark mode, prevent background scrolling behind login, reduce distracting animation, reconsider the placement of the AI button, and preserve both guest and account-based access.

The reassurance is valuable precisely because it is not blind praise. The interface, customization, and typing direction repeatedly received positive reactions, while the criticisms point directly to the next engineering priorities.

## Additional visual product reviews

The [`revies/`](./revies/README.md) folder preserves **32 additional review screenshots from 31 reviewers**: Ali Rehman, Muhammad Taha, Huzaifa Sharif, Sami, Muhammad Zubair, Maheen Ateeq, Muhammad Ali Imran, Miray Fatima, Minahil Fatima, Muhammad Mahd, Taimoor, Ahmad, Areeba Naeem, Bilal Nadeem, Fawad, Saad, Abdur Rehman, Abubakar, Hassan Mehboob, Reyan, Muneeb, Obaida Nadeem, Omair, Rehan, Talha Aziz, Jiya, Faryal Fatima, Maryam, Hamza Zia, Zoha Hussayn, and Ahmed.

Together, these reviewers reinforce that Type2Learn is clean, simple, student-friendly, useful for typing practice, and meaningful for learners with different needs. They also give us actionable priorities: explain the neurodivergent value more clearly, improve navigation and course discoverability, add more courses and a team group photo, improve mobile autofill and unrealistic WPM readings, reduce landing-page and mascot loading delays, clarify certificates, improve line wrapping during typing, modernize visual detailing and graphics, refine buttons, dashboards, and page transitions, add dark mode, and continue collecting feedback directly from neurodivergent users.

One review is especially important for learning-design validation. Muhammad Zubair reported that the typing activity made him concentrate on capitalization, punctuation, and error correction instead of understanding the lesson, leaving him with very little recall. This supports a comprehension-first design in which typing is optional or adaptable and assessment can use multiple response modes.

## What educators and professionals taught us

### Ma’am Myeda — psychology professional

Ma’am Myeda emphasized that neurodivergence is often invisible, varied, and strongly affected by sensory experience, environment, attention, rigidity, and nervous-system regulation. A child may be overloaded rather than simply angry; a behavior that looks disruptive may be an attempt to self-regulate; and no single strategy can serve every learner.

The product lessons are clear:

- Do not confuse a learning preference with a diagnosis or pretend that the platform can diagnose users.
- Avoid overwhelming learners with too much information, motion, brightness, or speed.
- Let learners use short chunks, flashcards, sliders, quiet, natural sounds, or other regulating supports according to their own needs.
- Treat typing as a meaningful communication and learning mode; some nonspeaking people communicate through typing.
- Build support around the individual rather than forcing every learner through one “normal” path.

She also allowed her official contact details to be listed for referrals, while clarifying that she is not available for clinical screening through the platform. That distinction is an important boundary for Type2Learn.

### Ma’am Qurat — IT lecturer and education researcher

Ma’am Qurat described recurring classroom problems: rote memorization, weak practical application, difficulty following instructions, poor concentration, low participation, and unequal access to devices and reliable internet.

She reassured the project in several concrete ways. She permitted the team to cite her dyslexia-related research, offered to refer other teachers after obtaining their consent, welcomed future research collaboration, and encouraged the team’s mission.

Her teaching practice gives Type2Learn a practical design direction:

- Start with brainstorming and students’ existing ideas instead of one-way lectures.
- Use group discussion, practical demonstrations, multimedia, and self-research.
- Stop and change approach when students are not responding.
- Establish foundations before moving to advanced material.
- Use low-pressure quizzes, participation incentives, and recognition of effort.
- For dyslexia, consider clear fonts, repeated display, audio or audiobooks, and short manageable chunks.
- Design for the digital divide: many students lack computers, privacy, stable internet, or suitable classroom technology.

### Ayesha Shah Muhammad — social sciences lecturer

Ayesha identified attention loss as a recurring problem, especially when students are not invited to participate. She recommended simple wording, everyday examples, clear instructions, small linked portions, pauses after each portion, discussion, and multiple teaching techniques.

She described step-by-step assessment: check whether students understand the previous point before moving forward, then use another delivery method when they do not. Understanding can be demonstrated through discussion, debate, verbal responses, written work, and presentations—not only through written exams.

For abstract topics, she found videos, images, and multimedia more engaging than lecture-only delivery. She also stressed that flexible course content and properly equipped classrooms require institutional support. Her online-learning experience was negative because of weak internet and low seriousness at undergraduate level, and she advised Type2Learn to keep consulting teachers with different methodologies. She was open about her limited availability for a second questionnaire, so her interview is treated as expert guidance rather than a product endorsement.

### Dr. Asjad — Biological Sciences academician, Virtual University

Dr. Asjad reported that students often memorize biological facts without understanding concepts, lack foundational knowledge, and struggle to apply theory to experiments or case-based problems.

He identified the following interventions as effective:

- Laboratory demonstrations
- Case studies
- Visual models
- Practical-based and case-based assessments
- Additional visual aids
- Simplified explanations
- Extra practice sessions
- Virtual laboratories, interactive sessions, and formative assessment for online learning

He also highlighted large classes, limited laboratory time, limited resources, and the loss of hands-on interaction in online classes. Most importantly for future validation, he explicitly agreed to participate in a second interview and assess whether Type2Learn addresses these challenges.

## The shared design principles

Across learners, educators, and professionals, the interviews repeatedly support these principles:

1. **Choice beats assumptions.** White noise helps some people, pink noise helps others, lofi helps others, and silence is best for some. The same is true of animation, mascots, colors, reading, speaking, and typing.
2. **Short, connected steps beat overwhelming blocks.** Break chapters, explanations, instructions, and tests into manageable units without losing the link between ideas.
3. **Active learning beats passive exposure.** Typing, questions, discussion, flashcards, case studies, practical examples, and explanation in the learner’s own words are recurring needs.
4. **Feedback should be useful and humane.** Students want encouragement, but not constant distraction. When possible, feedback should show what was understood and what needs attention.
5. **Accessibility must be configurable.** Dyslexic-friendly typography, text-to-speech, synchronized reading support, visual alternatives, contrast, language options, sound choices, motion controls, and offline capability should be treated as user-controlled tools.
6. **Privacy must be a first-class feature.** Guest mode matters, but users should understand the tradeoff between anonymity and saved progress. Consent, face blurring, clip permissions, and careful handling of minors are non-negotiable.
7. **The platform must work in the real world.** Unreliable internet, limited devices, large classes, limited lab time, noisy homes, and lack of privacy are not edge cases for the communities being served.
8. **Disagreement is evidence, not a problem to hide.** The research is strongest when one learner finds animation motivating and another finds it disruptive. Type2Learn should respond with personalization, not a single universal default.

## Evidence of reach and momentum

The repository also preserves [the full analytics evidence pack](./proves/README.md) and both original dashboard PDFs. The headline figures are:

### Google Analytics Reports Snapshot

Window: **12 July–8 August 2026**, labelled as the last 28 days.

- **8.3K active users**
- **8.3K new users**
- **1 minute 40 seconds average engagement time per active user**
- **23K page views**
- **12K user-engagement events**
- **11K session starts**
- **8.3K first visits**
- Active users shown from Pakistan, the United States, India, the United Kingdom, the United Arab Emirates, Russia, and Afghanistan

### Cloudflare HTTP Traffic snapshot

Captured **9 August 2026 at 16:27**.

- **2.07K total unique visitors** in the previous 30 days
- **242 maximum unique visitors in one day** during the displayed period
- **31,843 SSL requests served**
- **398 MB saved** through Cloudflare in the last month
- **70 attacks blocked**
- Visible previous-24-hour request counts included **4,786 from Pakistan**, **552 from Lithuania**, **271 from the United States**, **158 from the Netherlands**, and **112 from China**

These numbers show measurable early reach, international visibility, product interaction, and a live site handling real traffic. They must not be added together as a single unique-user total: Google Analytics and Cloudflare measure different things across different windows. The accurate claim is that two independent systems recorded substantial activity around Type2Learn.

## Interview source index

### Student pre-product interviews

- [Hiba — under 18](./Students/Pre-Product/Female-1-Under-18/Female_1_Interview_Under18.md)
- [Maheen](./Students/Pre-Product/Female-2/Female_2_interview.md)
- [Tooba](./Students/Pre-Product/Female-3/Female_3_interview.md)
- [Hassaan](./Students/Pre-Product/Male-1/Male_1_Interview.md)
- [Arham](./Students/Pre-Product/Male-2/Male_2_Interview.md)

### Student product reviews

- [Hiba — under 18](./Students/Product-Review/Female-1-Under-18/Female_1_under18_productreview.md)
- [Maheen](./Students/Product-Review/Female-2/Female_2_ProductReview.md)
- [Tooba](./Students/Product-Review/Female-3/Female_3_review.md)
- [Hassaan](./Students/Product-Review/Male-1/Male_1_Productreview.md)

### Professor pre-product interviews

- [Ma’am Qurat](./Professors/Pre-Product/Maam-Qurat/maam_qurat_interview_transcript_rearranged.md)
- [Ayesha Shah Muhammad](./Professors/Pre-Product/Ayesha-Shah/ayesha_shah_professor_interview_round_one.md)
- [Dr. Asjad — Virtual University](./Professors/Pre-Product/Dr-Asjad-Virtual-University/Dr_Asjad_Virtual_University_Interview.md)

### Professional pre-product interview

- [Dr. Mayeda — psychology professional](./Professionals/Pre-Product/Dr%20Mayda/readme.md)

## Consent, privacy, and responsible use

The transcripts include interview-specific consent and permission details. Those details must govern any future publication of clips or recordings. In particular:

- Hiba’s under-18 interview records permission for selected clips with face blurring.
- Arham’s transcript records confirmation of the interview script and planned clips.
- Female 3’s supporting audio clips and Ayesha Shah’s audio recording are retained as source material; they should not be republished outside the permission given for each interview.
- Professional contact information should only be used for the referral purpose explicitly permitted by the professional.
- Interview findings are product research, not clinical diagnoses or proof that one accommodation works for every learner.

## File structure

The following tree shows the tracked research content. Structural `.gitkeep` placeholders are omitted for readability.

```text
/
├── README.md
├── Type2Learn_Commit_History.md
├── proves/
│   ├── README.md
│   ├── Analytics_HTTP_Traffic_type2learn.tech_Cloudflare.pdf
│   └── Reports_snapshot-1.pdf
├── revies/
│   ├── README.md
│   ├── Ahmed_dark_mode_review.jpeg
│   ├── Abdul rehman.jpeg
│   ├── Abubakar.jpeg
│   ├── Ahmad_review.png
│   ├── Ali_Rehman_review.jpeg
│   ├── Areeba_Naeem_review.png
│   ├── Bilal_Nadeem_review.png
│   ├── Fawad_review.png
│   ├── Faryal_Fatima_review.jpeg
│   ├── Hamza_Zia_review.jpeg
│   ├── Huzaifa_Sharif_review.png
│   ├── Ihave.jpeg
│   ├── Maheen_Ateeq_review.jpeg
│   ├── Maryam_review.jpeg
│   ├── Minahil_Fatima_review.jpeg
│   ├── Miray_Fatima_review.jpeg
│   ├── Muhammad_Ali_Imran_review.jpeg
│   ├── Muhammad_Mahd_review.jpeg
│   ├── Muhammad_Taha_review.png
│   ├── Muhammad_Zubair_review.jpeg
│   ├── Obaida.jpeg
│   ├── Omair.jpeg
│   ├── Jiya_review.jpeg
│   ├── rehan.jpeg
│   ├── rayna.jpeg
│   ├── Saad_review.png
│   ├── Sami_review.jpeg
│   ├── Talhaaziz.jpeg
│   ├── Taimoor_review.png
│   ├── Zoha_Hussayn_review.jpeg
│   ├── hassanmehboob.jpeg
│   └── muneebb.jpeg
├── Professionals/
│   └── Pre-Product/
│       └── Dr Mayda/
│           ├── readme.md
│           └── animation.mp4
├── Professors/
│   └── Pre-Product/
│       ├── Ayesha-Shah/
│       │   ├── ayesha_shah_professor_interview_round_one.md
│       │   └── ayesha_shah_professor_interview_round_one.ogg
│       ├── Dr-Asjad-Virtual-University/
│       │   └── Dr_Asjad_Virtual_University_Interview.md
│       └── Maam-Qurat/
│           └── maam_qurat_interview_transcript_rearranged.md
└── Students/
    ├── Pre-Product/
    │   ├── Female-1-Under-18/
    │   │   └── Female_1_Interview_Under18.md
    │   ├── Female-2/
    │   │   └── Female_2_interview.md
    │   ├── Female-3/
    │   │   ├── Female_3_interview.md
    │   │   ├── (Audio) animations.m4a
    │   │   ├── (Audio) opinion on typing.m4a
    │   │   ├── (Audio) recording on.m4a
    │   │   ├── (Audio) situation where you had to be verbal.m4a
    │   │   ├── (Audio) study techniques.m4a
    │   │   ├── (Audio) what were you feeling.m4a
    │   │   ├── (Audio) what would have helped.m4a
    │   │   └── (Audio) white noise.m4a
    │   ├── Male-1/
    │   │   └── Male_1_Interview.md
    │   └── Male-2/
    │       └── Male_2_Interview.md
    └── Product-Review/
        ├── Female-1-Under-18/
        │   └── Female_1_under18_productreview.md
        ├── Female-2/
        │   └── Female_2_ProductReview.md
        ├── Female-3/
        │   └── Female_3_review.md
        └── Male-1/
            └── Male_1_Productreview.md
```
