# NeuroPrompt

A standalone, responsive neuroradiology prompt reference. Open `index.html`, or serve with `python3 -m http.server 8000` from this directory. No build or dependencies are required. Clipboard copying requires localhost or HTTPS; manual selection is provided when clipboard access fails.

117 prompts across Quick Prompts, 15 Clinical Domains, and Clinical Synthesis. Every detail panel prepends the same examination identification and accuracy rules. These rules are a new draft because the previously discussed wording was not available; a clinician should review the wording before clinical use. Prompt content is in `prompts.js`; shared rules are in `app.js`.

No Epic integration, patient data entry, or patient data storage. Theme preference is stored locally. An optional Google Fonts request enhances typography; system fonts work offline.
