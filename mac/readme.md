# How to open the Mac apps

### This is only for mac app downloads not HTML downloads.

### I am unable to pay for app signing so you have to do this.

---

## Step 1- for both

Once you have downloaded the zip file, unzip it. Next, move the app to your application folder.

## There are two ways

### One: the UI way

Open the app. It will then say something about the fact that it can't scan for malware. It will give you two options: "Move to Trash" or "Done", hit done. Then go to System Settings -> Privacy & Security. Scroll until you see "'{game_name}' was blocked to protect your Mac." Hit open anyway, then again when the window shows up, and follow the steps it shows from there. After that, you should be able to open the app and play the game!

### Two: the command way


Run the command bellow in terminal:
```
xattr -cr "/Applications/{app_name}.app"
```

Or run these personalized ones for my apps:
```
xattr -cr "/Applications/Forsaken Legends Cursed Isle.app"

xattr -cr "/Applications/The Coin Knight.app"
```