# NEXORA DAILYKIT

> A lightweight Windows desktop calendar and daily planning app for Windows 10 and Windows 11.

**Version:** 1.0.0 — Stable Release

[🇬🇧 English](README.md) | [🇮🇷 فارسی](README.fa.md) | [🇨🇳 简体中文](README.zh-CN.md) | [🇯🇵 日本語](README.ja.md) | [🇰🇷 한국어](README.ko.md) | [🇩🇪 Deutsch](README.de.md) | [🇫🇷 Français](README.fr.md) | [🇷🇺 Русский](README.ru.md)

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


## Installation

1. Download the latest Windows installer from Releases.
2. Run the installer.
3. Complete the Windows installation steps.
4. Launch **NEXORA DAILYKIT**.
5. First launch uses **English** and the **Gregorian** calendar.
6. Open **Settings** to customize the application.


---

# 📖 Complete User Guide

## 1. First Launch

Default startup uses English, Gregorian calendar, the widget near the lower-left area above the Windows taskbar, default widget opacity, and local storage.

<img width="358" height="531" alt="image" src="https://github.com/user-attachments/assets/73e9ac0c-961c-43a4-8993-eceef0728962" />

## 2. Main Interface

### Calendar
Displays the selected calendar and allows navigation between dates and months.

### Settings
Contains Appearance, Calendar, Widget, Reminders, Backup, Language, and About settings.

The application name is always **NEXORA DAILYKIT**.


## 3. Calendar

You can move between months, select a date, return to Today, change the primary calendar, show additional calendars, and open the selected day's information.

The selected date receives the main highlight. Today remains visible and becomes a lighter highlight when another date is selected.

<img width="350" height="422" alt="image" src="https://github.com/user-attachments/assets/55eb3451-893d-4cfc-8bf8-0120f4508026" />

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

<img width="579" height="500" alt="image" src="https://github.com/user-attachments/assets/d82d7d7f-c34c-434c-929d-6c845c01cf03" />

## 6. Daily Information

Selecting a date opens Daily Information.

### Tasks
Actionable items for the selected date.

### Journal
Free-form notes associated with the selected date.

<img width="410" height="552" alt="image" src="https://github.com/user-attachments/assets/3a5810b4-b162-431c-a6c4-d0955ab857f5" />

## 7. Tasks

A task can contain a title, optional description, optional time, and completion state.

You can create, edit, complete, reopen, and delete tasks.

To create one: select a date → open Daily Information → choose **New Task** → enter the title → optionally add a description and time → save.

A task with a time can be handled by the reminder engine.

<img width="1048" height="536" alt="image" src="https://github.com/user-attachments/assets/6524e2ae-b90f-4cfc-bc4f-0b06dd2e94f4" />

## 8. Journal

Journal is for date-based notes rather than actionable tasks. It supports automatic and manual saving.

Use it for daily notes, ideas, personal records, meeting notes, or short reflections.

<img width="362" height="532" alt="image" src="https://github.com/user-attachments/assets/5f3634ee-b3f2-48b9-89d0-738a5962ba66" />

## 9. Reminders

A task can have a reminder time. When due, the application can show a Windows notification, play the configured sound, offer Snooze, or allow Dismiss.

Scheduled reminders are reloaded when the application starts.

Windows notification settings and permissions also affect notifications.

<img width="333" height="112" alt="image" src="https://github.com/user-attachments/assets/e0b825c4-8583-466a-b69a-742c02d012f8" />

## 10. Reminder Settings

Open **Settings → Reminders**.

You can configure reminder sound, default/custom sound, Test, Stop Sound, volume, and default Snooze duration.

Use **Test** to preview a sound and **Stop Sound** to stop the test.

<img width="500" height="386" alt="image" src="https://github.com/user-attachments/assets/8241f326-8dc4-4922-8090-92aa53ba9d6e" />

## 11. Desktop Widget

By default, the widget is near the lower-left of the screen above the taskbar.

It can be moved, resized, shown/hidden, configured to start with Windows, configured to close to the System Tray, and reset to its position.

The desktop layer sits **behind normal windows**. It is not Always-on-top and does not steal focus. Multi-monitor position recovery is supported.

<img width="338" height="468" alt="image" src="https://github.com/user-attachments/assets/57cf1f70-3e17-447c-a6fe-50f8f5bffb1e" />

## 12. Widget Opacity

Opacity can be set from **20% to 100%** and applies to the widget.

During calendar interaction the widget temporarily becomes 100% visible for readability, then returns to the configured opacity. The saved opacity value is not changed.

<img width="465" height="396" alt="image" src="https://github.com/user-attachments/assets/bb95d4e5-0c84-4a29-b001-73b71b0beb16" />

## 13. System Tray

Closing the widget normally does not terminate the application. The application can remain active in the Windows System Tray.

The Tray menu can show the widget, hide it, or **Exit**. Only Exit terminates the application.


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

<img width="475" height="186" alt="image" src="https://github.com/user-attachments/assets/fc64dc34-7705-4d7a-8bb9-52e88f1ef861" />

## 15. Appearance

Open **Settings → Appearance**.

Options include Theme, Accent color, Calendar color, Task color, Journal color, Reminder color, Background, Primary/Secondary text, Font size/scale, and Density.

Light, dark, and system themes are supported. Use Preview to inspect changes and Reset to restore appearance defaults.

<img width="642" height="845" alt="image" src="https://github.com/user-attachments/assets/cd649b21-754c-4370-bd47-a3f590bf4842" />

## 16. Language

Open **Settings → Language**.

The application currently supports:

- English
- Persian

English is the first-install default. Persian uses RTL where appropriate, while URLs and wallet addresses remain LTR.

The eight README languages do not mean that the application UI supports eight languages.

<img width="387" height="287" alt="image" src="https://github.com/user-attachments/assets/83e789e4-61c5-4361-9ab2-8ba7fdd887f7" />

## 17. Backup & Restore

Open **Settings → Backup**.

You can configure automatic backup, frequency, location, retention, manual backup, and Restore.

Automatic frequencies are Daily, Weekly, and On exit.

Default location:

`Documents/Nexora DailyKit/Backups`

**Open Folder** opens the currently configured backup location. **Backup Now** creates an immediate backup.

<img width="579" height="454" alt="image" src="https://github.com/user-attachments/assets/122c29e4-417a-499d-a36b-d75cdeda08ec" />

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
