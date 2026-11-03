# CircleTrack — Personal Relationship & Check-In Tracker

CircleTrack is a personal relationship-management dashboard for keeping track of important connections. It helps users review contact goals, log check-ins, browse an interaction timeline, and understand communication patterns through simple analytics.

## Features

- Dashboard with friend cards and contact-status summaries.
- Individual friend pages with profile details and contact goals.
- Quick check-ins for calls, messages, and video interactions.
- Chronological interaction timeline with filtering.
- Analytics visualizations for interaction types.
- Responsive UI, notifications, loading states, and a custom not-found page.

## Tech stack

- Next.js App Router and React
- Tailwind CSS and DaisyUI
- Recharts for data visualizations
- React Icons, React Toastify, and React Hot Toast

## Run locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Useful scripts

```bash
npm run dev      # development server
npm run build    # production build
npm start        # start production server after build
npm run lint     # ESLint
```

## Data and storage notes

- The initial friend list is demo data in `src/data/friends.json`.
- Interaction timeline entries are stored in the browser's `localStorage` under the CircleTrack key.
- This version does not include a hosted database, user authentication, or cross-device synchronization. Use fictional/sample contact details when demonstrating the project.

## Source attribution note

The supplied source archive's earlier README explicitly named **Md Alamin Miah** as author and linked to `github.com/mdalaminmiah/b13-a7-keen-keeper-app`. Confirm your right to publish this code and preserve any required attribution before making this repository public. The supplied archive did not contain the `LICENSE` file referenced by its old README, so do not assume the MIT licence text is present.
