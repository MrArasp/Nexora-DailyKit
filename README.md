# NEXORA DAILYKIT

> A lightweight Windows desktop calendar and daily planning app for Windows 10 and Windows 11.

**Version:** 1.0.0 — Stable Release

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · [🇨🇳 简体中文](README.zh-CN.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇩🇪 Deutsch](README.de.md) · [🇫🇷 Français](README.fr.md) · [🇷🇺 Русский](README.ru.md)

---

## About

NEXORA DAILYKIT is a local Windows desktop calendar and daily-planning application for dates, tasks, journal notes, reminders, and calendar information.

It supports Gregorian, Persian/Jalali, and Islamic calendars. The application UI currently supports **English and Persian only**; the other README languages are documentation languages.

Everything needed for normal calendar, task, journal, reminder, and backup use is stored locally. No online account or cloud service is required.

---

## Features

- Gregorian, Persian/Jalali, and Islamic calendars
- Daily information for the selected date
- Tasks with optional descriptions and times
- Date-based Journal
- Windows reminder notifications
- Custom reminder sounds, volume, snooze, and dismiss
- Desktop-layer calendar widget
- Adjustable widget opacity
- System Tray operation
- Light, dark, and system themes
- Accent and separate calendar/task/journal/reminder colors
- Calendar and widget customization
- Automatic and manual backup
- Restore with a safety backup
- English/Persian UI with LTR/RTL support
- Local data storage
- About Us with NEXORA links and donation information

## System Requirements

- Windows 10 or Windows 11
- A Windows user account allowed to install and run desktop applications
- Internet is not required for normal calendar, task, journal, reminder, or backup operation

## Download

Download the official Windows release from the **Releases** section of the public GitHub repository.

The public repository is for releases and user documentation. Source code is maintained separately.

> **Screenshot placeholder:** Add the GitHub Releases screenshot here.

## Installation

1. Download the latest Windows installer from Releases.
2. Run the installer.
3. Complete the Windows installation steps.
4. Launch **NEXORA DAILYKIT**.
5. First launch uses **English** and the **Gregorian** calendar.
6. Open **Settings** to customize the application.

> **Screenshot placeholder:** Add the installation/first-launch screenshot here.

---

# 📖 Complete User Guide

## 1. First Launch

Default startup uses English, Gregorian calendar, the widget near the lower-left area above the Windows taskbar, default widget opacity, and local storage.

## 2. Main Interface

### Calendar
Displays the selected calendar and allows navigation between dates and months.

### Settings
Contains Appearance, Calendar, Widget, Reminders, Backup, Language, and About settings.

### About Us
Contains NEXORA information, project links, donation information, and wallet-copy functionality.

The application name is always **NEXORA DAILYKIT**.

> **Screenshot placeholder:** Add the main interface screenshot here.

## 3. Calendar

You can move between months, select a date, return to Today, change the primary calendar, show additional calendars, and open the selected day's information.

The selected date receives the main highlight. Today remains visible and becomes a lighter highlight when another date is selected.

> **Screenshot placeholder:** Add a calendar screenshot here.

## 4. Calendar Systems

### Gregorian
The standard international calendar.

### Persian / Jalali
The Persian Solar Hijri calendar.

### Islamic
The Islamic Hijri calendar.

Islamic dates use supported Umm al-Qura calendar data and can differ by about one day from calendars based on local moon sighting. Jalali uses the application's supported astronomical Solar Hijri calculation.

## 5. Calendar Display Settings

Open **Settings → Calendar**.

Available settings include primary, secondary, and third calendar; date format; number format; and first day of week.

First day can be automatic, Saturday, Sunday, or Monday.

In the Persian interface, date numbers remain Western/English numerals.

> **Screenshot placeholder:** Add Calendar Settings here.

## 6. Daily Information

Selecting a date opens Daily Information.

### Tasks
Actionable items for the selected date.

### Journal
Free-form notes associated with the selected date.

> **Screenshot placeholder:** Add Daily Information here.

## 7. Tasks

A task can contain a title, optional description, optional time, and completion state.

You can create, edit, complete, reopen, and delete tasks.

To create one: select a date → open Daily Information → choose **New Task** → enter the title → optionally add a description and time → save.

A task with a time can be handled by the reminder engine.

> **Screenshot placeholder:** Add the task editor screenshot here.

## 8. Journal

Journal is for date-based notes rather than actionable tasks. It supports automatic and manual saving.

Use it for daily notes, ideas, personal records, meeting notes, or short reflections.

> **Screenshot placeholder:** Add the Journal screenshot here.

## 9. Reminders

A task can have a reminder time. When due, the application can show a Windows notification, play the configured sound, offer Snooze, or allow Dismiss.

Scheduled reminders are reloaded when the application starts.

Windows notification settings and permissions also affect notifications.

> **Screenshot placeholder:** Add a reminder notification screenshot here.

## 10. Reminder Settings

Open **Settings → Reminders**.

You can configure reminder sound, default/custom sound, Test, Stop Sound, volume, and default Snooze duration.

Use **Test** to preview a sound and **Stop Sound** to stop the test.

> **Screenshot placeholder:** Add Reminder Settings here.

## 11. Desktop Widget

By default, the widget is near the lower-left of the screen above the taskbar.

It can be moved, resized, shown/hidden, configured to start with Windows, configured to close to the System Tray, and reset to its position.

The desktop layer sits **behind normal windows**. It is not Always-on-top and does not steal focus. Multi-monitor position recovery is supported.

> **Screenshot placeholder:** Add a desktop widget screenshot here.

## 12. Widget Opacity

Opacity can be set from **20% to 100%** and applies to the widget.

During calendar interaction the widget temporarily becomes 100% visible for readability, then returns to the configured opacity. The saved opacity value is not changed.

> **Screenshot placeholder:** Add opacity settings here.

## 13. System Tray

Closing the widget normally does not terminate the application. The application can remain active in the Windows System Tray.

The Tray menu can show the widget, hide it, or **Exit**. Only Exit terminates the application.

> **Screenshot placeholder:** Add a System Tray screenshot here.

## 14. Settings

Open **Settings** from the top navigation.

Sections:

- Appearance
- Calendar
- Widget
- Reminders
- Backup
- Language
- About

> **Screenshot placeholder:** Add the Settings overview here.

## 15. Appearance

Open **Settings → Appearance**.

Options include Theme, Accent color, Calendar color, Task color, Journal color, Reminder color, Background, Primary/Secondary text, Font size/scale, and Density.

Light, dark, and system themes are supported. Use Preview to inspect changes and Reset to restore appearance defaults.

> **Screenshot placeholder:** Add Appearance Settings here.

## 16. Language

Open **Settings → Language**.

The application currently supports:

- English
- Persian

English is the first-install default. Persian uses RTL where appropriate, while URLs and wallet addresses remain LTR.

The eight README languages do not mean that the application UI supports eight languages.

> **Screenshot placeholder:** Add Language Settings here.

## 17. Backup & Restore

Open **Settings → Backup**.

You can configure automatic backup, frequency, location, retention, manual backup, and Restore.

Automatic frequencies are Daily, Weekly, and On exit.

Default location:

`Documents/Nexora DailyKit/Backups`

**Open Folder** opens the currently configured backup location. **Backup Now** creates an immediate backup.

> **Screenshot placeholder:** Add Backup Settings here.

## 18. Restore

Before restoring, the application creates a safety backup of the current data.

Recommended workflow:

1. Open Settings → Backup.
2. Confirm the backup location.
3. Select Restore.
4. Choose the backup.
5. Confirm.
6. Wait for completion.
7. Reopen/refresh if requested.

Do not interrupt the application during restore.

## 19. About Us

Official links:

- Telegram: https://t.me/nexora_labs_2026
- GitHub: https://github.com/MrArasp
- Donations: https://donito.me/nexora_labs

**Network:** EVM / USDT BEP20

**Wallet:**
`0x5Bcdef9E0d9030e5cAa73e1D50aC71257EC8304e`

The wallet address is provided for copying.

> **Screenshot placeholder:** Add About Us here.

## 20. Data Storage & Privacy

NEXORA DAILYKIT is a local desktop application.

Calendar data, tasks, Journal entries, reminders, settings, and backups are stored locally.

Normal use requires no NEXORA account, cloud account, subscription, or online synchronization.

Internet is used only when you intentionally open an external link such as Telegram, GitHub, or the donation page.

> **Important:** Local data security also depends on the security of the Windows account and storage folders.

## 21. Troubleshooting

**Widget disappeared:** Check the System Tray and show it.

**Wrong widget position:** Use Settings → Widget → Reset Position.

**Reminder missing:** Check the task time, saved task, application/Tray status, Windows notifications, and Reminder settings.

**No reminder sound:** Check Windows volume, Reminder volume, selected sound, and use Test Sound.

**Wrong backup folder:** Check Settings → Backup and use Open Folder.

**Persian display:** Set Language to Persian.

**Islamic date differs by one day:** Different calculation methods, especially Umm al-Qura versus local moon sighting, can cause this difference.

## 22. Technical Calendar Note

Jalali uses the application's supported astronomical Solar Hijri calculation.

Islamic uses Umm al-Qura data and is not a local moon-sighting calendar.

Some Islamic dates can therefore differ by about one day from another calendar.

## 23. Version

**NEXORA DAILYKIT 1.0.0**

This documentation describes the stable 1.0.0 release.

Use the public repository for the latest installer and Release Notes.

## Feedback

- Telegram: https://t.me/nexora_labs_2026
- GitHub: https://github.com/MrArasp

When reporting a problem, include the application version and a clear description.

## Support NEXORA

https://donito.me/nexora_labs

**EVM / USDT BEP20**

`0x5Bcdef9E0d9030e5cAa73e1D50aC71257EC8304e`

## Copyright

© NEXORA. All rights reserved.

NEXORA DAILYKIT is distributed as a Windows desktop application. Refer to the public repository and Release package for applicable release and licensing information.
