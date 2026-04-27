# Claude Prompt — Generate Hi‑Fi UI + Design System

Use the prompt below in Claude:

---
You are a principal mobile product designer and UX strategist.

I am building **Krypta Chat**, a premium privacy-first messaging app that competes with WhatsApp and Threema.

Design goals:
1) Top-class, attractive, professional mobile UI
2) Seamless and easy messaging UX
3) Strong confidentiality and privacy

Critical behavior:
- Messages are end-to-end encrypted.
- Locked chats appear obfuscated/gibberish by default until biometric authentication (Face ID/fingerprint).
- After successful biometric auth, messages are revealed.

Please deliver:
1. A **hi-fi mobile UI design specification** for core screens
2. A **complete design system** (color, typography, spacing, components, states)
3. An **interactive prototype flow** with step-by-step transitions
4. UX copy suggestions for privacy/security states
5. Accessibility and usability best practices

Constraints:
- Mobile-first (iOS + Android)
- Premium, modern visual style
- Dark mode + light mode
- Clear privacy indicators without technical jargon

Core screens to include:
- Splash + onboarding
- Authentication + biometric setup
- Chat list
- Conversation screen
- Locked chat state + biometric unlock
- Group chat settings
- Privacy settings panel
- Vault/secure media area

Output format:
- Section 1: Product concept
- Section 2: Screen-by-screen hi-fi specs
- Section 3: Design system tokens and component library
- Section 4: Prototype map (nodes + transitions)
- Section 5: Implementation handoff notes for developers

Use concise but specific design language, with practical details that can be directly implemented in Figma and then in React Native.
---
