# Health-and-Fitness-Tracker-Android-
Health &amp; Fitness Tracker is an Android application that helps users monitor daily physical activity, track hydration, plan meals, and visualize health progress over time.
## Features

* **Step Counter** using device motion sensors
* **Water Intake Tracker** to log daily hydration
* **Meal Planner** for organizing daily meals
* **Reminders** using AlarmManager for water and meals
* **Progress Charts** to visualize health and fitness trends


## Tech Stack

* **Kotlin** – Primary programming language
* **Android SensorManager** – Step detection
* **Room Database** – Local data storage
* **AlarmManager** – Reminder notifications
* **MPAndroidChart** – Graphs and analytics


## Project Structure

```
HealthFitnessTracker/
│
├── app/
│   └── src/main/
│       ├── java/com/example/healthtracker/
│       │   ├── sensors/
│       │   ├── data/
│       │   ├── ui/
│       │   ├── reminders/
│       │   └── charts/
│       └── res/layout/
```

## How It Works

* The app listens to motion sensors to count steps in real time.
* Users can log daily water intake and planned meals.
* AlarmManager triggers notifications to remind users to stay hydrated and follow their meal schedule.
* Collected data is displayed using charts for easy progress tracking.


## Future Improvements

* Calorie tracking and nutrition analysis
* Integration with wearable devices
* Cloud backup and synchronization
* Weekly and monthly health reports


## Author

**Chitraksh Sonkar**
Developed as part of Android Development coursework.


## License

This project is created for educational purposes.
