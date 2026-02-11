# Tools

> Which tools do you use when? An overview.

> 🚧 **Work in progress** — This page is still being refined. Content may change.

---

The tool matters less than what you do with it. But it helps to know what's out there -- and what makes each one different.

---

## At a glance

| Tool | What it does | When |
|------|--------------|------|
| **MacWhisper** | Dictation + local transcription | You want to dictate, privacy matters |
| **Claude** | Thoughtful, concise | Deeper analysis, ethical considerations |
| **ChatGPT** | Extensive, broad | Quick sparring, many integrations |
| **Gemini** | 1M context, filters noise | Large documents, cross-model check |
| **T3 Chat** | Multi-model interface | Comparing models, price/value |
| **Claude Code + Finn** | Agentic collaboration | Toolkit/prompt development |
| **Dembrane** | Live transcription + echo | Real-time feedback in sessions |
| **Notion AI** | AI in your workspace | Everything in one place, context |
| **NotebookLM** | Sources → other formats | Creating podcasts, video, slides |

---

## Dictation + transcription (local)

### MacWhisper

**What is it?**
A Mac app that turns speech into text -- entirely on your own computer, without anything going to the cloud. Developed by Jordi Bruin, based on OpenAI's Whisper technology.

**Why I use it:**
Dictation is the number one reason. It changes the entire workflow: dictate → AI → dictate → AI. The threshold for capturing thoughts drops to almost zero. Giving feedback to AI, speaking observations after a session, thinking out loud -- it all goes faster than typing.

**Bonus: privacy-first**
Everything happens locally on your Mac. No audio to servers, no text to the cloud. Useful for sensitive conversations.

**What makes it different:**
With newer models (like Parakeet 3), an hour of audio can be transcribed in 1-2 minutes. The old assumption that local is slower is becoming less and less true.

---

## AI models

**Why three models?**
I mainly work with three: Claude, ChatGPT, and Gemini. There are dozens by now, but these are the three I use most. What I notice: they seem similar until you use them frequently. Then you feel the differences.

It's like having three advisors. The same question, but different style, different depth, different assumptions.

### Claude (Anthropic)

**What is it?**
An AI assistant from Anthropic, founded by former OpenAI researchers. Anthropic distinguishes itself through a strong focus on AI safety -- they have a team that looks at the long-term impact of AI on humanity.

**How it feels:**
What I notice: thoughtful. Sometimes you get two sentences when that's enough. Less "here's everything I know," more to-the-point.

**When to use:**
- Deeper analysis of transcripts
- Iteration on syntheses
- Complex prompt development
- When you want nuanced, concise answers

### ChatGPT (OpenAI)

**What is it?**
The AI assistant from OpenAI, the company that kicked off the generative AI wave with GPT-3. ChatGPT was the first to be used on a massive scale and is still the best known.

**How it feels:**
Extensive. The way I see it, ChatGPT's helpfulness lies in its richness and volume -- answers are often long and detailed. Becoming increasingly commercial.

**When to use:**
- Sparring and quick analysis
- Widely available, many integrations
- When you want extensive, detailed answers

### Gemini (Google)

**What is it?**
Google's AI assistant, based on their own language models. Distinguishes itself through an enormous context window (1 million tokens) -- you can feed it entire books.

**How it feels:**
What strikes me: Gemini filters noise. With the same prompt, its answer was 4x shorter than Claude and ChatGPT -- but still good. It seems like Gemini itself chooses what really matters. Emotionally intelligent.

**When to use:**
- Analyzing very large documents
- Cross-model feedback loops (have Gemini critique Claude's output)
- When you want shorter, filtered answers

---

## Multi-model tools

### T3 Chat

**What is it?**
A "multi-model interface" -- one chat app that gives you access to Claude, ChatGPT, Gemini, and other models simultaneously. Made by developer Theo Browne. Instead of three separate subscriptions and three separate tabs, you have everything in one window.

**Why I use it:**
Speed -- no switching between tabs and logins. And price/value -- cheaper than separate subscriptions ($8/month for access to models that would cost $60+ separately). It makes it easy to try and compare different models.

**When to use:**
- You want to compare outputs from different models
- Quick experimentation with which model works best for your task

### Claude Code + Finn

**What is it?**
Claude Code is Anthropic's "agentic coding tool" -- AI that doesn't just answer, but actually executes tasks. It runs in your terminal or development environment, reads your entire project, and can independently edit files, write code, and execute workflows.

"Agentic" means: the AI takes initiative. You give an instruction ("analyze these five transcripts and create a synthesis"), and Claude Code carries it out -- reads the files, creates analyses, writes output, asks for feedback, adjusts. That's fundamentally different from a chat where you always have to figure out the next step yourself.

**How I use it:**
By loading my personal context files, Claude Code gets a personality -- Finn. Tuned to my preferences, with skills I've developed: writing style check, prompt generation through interviews, best practices from a year and a half of work.

A concrete example: when analyzing multiple parallel table conversations, Claude Code can independently analyze each transcript separately, place the analyses side by side, identify patterns, and create a synthesis -- all in one instruction.

**When to use:**
- Toolkit development: writing and iterating on content
- Prompt development: building and testing prompts
- Multi-file analysis: processing multiple transcripts simultaneously
- When you want to collaborate on something, not just ask questions

---

## Integrated platforms

### Dembrane

**What is it?**
A platform from Eindhoven that uses AI for group conversations. You can transcribe live, analyze directly, and give the group real-time feedback. According to the makers: "Helping communities grow smarter as they grow larger."

The core: ECHO, their tool that captures conversations, analyzes them, and generates insights -- using the exact words of participants, so they recognize themselves in the output.

**How I use it:**
"Dictation but for groups." Semi-live: breakout → conversation → reflect back via projector → group responds → back to AI. A new collaboration tool that didn't exist before.

Using AI in the conversation with a human touch. You introduce it as a person.

**When to use:**
- Real-time feedback during a session
- Multi-session processes where you want to track patterns over time
- Ownership in participant language is crucial
- Groups without an experienced facilitator who still want structure

**What makes it different:**
"10 seconds. One question. The conversation that was stuck started moving." The timing makes the difference -- feedback in the moment lands differently than a report after the fact.

### Notion AI

**What is it?**
Notion is an "all-in-one workspace" -- an app that combines notes, documents, databases, and project management. Notion AI adds artificial intelligence to that: summarizing, writing, asking questions of your documents.

**How I use it:**
Notion is my work environment -- a lot of my context already lives there. Now with powerful AI models (Claude Opus 4.5, Gemini 3 Pro) that can work with all that context.

**What it does:**
- Integrated meetings tool with live transcription (digital and in-person)
- Apply AI to live transcript
- Everything in one place: recordings, transcripts, notes, documents

**Why it's interesting:**
Notion AI is something to keep an eye on. It's becoming increasingly powerful -- precisely because so much context already lives there.

### NotebookLM

**What is it?**
Google's "virtual research assistant" -- you upload sources (PDFs, docs, websites), and NotebookLM helps you understand them. The special thing: the AI only answers based on your sources, not based on the entire internet.

The best-known feature is "Audio Overview": NotebookLM creates a podcast from your documents. Two AI hosts discuss the key themes in an accessible conversation. By now also: video presentations, infographics, and slide decks.

**Why I use it:**
You can share information and knowledge in ways that weren't possible before. "The podcast made the insights shareable with others who weren't there."

**When to use:**
- Sharing a 3-hour workshop in a more accessible way
- Making insights listenable (on the go, for people who don't read)
- Distilling key themes to their essence

---

## Built-in options

### Google Meet / Microsoft Teams

Basic transcription within your existing ecosystem. If you're already working in Google or Microsoft and only need basic transcription, you don't need to install extra tools.

---

## How do you choose?

| Question | Tool |
|----------|------|
| Want to dictate? | MacWhisper |
| Privacy matters? | MacWhisper (local) |
| Thoughtful and concise? | Claude |
| Extensive and detailed? | ChatGPT |
| Large context, filtered? | Gemini |
| Compare models? | T3 Chat |
| Collaborate on a project? | Claude Code |
| Real-time feedback in session? | Dembrane |
| Everything in Notion? | Notion AI |
| Convert sources? | NotebookLM |

---

## Privacy considerations

Make a conscious choice per conversation:

| Type of conversation | Recommendation |
|----------------------|----------------|
| Sensitive | Local tool (MacWhisper) |
| External/public | Cloud is fine |
| In doubt? | Local |

*For a deeper dive into privacy choices per tool, read [Safe practices with AI](safe-practices.md).*

---

> "The tool matters less than what you do with it. Start with what works for your situation."
