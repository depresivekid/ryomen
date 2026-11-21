# RYŌMEN — iPhone PWA prototype

A personal installable web-app prototype for iPhone. No build tools are required to preview the UI.

## Included
- Russian dark-themed chat interface
- Editable character persona field
- Local chat history and manually added memory notes (localStorage)
- System speech synthesis for reading the last reply
- Experimental browser speech recognition; iOS Safari may not expose it, so iOS keyboard dictation is an alternative
- PWA manifest and offline shell cache

## Important limitations
This is a front-end prototype. Replies are local demo templates, not a connected language model. No user data is sent to a server. A real model requires a separately selected provider and a secure API relay; never embed a private API key in a public client app.

## Install on iPhone
Host these files over HTTPS (for example, a personal static site on a free hosting tier), open the site in Safari, tap Share -> Add to Home Screen -> Add. The files cannot be installed directly from a ZIP as an app.
