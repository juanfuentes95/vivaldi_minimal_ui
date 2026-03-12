# Vivaldi Minimal UI

Minimal CSS configuration for a **clean and compact** Vivaldi toolbar interface.

<img width="1172" height="795" alt="image" src="https://github.com/user-attachments/assets/30b3183b-8728-44e1-82ee-8f33bc57e634" />

---

## Enable CSS Modifications

Open:

```text id="k9u2rx"
vivaldi://flags
```

Enable:

```text id="m2v6qe"
Allow CSS modifications
```

Then go to:

```text id="7p8y1d"
Settings → Appearance → Custom UI Modifications
```

Select your CSS folder and **restart Vivaldi**.

---

## UI Configuration

`Settings → Appearance`

```text id="b3j4sw"
User Interface Density → Compact
Compact Menu Layout → Enabled
Status Info → Overlay
Menu Position → Vivaldi Button
Menu Icon Style → Menu Icon
```

---

## Toolbar Cleanup

Right click any toolbar button → **Customize Toolbar**.

**Address Bar**

I removed the following icons:
* VPN
* Reload
* Share Vivaldi
* Vivaldi Account
* Horizontal Panel

**Tab Bar**
* Remove **Workspaces** icon

---

## Flatpak Note

If you use the Flatpak version of Vivaldi, place the CSS folder inside:

```text id="p6n3ah"
/home/<user>/.var/app/com.vivaldi.Vivaldi/config/<css_folder>
```

This ensures the modifications persist.
