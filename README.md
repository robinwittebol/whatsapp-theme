![whatsapp-theme-screenshot-darkmode](https://user-images.githubusercontent.com/27996405/156218537-c1f58489-7d0e-4c97-8d88-4689b8b404a2.png)

# Whatsapp Theme

Home Assistant theme inspired by WhatsApp. Made by Robin Wittebol.
Supports dark and light mode.

## Preparation

1. Make sure that in your **configuration.yaml** file you have the following:

```
frontend:
  themes: !include_dir_merge_named themes
```

2. Create a new folder named **themes** in your Home Assistant **config** folder.
3. Restart Home Assistant to apply the changes.

## Installation (HACS)

1. Go into the Community Store (HACS).
2. Search for **Whatsapp Theme**.
3. Open the theme.
4. Press Install.
5. Restart Home Assistant.

## Installation (Manual)

1. Create a file named **whatsapp_theme.yaml** in your Home Assistant themes folder.
2. In this repository, copy the contents of **[themes/whatsapp_theme.yaml](https://github.com/robinwittebol/whatsapp-theme/blob/main/themes/whatsapp_theme.yaml)**.
3. Paste the contents in the **whatsapp_theme.yaml** file you created.

## Enable theme

1. Open your Home Assistant Profile.
2. Go to **Themes** and select **whatsapp_theme**.
