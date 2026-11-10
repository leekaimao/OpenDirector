# GPT Image quality verification evidence

PR: https://github.com/ThinkFlowLab/OpenDirector/pull/243

Implementation commit: `7390034ed70cc40b7ca44a76620514ad96b5e1ae`

Captured on macOS on 2026-11-10 using the isolated creation test server and a model double. No live OpenAI API calls or real API keys were used.

The screenshots show High retained after save and reload in Chinese and English. The recording shows Low/Medium/High selection, save/reload, language switching, a mock generation with persisted/frozen High inputs, switching to an unsupported model, and resetting to Auto. The solid-color image is a fixture, not evidence of real model quality.

Real-provider acceptance, including checking the returned quality against the request, remains unverified and requires an OpenAI API key with image-model access.
