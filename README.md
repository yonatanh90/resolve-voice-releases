# Resolve Voice - releases

This repository only distributes Resolve Voice, a Hebrew voice-editing assistant for DaVinci Resolve: signed
installers and the update feeds the app reads. It contains no source code.

- **Install:** open [Releases](../../releases), download `ResolveVoice_Setup_<version>.exe` and run it. It installs
  for the current Windows user (no administrator rights, no Python needed).
- **Updates:** the installed app checks `appcast-beta.xml` / `appcast-stable.xml` (assets of the `feed` release -
  please do not delete it) and installs an update only after you press "Update now" and only when the installer's
  Ed25519 signature matches the key built into the app (key id `48e38e40a6ed08a8`).
- **Windows warning:** the installer is not yet signed with a code-signing certificate, so Windows may show
  "Windows protected your PC". Choose *More info* -> *Run anyway*.

## בעברית

המאגר הזה משמש רק להפצת Resolve Voice - עוזר עריכה קולי בעברית ל-DaVinci Resolve: קובצי התקנה חתומים וקובצי העדכון
שהתוכנה קוראת. אין בו קוד מקור.

- **התקנה:** ב-[Releases](../../releases) הורד את `ResolveVoice_Setup_<גרסה>.exe` והפעל אותו. ההתקנה למשתמש הנוכחי בלבד,
  בלי הרשאות מנהל ובלי פייתון.
- **עדכונים:** התוכנה מציגה הודעה כשיש גרסה חדשה, ומתקינה רק אחרי שלוחצים "עדכן עכשיו" ורק אם החתימה הדיגיטלית תקינה.
- **אזהרת Windows:** אם מופיע "Windows protected your PC" - לחץ *More info* ואז *Run anyway*.
