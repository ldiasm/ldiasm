<div align="center">

# Lucas Dias Procópio Mercês

### Software Engineer · Mobile Products · Native Platforms · Full-Stack Architecture

Building accessible, reliable, and delightful products for mobile, web, and desktop.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasmerces)
[![Active Projects](https://img.shields.io/badge/Portfolio-Active_Projects-6C47FF?style=for-the-badge&logo=github&logoColor=white)](#active-private-projects)

[Active projects](#active-private-projects) · [Production work](#production-work--plein-air) · [Engineering approach](#engineering-approach) · [Career highlights](#career-highlights)

</div>

---

## About me

I am a Software Engineer focused on mobile products, accessible user experiences, performance, and dependable production delivery. I work comfortably from product discovery and interface architecture to native integrations, backend contracts, data, testing, and release pipelines.

My experience spans food-service technology, fitness, e-commerce, financial services, consumer electronics, healthcare, games, creative tools, and public-sector systems. Recent work includes high-traffic consumer applications used across the United States and a growing portfolio of independently developed products.

> 🔒 **Privacy by design:** professional and private-project source code remains private. This portfolio presents public products, verified technologies, contribution areas, and outcomes without exposing client-owned code or confidential implementation details.

## Active private projects

These are products I am actively building or evolving. Their repositories remain private, but the product direction, engineering scope, and technology choices can be shared.

### Product development

#### 🃏 Royale Companion

![Active](https://img.shields.io/badge/Status-Active_Development-22C55E?style=flat-square)
![Mobile and Web](https://img.shields.io/badge/Platforms-iOS_%C2%B7_Android_%C2%B7_Web-6C47FF?style=flat-square)
![Private Source](https://img.shields.io/badge/Source-Private-334155?style=flat-square&logo=github)

A Magic: The Gathering companion platform designed to support real matches, deck and commander workflows, multiplayer tables, card discovery, rules assistance, and community participation from a single product ecosystem.

- **Current engineering:** resilient QR seat claiming, authenticated and guest participation, live-session synchronization, indexed card search, game-screen performance, accessibility, and Android/iOS delivery.
- **Architecture:** durable server state as the source of truth, Realtime as a synchronization signal, capability-backed transactions, RLS-protected data, local SQLite support, isolated high-frequency rendering, and observable release flows.
- **Stack:** React Native, Expo Router, TypeScript, Supabase Auth/Postgres/Realtime/Storage/Edge Functions, SQLite, Skia, Reanimated, Zustand, Zod, Sentry, Jest, pgTAP, and Fastlane.
- **Public surface:** [open the Royale Companion web experience](https://royalecompanion.vercel.app/).

#### 📋 Peripecia Tech

![Active](https://img.shields.io/badge/Status-Active_Development-22C55E?style=flat-square)
![Full Stack](https://img.shields.io/badge/Product-Full_Stack_Web_%C2%B7_Mobile-F97316?style=flat-square)
![Private Source](https://img.shields.io/badge/Source-Private-334155?style=flat-square&logo=github)

A collaborative work-management platform inspired by the clarity of Trello, organized around teams, workspaces, boards, lanes, and cards while extending the model with planning, permissions, activity, and richer project context.

- **Current engineering:** multi-tenant access rules, invitations and ownership, drag-and-drop boards, card details and activity, aggregate planning views, notifications, and private attachments.
- **Architecture:** a type-safe monorepo with shared UI and contracts, vertical feature slices, end-to-end typed APIs, authorization-preserving projections, direct-to-storage uploads, and short-lived signed access.
- **Stack:** Bun, Turborepo, React, React Native, TanStack Router/Query/Form, Elysia, oRPC, Drizzle ORM, PostgreSQL, Supabase Storage, Better Auth, Zod, Biome, and Vercel.

#### 📸 Tubbiecam

![Active](https://img.shields.io/badge/Status-Active_R%26D-22C55E?style=flat-square)
![Native Camera](https://img.shields.io/badge/Product-Native_Camera_%C2%B7_On--device_AI-EC4899?style=flat-square)
![Private Source](https://img.shields.io/badge/Source-Private-334155?style=flat-square&logo=github)

A camera-first portrait assistant that helps people capture better selfies and product photos through live framing guidance, on-device visual signals, fast capture, and a native post-processing workflow.

- **Current engineering:** person, face, smile, pose, and luminance signals; capture-readiness guidance; JPEG-first and RAW-aware processing; non-destructive editing; native live previews; gallery variants; and privacy-reduced local evaluation.
- **Architecture:** Feature-Sliced Design in React Native, deferred camera loading, native frame processors and renderers, revision-protected preview sessions, background render queues, and device-local research workflows.
- **Stack:** React Native, Expo Development Builds, VisionCamera, MediaPipe, Worklets, TypeScript, Swift, Kotlin, Core Image, Android media APIs, TTS, and Jest.

#### 🩺 Singular Tech

![Active](https://img.shields.io/badge/Status-Active_Architecture_Evolution-22C55E?style=flat-square)
![Desktop](https://img.shields.io/badge/Product-Desktop_%C2%B7_Offline_Capable-0EA5E9?style=flat-square)
![Private Source](https://img.shields.io/badge/Source-Private-334155?style=flat-square&logo=github)

A desktop-first operations platform for psychology clinics, covering administrative records, professionals, patients, rooms, insurance plans, availability, and appointment scheduling with dependable local continuity.

- **Current engineering:** migration from a local desktop runtime toward a Supabase-authoritative shared backend while preserving existing workflows and offline contingency.
- **Architecture:** UI → application use case → repository contract → Tauri command → Rust → SQLite, complemented by a local outbox, idempotent replay, conflict evidence, timeout protection, SQL migrations, RLS, and RPC boundaries.
- **Stack:** Tauri 2, React, TypeScript, Vite, Rust, SQLite, Supabase Postgres, Edge Functions, Vitest, pgTAP, GitHub Actions, and Windows installer delivery.

### Creative and experimental labs

#### 🎨 Jega Noir

![Incubation](https://img.shields.io/badge/Status-Product_Incubation-F59E0B?style=flat-square)
![Web](https://img.shields.io/badge/Product-Responsive_Web_Experience-8B5CF6?style=flat-square)
![Private Source](https://img.shields.io/badge/Source-Private-334155?style=flat-square&logo=github)

A highly visual, responsive brand and portfolio experience built around a noir-inspired art direction. The product explores how cinematic presentation, strong typography, modular storytelling, and responsive behavior can coexist without sacrificing maintainability.

- **Current engineering:** responsive one-page composition, reusable design tokens, modular content sections, mobile navigation, deployment optimization, and preparation for final case studies and imagery.
- **Stack:** React 19, TypeScript, Vite, SCSS Modules, responsive design, semantic HTML, and component-driven content.

#### 🧩 Procedural Maze X

![Prototype](https://img.shields.io/badge/Status-Experimental_Prototype-F59E0B?style=flat-square)
![Game](https://img.shields.io/badge/Product-Mobile_3D_Game-10B981?style=flat-square)
![Private Source](https://img.shields.io/badge/Source-Private-334155?style=flat-square&logo=github)

A mobile-first 3D maze prototype that evolves an earlier React Native procedural-maze experiment into a native game-engine environment with generated levels and touch-oriented play.

- **Current engineering:** runtime 3D maze generation, multiple difficulty levels, collision-aware first-person movement, desktop fallbacks, and dual touch joysticks.
- **Stack:** Godot 4.6, GDScript, procedural generation, `CharacterBody3D`, runtime UI drawing, collision systems, and mobile input.

---

## Production work · Plein Air

From 2023 to 2025, I contributed to a portfolio of customer-facing restaurant applications as part of the Plein Air engineering team. Each product had its own brand, operational rules, integrations, and customer journey, while sharing the demands of reliable ordering, loyalty, payments, and production support.

| Product | Project synopsis | Live products |
| :--- | :--- | :---: |
| 🍗 **Dave's Hot Chicken** | A high-traffic ordering and loyalty experience with personalized menus, pickup and delivery, rewards, offers, store discovery, and repeat-order flows. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://www.daveshotchicken.com/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/daves-hot-chicken/id1668228991) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.mobile.daveshotchicken) |
| 🍕 **Sbarro** | A mobile ordering platform for a global pizza brand, combining order-ahead, delivery, rewards, menu browsing, location discovery, and quick reordering. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://sbarro.com/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/sbarro/id1670813889) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.sbarro.mobileapp) |
| 🍨 **Cold Stone Creamery** | A highly customizable ice-cream ordering journey with pickup and delivery, favorites, recent orders, points, and reward redemption. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://www.coldstonecreamery.com/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/cold-stone/id690080616) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.olo.coldstone) |
| 🌮 **Taco Palenque** | An order-ahead and delivery product with customer profiles, favorite and recent orders, scheduled pickup, card payments, and order instructions. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://tacopalenque.com/home/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/taco-palenque/id1593418589) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.tacopalenque.app) |
| 🌯 **TacoTime** | A location-aware ordering experience that helps customers find participating restaurants, explore menus, and place orders ahead of arrival. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://www.tacotime.com/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/tacotime/id865048468) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.kahala.tacotime) |
| 🥑 **Baja Fresh** | A streamlined order-ahead product centered on store discovery, menu exploration, advance payment, and convenient in-store pickup. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://www.bajafresh.com/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/baja-fresh/id658240462) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.olo.bajafresh) |
| 🍪 **Dirty Dough** | A customer mobile experience for the stuffed-cookie brand, supporting its digital ordering and engagement journey. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://www.dirtydoughcookies.com/) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.ce.android.brand.dirtydoughcookiesapp) |
| 🥤 **Nekter Juice Bar** | A mobile ordering and loyalty platform designed for order-ahead convenience, group orders, rewards, birthday benefits, and personalized offers. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://www.nekterjuicebar.com/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/nekter-juice-bar/id902660278) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.ak.app.neckter.activity) |
| 🌶️ **Tijuana Flats** | An ordering and tiered-rewards experience with pickup and delivery, saved meals, recent orders, receipt scanning, offers, and restaurant discovery. | [![Web](https://img.shields.io/badge/Web-Visit-6C47FF?style=flat-square&logo=googlechrome&logoColor=white)](https://www.tijuanaflats.com/) [![iOS](https://img.shields.io/badge/iOS-App_Store-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/tijuana-flats/id1491125522) [![Android](https://img.shields.io/badge/Android-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.tijuanaflats.app) |

### My contribution across the portfolio

| Product engineering | Quality and collaboration |
| --- | --- |
| React Native feature development and continuous maintenance | Production incident response and crash investigation |
| Ordering, payments, loyalty, location, and engagement integrations | Performance, stability, and structural improvements |
| Olo/OloPay, Punchh, Infobip, SpendGo, RadarSDK, and MapLibre | Daily collaboration in English with PMs, QAs, engineers, and stakeholders |
| ADA/WCAG accessibility with VoiceOver, TalkBack, keyboard, and TV navigation | Ownership of urgent work and dependable cross-platform delivery |

## Engineering approach

| Principle | How I apply it |
| :--- | :--- |
| **Product-aware architecture** | Start from the user journey and business invariants, then choose boundaries and infrastructure that keep the product understandable. |
| **Reliable distributed state** | Separate durable state from notifications, design idempotent operations, reconcile after missed events, and make failure states visible. |
| **Performance by isolation** | Measure the interaction path, keep high-frequency state close to its consumers, and avoid unnecessary render or I/O cascades. |
| **Native where it matters** | Use Swift, Kotlin, Rust, camera pipelines, and platform APIs behind focused interfaces when cross-platform abstractions are not enough. |
| **Privacy and secure boundaries** | Minimize sensitive data, enforce authorization at server and database boundaries, and keep secrets and private artifacts out of clients and public documentation. |
| **Verification proportional to risk** | Combine unit, integration, database, build, and device checks according to the surface being changed. |

## Technical toolkit

**Mobile and native**

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Skia](https://img.shields.io/badge/React_Native_Skia-0F9D58?style=flat-square&logo=skia&logoColor=white)
![VisionCamera](https://img.shields.io/badge/VisionCamera-111111?style=flat-square&logo=camera&logoColor=white)

**Web, desktop, and product UI**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TanStack Query](https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)

**Backend, data, and delivery**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=1A1A1A)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=white)

## Career highlights

Some client and product names remain confidential, so these projects are presented through their public business context and the engineering work involved.

| Project | Synopsis | Main technologies and practices |
| :--- | :--- | :--- |
| **Global digital fitness platform** | Mobile and web experiences for a worldwide fitness product serving millions of users, with an emphasis on continuous feature delivery, maintenance, and consistent cross-platform behavior. | React Native, React, Node.js, JavaScript, product collaboration |
| **Large online marketplace** | Consumer-facing marketplace work focused on improving mobile and web journeys inside a high-scale product environment. | React Native, React, API integration, mobile and web UX |
| **Consumer-electronics applications** | Cross-platform applications delivered for a leading global electronics company, alongside an internal React Native course created to strengthen the engineering team. | React Native, React, Node.js, technical instruction |
| **Investment and financial education ecosystem** | A cross-platform investment product and a gamified financial-education experience backed by Node.js and PostgreSQL APIs. The work included product definition, gamification strategy, and client-facing presentation at Brazil Game Show. | React Native, Node.js, PostgreSQL, REST APIs, gamification |
| **VOBYS human-capital management** | An enterprise people-management platform evolved for government clients through full-stack features, business-rule implementation, database work, and Agile delivery. | Java, JSF, JavaScript, HTML, CSS, Oracle, PostgreSQL, Scrum |
| **Benner Health implementations** | Healthcare-system implementations tailored to large organizations through workflow customization, reports, macros, SQL queries, data extraction, and process automation. | SQL, reporting, workflow customization, automation, consulting |
| **Public-sector web systems** | Web application development and operational support in federal institutions, combining feature delivery, database queries, CI, version control, and structured team workflows. | Java, SQL, Jenkins, Git, SVN, Jira, enterprise delivery |

## What I value

Useful products. Clear engineering decisions. Inclusive experiences. Sustainable architecture. Dependable collaboration.

I enjoy solving difficult mobile problems while keeping the result maintainable for the people who will support it next.

<div align="center">

### Let's build something people enjoy using.

[![LinkedIn](https://img.shields.io/badge/Let's_connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasmerces)

</div>
