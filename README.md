<p align="center">
  <img src="docs/assets/rika-hero.svg" width="846" alt="rika! — a home for your beautifully tangled mind. A local-first workspace for connected ideas.">
</p>

<p align="center">
  Notes become connections. Connections become something you can build.<br>
  A local-first desktop workspace for your notes, documents, study and plans.
</p>

<p align="center">
  <a href="https://github.com/ZacharySF/rika/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/ZacharySF/rika?style=flat-square&label=release&labelColor=000&color=333"></a>
  <img alt="Linux x86_64" src="https://img.shields.io/badge/linux-x86__64-333?style=flat-square&labelColor=000">
  <img alt="AppImage and .deb" src="https://img.shields.io/badge/AppImage%20%2B%20.deb-333?style=flat-square&labelColor=000">
  <img alt="Signed updates" src="https://img.shields.io/badge/updates-signed-333?style=flat-square&labelColor=000">
</p>

<p align="center">
  <b><a href="https://github.com/ZacharySF/rika/releases/latest">Download for Linux ↗</a></b>
  &nbsp; / &nbsp; <a href="#install">Install</a>
  &nbsp; / &nbsp; <a href="#a-look-around">A look around</a><br>
  <sub>Local-first · No account needed · One SQLite workspace on your machine</sub>
</p>

<p align="center">
  <a href="#at-a-glance">At a glance</a> ·
  <a href="#install">Install</a> ·
  <a href="#updates-and-your-data">Updates and your data</a> ·
  <a href="#a-look-around">A look around</a> ·
  <a href="#keys-worth-knowing">Keys</a> ·
  <a href="#about-this-repository">About</a>
</p>

<br>

<p align="center"><b>A little less scattered. A lot more connected.</b></p>

<p align="center">
  <img src="docs/screenshots/home.jpg" width="100%" alt="The rika! home dashboard on black: today's schedule with a line for now, a quick note and a focus timer on the left; up next and an agent session in the middle; and the Rika panel on the right with three drafted replies waiting for Send.">
</p>
<p align="center"><sub>Home: today, what's next, and Rika on the right with your replies already drafted.</sub></p>

<br>

## At a glance

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Write</b><br>
      <sub>Blocks, <code>[[wiki]]</code> links and <code>((block))</code> references. Documents, PDFs, canvases, mind maps and floating quick notes.</sub>
    </td>
    <td width="33%" valign="top">
      <b>Plan</b><br>
      <sub>A calendar, tasks and goals, with flashcards and study beside the material you're learning.</sub>
    </td>
    <td width="33%" valign="top">
      <b>See</b><br>
      <sub>The Brain: every record and every edit as a point on a 3D brain or a flat 2D map.</sub>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <b>Delegate</b><br>
      <sub>Rika reads what changed, drafts the replies and keeps an eye on your coding agents. You press Send.</sub>
    </td>
    <td width="33%" valign="top">
      <b>Shape</b><br>
      <sub>Rearrange any page, start home from eighteen templates, and pick Black or seventeen other themes.</sub>
    </td>
    <td width="33%" valign="top">
      <b>Grow</b><br>
      <sub>Switch modules on and off. Heavy parts download as signed packs only when you ask for them.</sub>
    </td>
  </tr>
</table>

<br>

## Install

1. **[Download the latest release.](https://github.com/ZacharySF/rika/releases/latest)**
2. Install the `.deb` with your software installer, or run the AppImage.
3. Open rika! from your application launcher and choose **Start locally**.

<p align="center">
  <img src="docs/screenshots/welcome.jpg" width="62%" alt="The rika! welcome card: a glowing neural-network brain above the words 'Welcome to rika!', with Continue with Google and Start locally buttons">
</p>
<p align="center"><sub>First launch: one button to start locally. No account needed.</sub></p>

### Which file?

| Your system | Download | How |
| --- | --- | --- |
| Ubuntu 22.04+ and compatible Debian-based desktops | `kitty_<version>_amd64.deb` | Open it in your software installer and approve. It brings its own dependencies and a **rika!** menu entry. |
| Other Linux desktops (x86_64, glibc 2.35+) | `kitty_<version>_amd64.AppImage` | Keep it in a writable folder such as `~/Applications`, allow it to run as a program, and double-click it. Needs FUSE (`libfuse2` on Ubuntu 22.04). |
| NixOS | the AppImage | Run it through `appimage-run`, which keeps signed self-updates working. |

The files still carry the project's earlier name, `kitty`; the app installs as
**rika! Workspace** (package `rika-workspace`) and has nothing to do with the
`kitty` terminal. These installers don't cover ARM, Windows or macOS.

<br>

## Updates and your data

- **Updates are signed.** Use **Check for updates** in the app or the tray menu,
  then **Download update** and **Install and restart**. The app checks every
  installer against the key built into it before it touches anything.
- **Your workspace lives apart from the app.** Notes, databases and settings stay
  in `~/.local/share/kitty/workspace` by default and are reused in place. Updating, replacing
  or uninstalling the app leaves them alone, so back them up like any personal data.
- **Modules download only when you ask.** The Brain, Themes, Voice, Math and
  others come as packs from the same release, checked against a signed list and
  their SHA-256 before they're used.
- **No account needed.** Choose **Start locally** and your workspace is one
  SQLite database on your machine; Google sign-in is optional.

<br>

## A look around

### Follow the thread

Every record and every edit becomes a glowing point in the **Brain**: a
neural-network map of everything you've written, studied and planned. Prefer
flat ground? Switch to the **2D** map.

<img src="docs/screenshots/brain.jpg" width="100%" alt="The Brain view: a glowing neural-network brain threaded in red, orange, yellow, green and blue, above a legend counting calendar, applications, jobs, reminders and flashcards.">

### Give it somewhere to go

Put the next step on your calendar: one quiet row of controls, a line for now,
and the day you picked beside it.

<img src="docs/screenshots/calendar.jpg" width="100%" alt="The calendar's week view: the Calendar title as a menu, one row with the range, Today, and Day, Week, Month, Agenda, Year and Plan; a hairline grid of grey events, today's date in a filled circle and a line marking the time now; a small month, the week's hours and the selected day's agenda on the right.">

### Someone to hand the loose ends to

Rika reads what changed overnight and tells you in a few lines. She drafts the
replies; **you** press Send. Her own page shows the coding agents working for you,
and **Ctrl + R** docks her beside any page.

<img src="docs/screenshots/rika.jpg" width="100%" alt="Rika's page: the conversation with three drafted email replies on the left, and on the right four coding agents with their task, context, tokens, cost and state.">

### Looking for work? Three tabs, one bar.

Turn on ApplyAI and **Career** keeps the search in one place: **Find**, **Saved**
and **Track**. Tick the jobs and press Fill: rika! fills in the forms and stops
before Submit, every time.

<img src="docs/screenshots/jobs.jpg" width="100%" alt="Career's Find jobs page: Find, Saved and Track across the top with More on the right, Ready to apply beside Progress and Add a job link, a list of ranked jobs with two ticked, and a small bar at the bottom offering Save, Change, Check and Fill in 2 forms.">

### Your desk, not ours

Press **Ctrl + Shift + Space** on any page. Drag a block where you want it, pull
an edge to resize it, and open **Widgets** to drag in a clock, a quick note or
your goals.

<img src="docs/screenshots/edit.jpg" width="100%" alt="Edit mode on the Find jobs page: a clock and a quick note dragged onto the page, a dashed outline with a grip around the quick note, and a small bar at the bottom with Widgets, Parent, Remove widget, Reset page and Done.">

### Black by default. Loud when you want it.

rika! opens in **Black**: white type, hairlines, nothing glowing. Turn Themes on
for seventeen more, and press **Ctrl + Y** to slide through them live. Turn
Animations on if you want pages to turn instead of blink.

<p align="center">
  <img src="docs/screenshots/kitty.jpg" width="49%" alt="The Kitty theme: the same home in heavy capitals and tube yellow over a green, grainy film still of a corridor, with the page's name running down the edge.">
  <img src="docs/screenshots/themes.jpg" width="49%" alt="The theme carousel: five theme cards in a row over a blurred, blossom-pink preview of the page, with Blossom raised in the middle and the hint 'Ctrl + Y next · Enter keep · Esc undo' beneath.">
</p>
<p align="center"><sub>Left: the Kitty theme. Right: Ctrl + Y, previewing Blossom.</sub></p>

### Only the parts you want

Keep the workspace, add a terminal when you're building, turn on ApplyAI when
you're looking for work, or download the Brain, Themes and Animations. Disabled
modules disappear; their data stays.

<p align="center">
  <img src="docs/screenshots/modules.jpg" width="72%" alt="Settings › Modules: switches for ApplyAI, Workspace, Math, LearnHarness, Terminal, Voice, Brain, Themes, Animations and Icons, each with one line saying what it does.">
</p>

<p align="center"><sub>Screenshots use a demo workspace with synthetic data.</sub></p>

<br>

## Keys worth knowing

| Keys | What they do |
| --- | --- |
| <kbd>Ctrl</kbd> <kbd>Space</kbd> or <kbd>Ctrl</kbd> <kbd>K</kbd> | Search commands, sections and jobs |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>Space</kbd> | Edit the page you're on |
| <kbd>Ctrl</kbd> <kbd>R</kbd> | Rika beside the page; again or Esc to close |
| <kbd>Ctrl</kbd> <kbd>J</kbd> | Ask Rika from anywhere but a terminal |
| <kbd>Ctrl</kbd> <kbd>O</kbd> | Every open tab as a card: arrows or 1–9, Enter to open |
| <kbd>Ctrl</kbd> <kbd>Tab</kbd> · <kbd>Ctrl</kbd> <kbd>T</kbd> · <kbd>Ctrl</kbd> <kbd>W</kbd> | Next tab · new tab · close tab |
| <kbd>Ctrl</kbd> <kbd>Y</kbd> | Slide through your themes live |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>F</kbd> | Fill the window with the focused panel |
| <kbd>?</kbd> | Every shortcut for the screen you're on |

<br>

## About this repository

This repository holds the official installers, module packs and signed update
metadata. The application source is maintained in a separate private repository.
The LearnHarness pack includes its corresponding source and licences.

**Never share your workspace, credentials, resumes or private database in an issue.**

<sub>The wordmark uses <a href="https://fraunces.undercase.xyz">Fraunces</a> by Undercase Type, embedded under the <a href="docs/assets/OFL-Fraunces.txt">SIL Open Font License</a>.</sub>
