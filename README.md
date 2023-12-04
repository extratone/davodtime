# MMddYYYY-HHmmss
Updated `12042023-100354`

- [**GitHub Repository**](https://github.com/extratone/davodtime)
- [Gist](https://gist.github.com/extratone/0540718c80734fd6ec7e2c974c7a9e70)
- [The Psalms’ Wiki Entry](https://github.com/extratone/bilge/wiki/DavodTime)
- [WTF](https://davidblue.wtf/drafts/A09BB9CE-430D-4DDF-8FB6-F17912FB1E26.html)
- [Local](shareddocuments:///private/var/mobile/Library/Mobile%20Documents/com~apple~CloudDocs/Written/A09BB9CE-430D-4DDF-8FB6-F17912FB1E26.md)
- [Draft](drafts://open?uuid=A09BB9CE-430D-4DDF-8FB6-F17912FB1E26)

---

`MMddYYYY-HHmmss`

I decided to create my own standardized time format because I was getting tired of getting confused by my own timestamps.

Ex:
`01152022-135757`
`05212022-042625`

<script src="https://gist.github.com/extratone/0540718c80734fd6ec7e2c974c7a9e70.js"></script>

---

## Siri Shortcut
- [#3](https://github.com/extratone/davodtime/issues/3)

- [**RoutineHub Page**](https://routinehub.co/shortcut/10872)
- [iCloud Share URL](https://www.icloud.com/shortcuts/cc71704b3a9a4f98949b59fdeba49e24)
- [Raw Repository File](https://github.com/extratone/davodtime/blob/main/shortcut/DavodTime.shortcut)
- [iCloud Share URL](https://www.icloud.com/shortcuts/5a4ebd4ed057415b8915c535951c1059) - *Version 1.0*

### Source

![Showcuts Source](shortcuts/Showcuts.png)

- [**GitHub Pages**](https://extratone.github.io/davodtime/shortcut/DavodTime.html) (HTML)
- [JSON](https://github.com/extratone/davodtime/blob/main/shortcut/DavodTime.json)
- [Showcuts](https://showcuts.app/share/view/cc71704b3a9a4f98949b59fdeba49e24)

```jelly
date() >> date
formatDate(date: "${Date}", dStyle: Custom, custom: "MMddYYYY-HHmmss") >> formatDate
var DavodTime = Formatted Date
setClipboard(variable: Formatted Date) >> setClipboard
```

### WordPress Date/Time
- [#4](https://github.com/extratone/davodtime/issues/3)

As specified in [this documentation](https://wordpress.org/documentation/article/customize-date-and-time-format), dtime is represented in WordPress applications as:

`m/d/Y-H/i/s`

## ToDo

Since I’m in the process of learning JavaScript, I think it would be interesting to attempt the creation of a live clock webpage displaying the current, *timezone-adjusted* time in DavodTime.