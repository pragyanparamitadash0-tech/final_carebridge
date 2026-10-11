# CareBridge | Care, Connected

A responsive React + Vite hackathon prototype for patient-controlled health cards, consent-first provider access, appointments, chronological medical records, an emergency-card screen, a scripted health-information assistant, and community health resources.

## Run locally

```bash
npm install
npm run dev
npm run build
```

## Demo flows

- Switch Patient / Provider workspaces from the left navigation.
- Patient: inspect the emergency card, browse medical records, request appointments, try the scripted assistant, and open SOS mode.
- Provider: request consent, review appointment requests, add a demo clinical note, and inspect sample staff roles.
- Responsive desktop/mobile layout; English, Bengali and Hindi preference selector.

## Safety and scope

All identities, records, clinic schedules and staff are synthetic. Interactions run in the current browser session. Do not enter real patient data. There is no production authentication, database, identity verification, real consent delivery, biometric lock, live pharmacy directory, real AI inference, or emergency dispatch. SOS shows a locally available sample card and a phone-call link only; it cannot guarantee an offline alert. For emergencies in India, call 112. Never rely on this prototype for medical care.

## Before real deployment

Implement verified authentication and organization onboarding, server-enforced patient consent and time-limited access, database row-level security, audit logs, encryption, secure offline storage, clinician-reviewed health guidance, verified emergency integrations, and privacy/security/legal review.
