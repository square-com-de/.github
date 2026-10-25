# square | com

**Connect everyday devices to your smart home.**

Practical, independent integrations for Loxone: bring your Hue lights under control or choose which Porsche Connect measurements your home receives.

[Hue2Lox](#hue2lox) · [PLX](#plx) · [Website](https://square-com.de/)

---

## Hue2Lox

<p><img src="https://raw.githubusercontent.com/square-com-de/hue2lox/main/web/hue2lox-logo.png" width="260" alt="Hue2Lox logo with its octopus mascot"></p>

**Bring Philips Hue lights and scenes into Loxone with ready-made commands and XML templates.**

[**Quick start**](https://github.com/square-com-de/hue2lox/blob/main/INSTALL.md) · [Documentation](https://github.com/square-com-de/hue2lox/blob/main/docs/MANUAL.md) · [Releases](https://github.com/square-com-de/hue2lox/releases) · [Help & feedback](https://github.com/square-com-de/hue2lox/issues/new/choose) · [Repository](https://github.com/square-com-de/hue2lox)

[![Hue2Lox command fields for Loxone](https://raw.githubusercontent.com/square-com-de/hue2lox/main/web/tutorial-commands.png)](https://github.com/square-com-de/hue2lox/blob/main/docs/TUTORIAL.md)

*Real application example with test data and German labels; the current layout is more compact.*

- **Multiple bridges, one view** — discover lights and scenes across your Hue Bridges.
- **Controls your lights support** — switching, dimming, RGB and white temperature, depending on the device.
- **Ready for Loxone Config** — copy HTTP commands or export selected devices as XML.
- **Scenes on and off** — recall a scene and switch off its assigned group.
- **Local and bilingual** — English/German web interface; no cloud account needed for normal operation.

**Preferred setup:** Docker Compose in a Linux VM. Installation, TLS, updates and supported alternatives stay in the [project guides](https://github.com/square-com-de/hue2lox/blob/main/docs/CONTAINER-SETUP.md).

---

## PLX

<p><img src="https://raw.githubusercontent.com/square-com-de/plx/main/icons/icon.svg" width="112" alt="PLX project logo"></p>

**See your Porsche Connect status and send only the measurements you select to Loxone via MQTT.**

[**Quick start**](https://github.com/square-com-de/plx/blob/main/INSTALL.md) · [Documentation](https://github.com/square-com-de/plx/blob/main/docs/MANUAL.md) · [Preview releases](https://github.com/square-com-de/plx/releases) · [Help & feedback](https://github.com/square-com-de/plx/issues/new/choose) · [Repository](https://github.com/square-com-de/plx)

[![PLX dashboard showing example vehicle measurements](https://raw.githubusercontent.com/square-com-de/plx/main/docs/preview/public-overview.png)](https://github.com/square-com-de/plx/blob/main/docs/MANUAL.md)

*Dashboard example with simulated measurements. The vehicle illustration comes from Porsche Connect; available data depends on your vehicle and contract.*

- **A compact vehicle dashboard** — view reported battery level, range, tire pressure and measurement age.
- **Choose what MQTT sends** — select the values your smart home receives.
- **Find useful measurements** — search and filter the parameters your vehicle reports.
- **Loxone mapping tools** — export selected numeric inputs as XML or CSV.
- **Two languages, two installation paths** — English/German interface; Docker Compose preferred, LoxBerry 4 plugin as an alternative.

**Preview — not a stable release.** A compatible Porsche Connect cloud account is required. PLX reads status only; it does not remote-control or wake your car. See [release status and limits](https://github.com/square-com-de/plx/blob/main/RELEASE.md) before relying on vehicle data in an automation.

---

[Website](https://square-com.de/) · [Legal notice / Impressum](https://square-com.de/impressum/)

Hue2Lox and PLX are independent projects, not affiliated with or endorsed by Philips Hue, Porsche or Loxone. All trademarks belong to their respective owners. Project artwork and third-party materials retain their respective terms; see each repository's notices.
