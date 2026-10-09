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

I build production React Native apps where the hard problems are the point: Bluetooth hardware and live MIDI.

I came from audiovisual work. I retrained as a developer in 2021 through an OpenClassrooms program, then kept learning on my own. That background is why I end up on products where the hardware and the interface have to talk to each other.

Most recently I was the lead React Native engineer on [Odisei Play](https://apps.apple.com/app/odisei-play/id6748117099), the companion app for the Travel Sax, an electronic saxophone: video courses, play-along songs and practice tools that react live to what you play, streamed from the instrument over Bluetooth MIDI. One React Native codebase, three platforms, a two-engineer team.

I also piloted coding agents ([Claude Code](https://www.anthropic.com/claude-code)) on that same production codebase. The specs, reviews and shipping decisions stay mine. The agents do the heavy lifting. I write about the method on my [blog](https://www.jean-desauw.fr/blog).

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

</td>
<td width="50%">

**Shipped:**
- ✅ Live on iOS, Android and web from one React Native codebase
- ✅ 5,677 of 14,778 commits in the repo (38%)
- ✅ A release every two weeks, from two engineers and AI agents
- ✅ 150+ screens, a design system of 400+ components documented in Storybook
- ✅ 10 shared packages, with 52 rule files and 13 hooks for the agents

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
| **React Native / Expo** | Production apps on iOS, Android and web: complex animations, BLE, video |
| **MIDI × hardware** | MIDI over Bluetooth, device connectivity across native and web |
| **Agentic delivery** | Claude Code as a main developer on production code: spec-first workflow, review gates, the human keeps the decisions |
| **Architecture & leadership** | CTO-facing ownership: monorepos, design systems, code reviews |

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## 🧩 A repo your agents can read

Two people do not ship a product this size every two weeks unless the codebase itself is doing part of the work. That is the second thing I install on a contract. It acts on your repo, not on your developers. I am not there to teach your team to prompt.

- **One CLAUDE.md per package.** The agent loads the context of the module it works in, not the whole repo.
- **Rules in one place.** You change a convention once, every agent follows it.
- **Skills and hooks written for your repo.** What has to be checked before a commit gets checked without you.

This is the setup I put in place on Odisei Play, where the designer worked in Storybook, on shared design tokens, with an agent. [How it works](https://www.jean-desauw.fr/services).

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

## 📦 Open source

- [sneq-narrative-system](https://github.com/JeanDes-Code/sneq-narrative-system): narrative-state engine for AI-narrated games, published on npm as `sneq-engine`. Built to keep the LLM from forgetting or forking what already happened in the story. TypeScript, SQLite, optional sqlite-vec.

  [![npm version](https://img.shields.io/npm/v/sneq-engine)](https://www.npmjs.com/package/sneq-engine) [![npm downloads](https://img.shields.io/npm/d18m/sneq-engine)](https://www.npmjs.com/package/sneq-engine)
- A merged fix in [react-native-ble-manager](https://github.com/innoveit/react-native-ble-manager): [#1437](https://github.com/innoveit/react-native-ble-manager/pull/1437), "fix(android): forward the GATT status on remote disconnect".
- Bug reports filed since 2024, including:
  - [expo/expo](https://github.com/expo/expo/issues/43692): `expo-screen-orientation` `lockAsync` ignored on iOS 16+ during navigation transitions. The same bug is open in [react-native-screens #3831](https://github.com/software-mansion/react-native-screens/issues/3831).
  - [Shopify/react-native-skia #3794](https://github.com/Shopify/react-native-skia/issues/3794): duplicate `WebGPUView` registration with react-native-wgpu. On the WebGPU side, [wcandillon/react-native-webgpu #323](https://github.com/wcandillon/react-native-webgpu/issues/323): the iOS build fails with Skia.
  - Five issues in [uni-stack/uniwind](https://github.com/uni-stack/uniwind/issues?q=author%3AJeanDes-Code) and one in [nativewind/nativewind #846](https://github.com/nativewind/nativewind/issues/846).

<img src="https://raw.githubusercontent.com/JeanDes-Code/JeanDes-Code/master/assets/rule.svg" width="100%" alt="" />

<div align="center">

### Let's build

Available for a new mission. React Native, Expo, TypeScript, agentic delivery. Full remote.

[![Services](https://img.shields.io/badge/Services-13100D?style=for-the-badge&logo=safari&logoColor=D7A44D)](https://www.jean-desauw.fr/services)
[![Contact Me](https://img.shields.io/badge/Contact_Me-AD6800?style=for-the-badge&logoColor=white)](mailto:contact@jean-desauw.fr)

</div>
