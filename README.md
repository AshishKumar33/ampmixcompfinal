# Amplitude vs Mixpanel — Schema Compare

Compare Amplitude and Mixpanel event payloads side by side: match keys (including by leaf name), spot value differences, and see same-value/different-key pairs.

## Live demo

**https://ashishkumar33.github.io/ampmixcompfinal/**

*(Enable GitHub Pages in repo **Settings → Pages → Source: GitHub Actions** if not already on.)*

## Run locally

Open `amplitude-mixpanel-compare/index.html` in a browser (no server needed).

## Features

- Paste or edit JSON for Amplitude and Mixpanel; compare on demand
- Keys compared by **leaf name** (e.g. `event_properties.vertical` ↔ `vertical`); warning when paths differ
- Search, filter (all / common / Amplitude only / Mixpanel only), sort
- **Same value, different key** table (e.g. `device_id` vs `$device_id`)
- Tree and JSON views; hide input or show only the comparison table
- Mixpanel `$` keys normalized (e.g. `$device_id` → `device_id`) for comparison

## Repo

[https://github.com/AshishKumar33/ampmixcompfinal](https://github.com/AshishKumar33/ampmixcompfinal)
