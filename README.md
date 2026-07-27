# MadsIT

### A softer landing for Windows administrators moving to Debian

Debian already has powerful, dependable administration tools. Many of them
start at a command prompt, though, and that can make the move from Windows feel
larger than it needs to be—even for experienced administrators.

The **Shift** suite adds small, native-feeling KDE launchers around those proven
tools. The goal is not to replace the command line. It is to make the first step
comfortable, expose safe defaults, and help people learn what is underneath as
they go.

## The Shift suite

| Tool | Familiar starting point | Debian engine |
| --- | --- | --- |
| [RDPShift](https://github.com/MadsIT-com/rdp-shift) | An `mstsc`-style “enter a computer and connect” workflow | [FreeRDP](https://www.freerdp.com/) |
| [SSHShift](https://github.com/MadsIT-com/ssh-shift) | `Windows key → PuTTY → Enter → host → Enter`, made native to KDE | [OpenSSH](https://www.openssh.com/) + Konsole |

Both projects currently target **Debian 13, KDE Plasma, and Wayland**.

## What “thin wrapper” means here

- Use Debian's established tools instead of reimplementing their protocols.
- Offer workflows that feel recognizable to Windows administrators.
- Keep secure, conservative defaults visible and understandable.
- Avoid inventories of server names, saved credentials, and unnecessary state.
- Put advanced capabilities within reach without crowding the first screen.
- Show the equivalent command where useful, so the wrapper teaches the tool.
- Never create lock-in: users should be able to graduate straight to the CLI.

## Why I am building this

I learned Debian's tools while administering servers over SSH. When it was time
to move my own daily-driver laptop from Windows to Debian, I found that the
underlying tools were excellent but some familiar, focused entry points were
missing.

Modern AI makes it practical to build and review small interfaces like these.
If a wrapper solves a real problem for me, sharing it may make the same move
easier for the next administrator too.

The suite is young, deliberately small, and built in public. Compatibility
reports, careful security review, accessibility feedback, and focused fixes are
welcome in each project's repository.
