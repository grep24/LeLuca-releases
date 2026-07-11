# LeLuca — Releases

LeLuca is a native macOS meeting transcription and AI notes app. Record microphone and system audio, transcribe on-device with Whisper, then create summaries and cited answers with ChatGPT, OpenAI, Claude, OpenRouter, or Apple Intelligence.

**Download the latest DMG from [Releases](https://github.com/grep24/LeLuca-releases/releases/latest).**

- Universal (Apple Silicon + Intel), Developer ID-signed, notarized & stapled — no Gatekeeper warning.
- Requires macOS 26 or later.
- Verify integrity with the attached `.sha256` file: `shasum -a 256 -c LeLuca-<version>-macOS-universal.dmg.sha256`

Source code lives in a private repository; this repo only hosts release artifacts.

## Privacy

Read the full [Privacy Policy](PRIVACY.md).

LeLuca is local-first and does not include advertising, analytics, or tracking.

- Recording begins only after a user action and the required macOS permission.
- Speech transcription runs on the Mac. Original audio is not uploaded by the AI summary layer.
- Recordings, transcripts, summaries, and conversations are stored in the app’s local container.
- If the user selects a cloud AI service and grants permission, only the transcript text needed for a summary or question is sent directly to the selected OpenAI, Anthropic, or OpenRouter service. That processing is governed by the selected service’s terms and privacy policy.
- API keys and OAuth tokens are stored in the macOS Keychain.
- The update checker makes an anonymous request to this GitHub releases repository.
- Users can delete recordings in LeLuca and remove cloud credentials in Settings.

For privacy or support questions, open an issue in this repository.