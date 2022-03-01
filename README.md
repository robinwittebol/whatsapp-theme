![whatsapp-theme-dashboard-dark](https://user-images.githubusercontent.com/27996405/155767773-e9dcdee3-f3da-4a9b-9512-d92db8c8968b.png)

# Whatsapp Theme

Home Assistant theme based on Whatsapp colors by Robin Wittebol.
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
