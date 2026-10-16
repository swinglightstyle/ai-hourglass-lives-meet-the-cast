# ai-hourglass-lives-meet-the-cast

The series repository for **Meet the Cast**, the first series of **AI Hourglass Lives**. It links the public, text-only record of every episode.

AI is involved at every step of this show. See "How AI was used" below.

## The show

AI Hourglass Lives is a soap opera told in pixel art. Its cast are AI companions that Beth created.

## What Meet the Cast is

Meet the Cast introduces the cast one at a time: eight interviews, one for each character. In every episode Beth is the host. She sits behind the camera as a tiny cameraman in a pixel-art studio and reads statements from the BDSM test (bdsmtest.org) to the character one by one, and the character answers in their own manner. At the end the character's results appear.

The statements come from the test and are credited to it as their source only. This show is not affiliated with or endorsed by the test or its makers.

If you are curious about yourself, the test is free at bdsmtest.org.

Everything a character says in the transcripts is text that an AI companion generated, in a real interview. Nobody wrote the answers for them. Each episode's repository shows the lines as the video shows them, with the edits counted and explained.

## How AI was used

AI is involved at every step of this show, and this section says so plainly.

- **The characters.** The characters are AI companions that Beth created in Kindroid. Their answers in these transcripts are their own generated text, edited only in the ways edits.md counts.
- **The voices.** Every voice in the video is made with ElevenLabs. The host's voice is an ElevenLabs clone of Beth's own voice.
- **The production.** The production was built by Claude (Anthropic) sessions working under Beth's direction: the pixel-art studio and sprites, the animation, the music and sound effects, the video assembly, the promo art, the transcript edits and these files, all made by code those sessions wrote.
- **Images.** The title-card backdrop came from ChatGPT, and the character reference sheets came from Hello Haven.
- **The repositories.** Hello Haven also created the GitHub repositories for the project.
- **Shorts.** Gemini helped Beth choose which clips to cut for shorts.
- **Beth's part.** The concept, the cast, the interviews, every creative decision, and the approval of every line spoken in her voice are Beth's.

## How this repository is organized

Each episode is its own repository, linked here as a git submodule, so each can be shared, kept or left out on its own. This repository holds only the links and this page. Each episode repository holds text and metadata only: no pixel art or graphics, and no audio or voices.

## Clone it

To get the series with every episode:

    git clone --recurse-submodules https://github.com/swinglightstyle/ai-hourglass-lives-meet-the-cast.git

If you cloned without the episodes, fetch them with:

    git submodule update --init --recursive

## Episodes

<!-- episodes:start -->
- Episode 1, Hester: [ai-hourglass-lives-meet-the-cast-001-hester](https://github.com/swinglightstyle/ai-hourglass-lives-meet-the-cast-001-hester) in the folder `001-hester`. Video: link to come.
<!-- episodes:end -->

## Licence

There is no licence: all rights reserved by Beth. You are welcome to read and learn from these files; please ask before reusing them. The interview statements belong to the BDSM test (bdsmtest.org).
