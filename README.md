# Pinewood Derby Logger

A simple mobile-friendly web app for tracking Pinewood Derby race results on race day.

## Quick Start

The app comes pre-loaded with dummy data so you can explore how everything works. **Take a few minutes to tap through each tab** and see the features before clearing the data for your event.

### Important: Your Data is Stored Locally

All race data is saved to your browser's local storage on your device. This means:
- Your data persists even if you close the browser
- **If you switch to a different phone/tablet/computer, your data won't be there**
- Use **Export Data** to save a backup file, then **Import Data** on another device if needed

---

## The Four Tabs

### 1. Log Race Tab

This is where you record each race.

**How it works:**
1. The **Race Number** auto-increments after each logged race
2. Select a **racer for each lane** before the race starts (you can leave lanes empty if not all are used)
3. After the race, **enter the time** for each lane
4. Tap **Log Race** - winners are automatically calculated based on times (fastest = 1st place)

The lanes highlight blue when a racer is selected, and green when a time is entered.

**Clear Lanes** resets all lane selections and times for the next race.

### 2. Leaders Tab

Shows the current standings with quick stats at the top (total races, number of cars, fastest time overall).

**Sorting Options:**
- **By Points** - Traditional scoring (3 pts for 1st, 2 pts for 2nd, 1 pt for 3rd)
- **By Avg Time** - Average of all race times
- **Avg (drop worst)** - Average time excluding each racer's slowest run
- **By Best Time** - Single fastest time recorded

Each racer shows their points, race count, medal counts, average time, and best time.

Your car (if set) is highlighted with a gold star and border.

### 3. History Tab

View all logged races in reverse chronological order (newest first).

**Filters:**
- **All** - Shows every race
- **My Races** - Only shows races where your car participated

Each race entry shows the placements with medals, racer names, lane numbers, and times. Tap the **×** to delete a race if entered incorrectly.

### 4. Racers Tab

Manage your car list and app data.

**Generate Car Numbers:**
Enter a range (e.g., 1-75) and tap Generate to create all car entries at once.

**My Car:**
Select which car is yours to highlight it throughout the app with a gold star.

**All Cars:**
Tap on any car to add a friendly name (e.g., "Speed Demon" or the scout's name). Names are optional but make the leaderboard easier to read.

**Data Management:**
- **Export Data** - Downloads a JSON file backup
- **Import Data** - Restore from a backup file
- **Clear All Data** - Wipe everything and start fresh

---

## Getting Ready for Race Day

1. Go to the **Racers** tab
2. Tap **Clear All Data** to remove the dummy data
3. Enter your car number range and tap **Generate**
4. Optionally add names to cars as scouts check in
5. Select **My Car** if you want to track a specific car
6. Switch to **Log Race** and you're ready to go!

---

## Tips

- Keep your phone plugged in - the screen will be on a lot
- Export your data periodically as a backup
- The app works offline once loaded
- Times should be entered as seconds with decimals (e.g., 2.451)

---

## Hosting

This is a single HTML file designed to be hosted on GitHub Pages or any static web host.
