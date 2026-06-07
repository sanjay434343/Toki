<div align="center">
  <h1>🚀 Toki: Win Your Morning, Win Your Day</h1>
  <p><strong>A Gamified Productivity & Wellbeing Companion</strong></p>

  <!-- Badges -->
  <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />

  <p>
    <em>Toki merges extreme productivity, time management, and habit tracking into a deeply engaging, gamified experience. Avoid digital distractions, wake up on time, and turn your daily routine into a rewarding game.</em>
  </p>
</div>

---

## 🎨 The Toki UI Aesthetic

Toki isn't just a utility; it's an experience. We designed the app to feel incredibly **tactile, playful, and responsive**:
- **Neo-Brutalist & Playful**: Bold black borders, soft pastel color palettes (lavenders, mint greens, vibrant oranges), and rounded corners.
- **Haptic Feedback**: Every slider, button, and interaction provides satisfying physical feedback.
- **Fluid Animations**: From the counting scoreboard to the auto-scrolling leaderboard carousel, Toki feels alive.
- **Customizable**: Switch between fonts (like Nunito), toggle 24-hour time, and personalize your experience.

---

## 📸 Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center">
        <!-- Replace the URLs below with paths to your actual screenshots -->
        <img src="https://via.placeholder.com/250x500.png?text=Dashboard+View" width="250" alt="Dashboard View"/><br/>
        <b>The Dashboard</b>
      </td>
      <td align="center">
        <img src="https://via.placeholder.com/250x500.png?text=Cognitive+Alarm" width="250" alt="Alarm View"/><br/>
        <b>Cognitive Alarms</b>
      </td>
      <td align="center">
        <img src="https://via.placeholder.com/250x500.png?text=Insights+%26+Stats" width="250" alt="Stats View"/><br/>
        <b>Insights & Stats</b>
      </td>
    </tr>
  </table>
</div>

---

## 🤔 The Problem Toki Solves

Do you hit snooze 5 times every morning? Do you struggle to sit down and focus for 25 minutes without checking your phone? 

Toki is designed for individuals who struggle with **executive dysfunction**, **procrastination**, or simply want to elevate their daily productivity. It forces you to be deliberate about your time by requiring physical and mental interaction to stop alarms and rewarding you for deep work sessions.

---

## ✨ Core Features

### 1. 🧠 Cognitive Wake-Up Alarms
Standard alarms are too easy to turn off. Toki forces your brain to wake up.
- **Math Puzzles:** Solve dynamically generated math equations (with an adjustable difficulty slider) to turn off your alarm.
- **Tic-Tac-Toe:** Win 3 rounds against the app to silence the ringing.
- **Memory Games:** Memorize and match patterns to prove you are awake.
- **Unstoppable Alarms:** Uses Android native APIs (Foreground Services, WakeLocks) to override "Do Not Disturb" and ensure your alarm rings out loud, no matter what.

### 2. ⏳ Focus Timers (Pomodoro)
- Set quick timers (e.g., 25 mins) from the dashboard or create custom labeled sessions.
- Dynamic color themes and fluid countdown animations keep you engaged.
- Progress is tracked as "Focus Points" added to your daily score.

### 3. 📊 Daily Scoring & Analytics (The Aro Score)
Your entire day is quantified into a score out of 100 based on your actions:
- **Focus Time:** Earn points for completing timer sessions.
- **Task Completion:** Earn points for the number of activities logged.
- **Accuracy:** Answer math questions correctly on the first try to boost your accuracy score.
- **Penalties:** Lose points for hitting the snooze button or accumulating too much screen time.
- **Streaks:** Chain successful days together to build an unbreakable streak!

### 4. 🏆 Real-Time Gamified Leaderboard
- Compete globally with other Toki users!
- A real-time leaderboard (synced via Firebase Firestore) ranks users by their current Streak.
- The Dashboard features an **animated Carousel Leaderboard** that cycles through top users, dynamically counting up to their scores.

---

## 🛠️ Technology Stack

- **Frontend:** [Flutter](https://flutter.dev/) (Dart) for a beautiful, 60fps responsive UI.
- **Backend/Database:** [Firebase Authentication & Firestore](https://firebase.google.com/) for real-time leaderboards and user sync. Local SQLite (`sqflite`) for lightning-fast daily progress and history tracking.
- **Native Android:** Kotlin (`AlarmActivity.kt`, `NativeBridge.kt`) for robust background execution, system-level alarm triggering, and bypassing OS sleep states.
- **Icons:** [HugeIcons](https://hugeicons.com/) for a sleek, modern iconography style.

---

## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (latest stable)
- Android Studio / Android SDK
- Firebase Project (configured for Android)

### Installation
1. Clone the repository.
   ```bash
   git clone https://github.com/yourusername/toki.git
   ```
2. Fetch dependencies.
   ```bash
   flutter pub get
   ```
3. Ensure your Android device/emulator is connected.
4. Run the app!
   ```bash
   flutter run
   ```
   *Or build the APK:*
   ```bash
   flutter build apk --release
   ```

---
<div align="center">
  <b>Built with ❤️ using Flutter</b>
</div>
