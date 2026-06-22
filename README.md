# .NET MAUI News

Monthly .NET MAUI news briefings for senior MAUI developer discussions.

The repository contains two types of files:

```text
maui-news/
  YYYY-MM.md    Detailed monthly Markdown briefing

slides/
  YYYY-MM.md    Concise Slidev presentation for meetings
```

## View a Slidev presentation

Use Slidev directly with `npx`:

```bash
npx @slidev/cli slides/2026-06.md
```

To open the browser automatically:

```bash
npx @slidev/cli slides/2026-06.md --open
```

Slidev usually starts at:

```text
http://localhost:3030
```

Presenter mode is available at:

```text
http://localhost:3030/presenter
```

## View another month

Replace the file name with the month you want to present:

```bash
npx @slidev/cli slides/YYYY-MM.md --open
```

Example:

```bash
npx @slidev/cli slides/2026-07.md --open
```

## Basic presentation controls

```text
Space / Arrow Right   Next slide
Arrow Left            Previous slide
f                     Fullscreen
o                     Overview
```

## Report vs slides

Use the files like this:

- `maui-news/YYYY-MM.md` is the full reference document.
- `slides/YYYY-MM.md` is the screen-share presentation.

The slides are intentionally shorter and should be used for the verbal meeting. The full report contains the detailed source-backed briefing.
