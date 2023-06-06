# Obsidian ICS Plugin

This is a plugin for [Obsidian](https://obsidian.md). It adds events from google calendar ics URLs to your Daily Note on demand.

This only works with the Daily Note or [Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes) plugins: specifically it gets the date to search for events during from the currently open daily note.

## Development state

Alas, work limits us to only a couple of apps for note taking and Obsidian isn't on the approved list. :/ As such I don't get to use it nor this plugin much. 

It mostly works though I've seen it occasionally [miss some recurring events](https://github.com/muness/obsidian-ics/issues/36) and someone has reported a [timezone issue](https://github.com/muness/obsidian-ics/issues/37) though I haven't seen it. Give that I don't use it often, it's unlikely that I'll get to fix these issues.

I welcome a fork and will update this README to point to it if someone wants to take over.

## Installation

Manual Installation
1. Download the latest `obsidian-ics-[version].zip` file from [releases](https://github.com/muness/obsidian-ics/releases).
2. Unpack the file. It should create a `obsidian-ics` folder.
3. Place the folder in your .obsidian/plugins directory
4. Reload plugins
5. Activate the `ICS` plugin

## Usage

1. From Google Calendar, look for the calendar in the left sidebar click the vertical … menu, Settings and Sharing, Integrate calendar, Copy the Secret address in iCal format
2. Enter that URL into settings with a calendar name
3. Go to a daily note, use the `ICS: Import events` command

![Settings Screenshot](https://github.com/muness/obsidian-ics/blob/master/docs/2021-08-11-22-18-21.png?raw=true)

## Support

If you want to support my work, you can [buy me a coffee](https://www.buymeacoffee.com/muness)

## Contributions

- [DST fix](https://github.com/muness/obsidian-ics/pull/17) from @zakkolar
- [Readme improvements and release script cleanup](https://github.com/muness/obsidian-ics/pull/22) from @fcwheat
- [Export event getter function](https://github.com/muness/obsidian-ics/pull/33) @bvolkmer


