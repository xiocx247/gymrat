# Gym Consistency & Streak Tracker
A Python CLI tool that tracks gym attendance and measures consistency using weekly goals (e.g., 3 days/week).
Instead of daily streaks, it calculates streaks based on not missing your weekly target.

## Features
- Configurable weekly goal
- Log workouts by date
- Weekly summary (workouts per week)
- Current consistency streak
- Longest consistency streak
  
## Tech
- Python
- JSON file storage
- Command-line interface (CLI)

## Data Format (data.json)
```json
{
  "weekly_goal": 3,
  "workouts": ["2026/01/08", "2026/01/10"]
}
