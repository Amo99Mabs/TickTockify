# ⏳ Ticktockify

Ticktockify is a simple yet effective terminal-based countdown timer built with Python. It converts user input (in seconds) into a readable `HH:MM:SS` format and updates every second until the time runs out.

## 🚀 Features

- Accepts time input in seconds
- Dynamically calculates and displays time in `Hours:Minutes:Seconds`
- Uses `time.sleep()` to refresh the timer every second
- Ends with a `"TIME'S UP!"` message for clarity

## 🛠 How It Works

1. User inputs total countdown time in seconds.
2. Loop calculates and displays the countdown in real time.
3. Timer decreases every second until it reaches zero.
4. Displays an end message `"TIME'S UP!"` at completion.

## 📦 Requirements

- Python 3.x

No third-party libraries needed—just pure Python!

## 💻 Usage

```bash
$ python ticktockify.py
Enter the time in seconds: 90
00:01:30
00:01:29
...
