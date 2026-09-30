# Mood Reader

A web page that reads your text out loud with an emotion, using a real human-sounding voice.

## How to use

1. Open `index.html` in Chrome, Edge or Safari (or host it with GitHub Pages, see below).
2. Type or paste your text. Put `*stars*` around a word to stress it.
3. Pick a mood: Neutral, Happy, Excited, Sad, Angry, Calm, Scared, Surprised or Secretive.
4. Pick a voice type, paste your API key, and press **Read**.
5. When it finishes, press **Save MP3** to keep the recording.

## Voice types

| Voice type | Sounds | Cost | Key |
|---|---|---|---|
| Human voice · OpenAI | Natural, acts out the mood from a written direction | about $0.015 per minute | [platform.openai.com/api-keys](https://platform.openai.com/api-keys) |
| Human voice · ElevenLabs | Most lifelike, uses mood tags like `[sad]` | free plan, then paid | [elevenlabs.io → Settings → API keys](https://elevenlabs.io/app/settings/api-keys) |
| Device voice | Robotic, built into your browser | free | none |

Use **Extra direction** to steer the voice further, for example "like a bedtime story" or
"British accent" (works best with OpenAI).

Your API key is saved only in your own browser (local storage) and is sent only to the voice
service you picked. Don't use it on a shared computer.

## Open it on your phone (GitHub Pages)

1. On GitHub, go to this repository → **Settings** → **Pages**.
2. Under **Branch**, choose the branch with `index.html` and the `/ (root)` folder, then **Save**.
3. After a minute, GitHub shows a link like `https://<your-name>.github.io/<repo>/`. Open it on any device.
