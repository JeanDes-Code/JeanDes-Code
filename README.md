<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/banner-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/banner-light.svg" />
  <img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/banner-dark.svg" width="100%" alt="Jean Desauw: React Native Engineer · Agentic Practitioner" />
</picture>

# Jean Desauw

**I build React Native in production. I pilot AI agents on the same code.**

[![Website](https://img.shields.io/badge/Portfolio-13100D?style=for-the-badge&logo=safari&logoColor=D7A44D)](https://www.jean-desauw.fr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-13100D?style=for-the-badge&logo=linkedin&logoColor=D7A44D)](https://www.linkedin.com/in/jean-desauw/)
[![Email](https://img.shields.io/badge/Email-13100D?style=for-the-badge&logoColor=D7A44D)](mailto:contact@jean-desauw.fr)

</div>

> **Available for a new mission.** React Native / Expo / TypeScript, full remote, with agentic delivery. [See my services](https://www.jean-desauw.fr/services).

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## About

I build production React Native apps where the hard problems are the point: real-time audio, Bluetooth hardware, live MIDI, on-device AI.

I came from audiovisual engineering and taught myself to code. That background is why I end up on products where the hardware and the interface have to talk to each other.

Most recently I was the lead React Native engineer behind [Odisei Play](https://apps.apple.com/app/odisei-play/id6748117099), the companion app for the Travel Sax, an electronic saxophone: video courses, play-along songs and practice tools that react live to what you play, streamed from the instrument over Bluetooth MIDI. One React Native codebase, three platforms, a two-engineer team.

In 2024 I started piloting coding agents ([Claude Code](https://www.anthropic.com/claude-code)) on that same production codebase. The specs, reviews and shipping decisions stay mine. The agents do the heavy lifting. I write about the method on my [blog](https://www.jean-desauw.fr/blog).

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## 🎵 Case study: Odisei Play

<table>
<tr>
<td width="50%">

**Lead React Native Engineer** (freelance) at [Odisei Music](https://odiseimusic.com/) · 2024 to 2026

Companion app for the Travel Sax, an electronic saxophone. Video courses, play-along songs and practice tools that react live to what you play over Bluetooth MIDI. One React Native codebase on iOS, Android and web.

**What I built and owned:**
- Device connectivity: scanning, pairing, MIDI-over-Bluetooth parsing, reconnection, with arbitration across Bluetooth, USB and audio input
- A web Bluetooth implementation, so the browser version connects to the instrument like the native apps do
- The learning experience: interactive video checkpoints that wait for you to actually play, and a post-session state machine sequencing awards, streaks and goals
- The monorepo migration: the app plus ten shared packages, a design-token pipeline, a Storybook design system
- The agentic infrastructure: per-package CLAUDE.md files, single-source-of-truth rules, custom skills and hooks. The whole team, designer included, worked with Claude Code on top of it

**What I did not build:** the audio engine, the pitch detection and the core playing screen are the work of Kim Chouard, the CTO. I built most of what surrounds them.

</td>
<td width="50%">

**Shipped:**
- ✅ Live on iOS, Android and web from one React Native codebase
- ✅ 5,677 of 14,778 commits in the repo (38%), in a codebase already a year old when I joined
- ✅ Bi-weekly release train with over-the-air patches in between
- ✅ 150+ screens, 24 feature modules, a design system of 340+ components in Storybook
- ✅ Two engineers, one designer and a few AI agents shipping like a much bigger team

**Stack:** React Native · Expo · TypeScript · Supabase · BLE

[![Visit live site](https://img.shields.io/badge/Visit_live_site-13100D?style=for-the-badge&logo=appstore&logoColor=D7A44D)](https://odiseimusic.com/odisei-play/)
[![App Store](https://img.shields.io/badge/App_Store-13100D?style=for-the-badge&logo=apple&logoColor=D7A44D)](https://apps.apple.com/app/odisei-play/id6748117099)

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## 🛠️ Technical Stack

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/stack-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/stack-light.svg" />
  <img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/stack-dark.svg" width="100%" alt="React Native · Expo · TypeScript · Reanimated · BLE · Supabase · Next.js · Claude Code" />
</picture>

</div>

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## 💼 What I Ship

| Domain | Reality |
|--------|---------|
| **React Native / Expo** | Production apps from zero to the App Store: complex animations, performance budgets, BLE and on-device AI |
| **Audio × hardware** | Real-time MIDI pipelines, Bluetooth device connectivity across native and web |
| **Agentic delivery** | Claude Code as a main developer on production code: spec-first workflow, review gates, the human keeps the decisions |
| **Architecture & leadership** | CTO-facing ownership: monorepos, design systems, roadmap, code reviews |

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## 🧩 A repo your agents can read

Two people do not ship a product this size every two weeks unless the codebase itself is doing part of the work. That is the second thing I install on a contract. It acts on your repo, not on your developers. I am not there to teach your team to prompt.

- **One CLAUDE.md per package.** The agent loads the context of the module it works in, not the whole repo.
- **Rules in one place.** You change a convention once, every agent follows it.
- **Skills and hooks written for your repo.** What has to be checked before a commit gets checked without you.

This is the setup I put in place on Odisei Play, where the designer worked in Storybook, on shared design tokens, with an agent. [How it works](https://www.jean-desauw.fr/services).

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## 📦 Open source

- [sneq-narrative-system](https://github.com/JeanDes-Code/sneq-narrative-system): narrative-state engine for AI-narrated games. Stops the LLM from forgetting or forking canonical reality. TypeScript, SQLite + sqlite-vec.

  [![npm version](https://img.shields.io/npm/v/sneq-engine)](https://www.npmjs.com/package/sneq-engine) [![npm downloads](https://img.shields.io/npm/d18m/sneq-engine)](https://www.npmjs.com/package/sneq-engine)
- High-signal bug reproductions for the React Native / Expo ecosystem: Fabric view-recycling touch-dead, LegendList sticky headers on web, Skia + WebGPUView conflicts. Minimal repros filed to help maintainers fix real issues.

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

<div align="center">

### Let's build

Available for a new mission. React Native, Expo, TypeScript, agentic delivery. Full remote.

[![Services](https://img.shields.io/badge/Services-13100D?style=for-the-badge&logo=safari&logoColor=D7A44D)](https://www.jean-desauw.fr/services)
[![Contact Me](https://img.shields.io/badge/Contact_Me-AD6800?style=for-the-badge&logoColor=white)](mailto:contact@jean-desauw.fr)

</div>
