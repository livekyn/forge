# FORGE — Priority HIT Architecture

**No drift. No excuses. Execute.**

FORGE is a precision workout tracking PWA (Progressive Web App) built on the Priority HIT Architecture — a scientifically-designed training framework that combines absolute strength, hypertrophy, and metabolic stress into a single efficient system.

## What is FORGE?

FORGE is a **single-file fitness application** that runs entirely in your browser. It's designed for athletes who demand efficiency, precision, and real-time feedback during their training sessions.

### Key Features

- **7-Day Customizable Workout Plan** — Day 1-5 focused training blocks, Days 6-7 optimization
- **Priority HIT Architecture** — Multi-badge system (Priority, Heavy, HIT, Blast, Carry, Recovery, Optimize)
- **Real-time Progress Tracking** — Live progress bar, set completion tracking, timer management
- **Persistent Custom Workouts** — Make changes (exercise names, add/delete sets, change badges) that persist across sessions
- **Reset to Default** — One-click revert to original workout protocol anytime
- **Session Logging** — Complete workout history with PRs, weights, reps, and timestamps
- **Active Recovery Protocol** — Day 3 includes cardio selection and box breathing breathwork
- **Set Management** — Add custom sets, delete sets with confirmation, long-hold detection
- **Offline Capable** — Full PWA with offline functionality and installable to home screen
- **Dark Mode UI** — Performance-optimized dark interface with red/gold/green accents

### Workout Structure

**Day 1: Upper Yoke A**
- Priority neck work, heavy pressing, pull-ups, and blast finishers
- Goal: Build the masculine silhouette

**Day 2: Lower Power**
- Priority squat work, deadlift variations, leg press, calf raises
- Goal: Raw leg strength and explosiveness

**Day 3: Active Recovery + Cardio**
- Cardio selection (rucking, rowing, bike, stair master, incline walk, jog)
- Box breathing protocol
- Goal: Recovery and work capacity

**Day 4: Upper Chest & Back**
- Incline pressing, row variations, cable work, blast finishers
- Goal: Chest thickness and back mass

**Day 5: Lower Hypertrophy**
- Leg press, hamstring curls, leg extensions, blast work
- Goal: Quad and hamstring development

**Days 6-7: Optimization**
- Sun exposure, posture correction, meal prep
- Goal: Lifestyle and recovery amplification

## Getting Started

### Installation

**Option 1: Web Browser**
1. Download `index.html`
2. Open in any modern web browser (Chrome, Safari, Firefox, Edge)

**Option 2: Install as PWA**
1. Open FORGE in Chrome/Edge
2. Click the install icon in the address bar
3. Add to home screen → Launches as native app

### Usage

1. **Select a day** from the home screen
2. **Tap to complete sets** as you work through them
3. **Double-tap completed sets** to reset if needed
4. **Long-hold sets** to delete them
5. **Click the pencil icon** next to exercise names to rename them
6. **Click the dropdown arrow** next to badges to change exercise type
7. **Click the plus button** next to sets to add custom sets
8. **View logs** to track your progress over time

## Customization

### Edit Exercise Names
- Click the **✎ (pencil icon)** next to any exercise name
- Change to any exercise you prefer
- Changes persist automatically

### Change Exercise Type (Badge)
- Click the **▼ (dropdown arrow)** next to the badge
- Select from: Priority, Heavy, HIT, Blast, Carry, Recovery, Optimize, Tech Fail, Abs Fail
- Updates instantly

### Add Custom Sets
- Click the **+ (plus button)** next to the set dots
- Choose set type: Warmup, Feeder, Working, Tech Fail, Abs Fail, Blast
- Enter rep range (e.g., 8-12, 15-25)
- New set appears in the set row

### Delete Sets
- **Long-hold (600ms)** any set square
- Confirm deletion
- Set is removed permanently

### Reset to Default
- Go to home screen
- Scroll to bottom
- Click **"Reset to Default Workout Plan"**
- Confirm → Reverts entire plan to original

## Technical Details

- **Framework**: Vanilla JavaScript (no dependencies)
- **Storage**: Browser localStorage for session persistence
- **PWA**: Service worker support for offline functionality
- **Responsive**: Optimized for mobile, tablet, and desktop
- **File Size**: Single HTML file (~120KB)
- **Browsers**: Chrome, Safari, Firefox, Edge (all modern versions)

## Data Privacy

- **All data stored locally** — Nothing uploaded to servers
- **No tracking** — No analytics, no user tracking
- **No accounts required** — Works completely offline
- **Your data is yours** — Full control in localStorage

## Features in Detail

### Progress Bar
- Starts at red (0%), transitions through orange, yellow, to green (100%)
- Shows percentage completion
- Updates after each set

### Rest Timer
- Countdown timer between sets
- Continues even if app is minimized (timestamp-based)
- Haptic feedback when timer completes

### Session Notes
- Add custom notes during your workout
- Saved with session data
- Visible in session logs

### Personal Records (PRs)
- Automatically tracked when you beat previous weights
- Highlighted with 🏆 badge
- Logged in session history

### Last Session Lookup
- Previous weights and reps pre-filled
- Makes it easy to match or exceed last session
- Customizable per set

## Keyboard & Touch

- **Tap set** → Complete set
- **Double-tap completed set** → Reset set
- **Long-hold set** → Delete with confirmation
- **Click pencil** → Edit exercise name
- **Click dropdown arrow** → Change badge/type
- **Click plus button** → Add new set
- **Enter key** → Confirm in modals
- **Escape key** → Cancel modals

## Troubleshooting

**Q: My changes disappeared after closing the app**
- A: They shouldn't. Refresh the page. If the issue persists, check if localStorage is enabled in your browser.

**Q: Can I backup my custom workouts?**
- A: Your data is in browser localStorage. Use browser dev tools (F12) → Application → Local Storage to export `forge3_workoutPlan`.

**Q: Can I use this offline?**
- A: Yes. Open once online, then it works offline. PWA support included.

**Q: How do I delete my data?**
- A: Clear browser cache/storage for this site, or click "Reset to Default" then manually clear localStorage.

## Contributing

This is a personal fitness application built with precision and purpose. Contributions focused on performance, usability, and the core training philosophy are welcome.

## License

FORGE — Built for the pursuit of strength and precision.

---

**Remember: The yoke is built in sessions no one sees. You just added another layer.**
