# CINEMATIC AI VIDEO EDITOR PRO

**A professional AI video-editing agent skill with Malayalam-first speech understanding, cinematic storytelling and word-aware typography.**

Turn raw footage into polished Reels, Shorts, podcast clips, political commentary videos and documentary-style edits.

## Core capabilities

- Full-footage inspection and story analysis
- Speech transcription and word-level timing where supported
- Malayalam transcript and subtitle quality checks
- Strong visual hooks and bold Malayalam text hooks
- Kinetic typography and synchronized captions
- Context-aware B-roll, overlays and motion graphics
- Chroma-key refinement and studio-look image treatment
- Cinematic colour correction and grading
- Dialogue cleanup, sound effects and music balancing
- Quality control and platform-ready export planning

## Install

This repository contains an instruction-based agent skill. Copy `SKILL.md` into the skills directory of a compatible AI agent, or add the repository as a skill source if your agent supports that workflow.

**Important:** The skill itself does not magically provide a video editor, speech-recognition model or renderer. Real timeline editing and rendering require compatible tools or editor integrations. If those tools are not available, the agent must provide an actionable edit decision list and must not pretend it rendered a file.

## Quick start prompt

> Edit this Malayalam video as a professional 9:16 Reel. Analyse the complete footage and every spoken word. Preserve the speaker's meaning and voice. Create a powerful opening hook, bold Malayalam title, accurate synchronized captions, relevant visual inserts, premium studio look, cinematic colour grading and clean dialogue audio. Use no background music. Review the final render for spelling, timing, audio and visual defects.

## Default export profiles

| Format | Resolution | Default frame rate |
|---|---:|---:|
| Reels / Shorts | 1080 × 1920 | 30 fps |
| Instagram portrait | 1080 × 1350 | 30 fps |
| Landscape | 1920 × 1080 | 30 fps |

Match source frame rate where appropriate and follow the destination platform's current requirements.

## Repository structure

- `SKILL.md` — master agent instructions
- `CONFIG.md` — default settings and quality gates
- `modules/` — specialist editing modules
- `presets/` — creative profiles
- `workflows/` — repeatable production workflows
- `examples/` — sample edit decision list and transcript schema

## Design philosophy

Professional editing is not the maximum number of effects. Every cut, animation, title, colour choice and sound cue should improve clarity, rhythm, emotion or storytelling.
