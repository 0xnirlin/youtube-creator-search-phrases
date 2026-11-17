# What YouTube creators search for: 8,430 real search phrases (November 2026)

A free dataset of 8,430 real search phrases about making YouTube videos, collected from Google and YouTube autocomplete in November 2026. Use it for video ideas, titles, keyword research, articles or your own analysis.

**The study with charts and findings:** [What YouTube Creators Search For: 8,430 Phrases Studied](https://getziztu.com/blog/what-youtube-creators-search-for?utm_source=github&utm_medium=dataset&utm_campaign=creator_search_study)

## Headline findings

- The average phrase has **5.0 words**. 52.7% have five words or more and 18.8% have seven or more.
- **Faceless channels and automation** are the largest group: 1,967 phrases (23.3%).
- **Scripts, hooks and voiceover** come second: 1,635 phrases (19.4%).
- **AI is named in 1,201 phrases** (14.2%). Claude appears in 37 phrases and ChatGPT in 33.
- **626 phrases** contain "monetize" or "monetization" (7.4%); 109 of them also name AI.
- **1,060 phrases start with "how to"** (12.6%). 444 are yes or no questions (can, does, is, do, are, will, should).
- **210 phrases include "2026"**; only 49 include "2025".
- **547 phrases (6.5%)** are Hindi or Urdu written in Latin letters, or name an Indian language.

| Topic | Phrases | Share |
|---|---|---|
| Faceless channels and automation | 1,967 | 23.3% |
| Scripts, hooks and voiceover | 1,635 | 19.4% |
| AI tools | 1,201 | 14.2% |
| Shorts | 1,051 | 12.5% |
| Money and monetization | 1,000 | 11.9% |
| Video and channel ideas | 895 | 10.6% |
| Documentary, history and video essays | 883 | 10.5% |
| Niches | 856 | 10.2% |
| Growth: subscribers, views, watch time | 433 | 5.1% |
| Starting a channel | 319 | 3.8% |

A phrase can sit in more than one topic, so the shares overlap.

## The file

`youtube_creator_search_phrases_2026-11.csv` (8,430 rows)

| Column | What it holds |
|---|---|
| `phrase` | the search phrase, lower case |
| `seen_in` | `google`, `youtube` or `both` |
| `words` | number of words |
| `topics` | topic groups used in the study, separated by `; ` |

## How it was collected

Autocomplete is the list of suggestions that appears while you type a search. Google says its predictions ["reflect real searches that have been done on Google"](https://support.google.com/websearch/answer/7368877).

1. 38 seed phrases about making YouTube videos (for example "youtube script", "faceless youtube channel", "youtube niche", "youtube shorts ideas", "youtube monetization").
2. Each seed was sent alone, followed by each letter a to z, and after question words (how to, how much, can you, is, does, best and others): 2,400 searches across Google and YouTube.
3. 8,701 distinct suggestions were saved. Phrases in non-Latin scripts and off-topic phrases were removed, leaving 8,430.

## Limits

- The file shows that a phrase is searched, not how often. Shares are shares of phrases, not of search volume.
- The seeds were ours, so the topic mix reflects what we asked about.
- Collected in English, from one location, in one week of November 2026.
- Autocomplete leaves out some phrases by policy, so the file is not complete.

## License and citation

[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/). Copy, change and reuse it, also in paid work, with credit and a link to the study.

> Ziztu, "What YouTube Creators Search For: 8,430 Phrases Studied", November 2026, https://getziztu.com/blog/what-youtube-creators-search-for

## Who made this

[Ziztu](https://getziztu.com/?utm_source=github&utm_medium=dataset&utm_campaign=creator_search_study) is an AI video studio. Its [AI YouTube Video Maker](https://getziztu.com/ai-youtube-video-maker?utm_source=github&utm_medium=dataset&utm_campaign=creator_search_study) turns an idea or a script into a finished narrated video, and its [YouTube script writer](https://getziztu.com/youtube-script-writer?utm_source=github&utm_medium=dataset&utm_campaign=creator_search_study) is free to start. More guides for creators: [getziztu.com/blog](https://getziztu.com/blog?utm_source=github&utm_medium=dataset&utm_campaign=creator_search_study).
