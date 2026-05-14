# Namma Mela

Namma Mela is a modern Android application designed for theater enthusiasts. It allows users to browse upcoming plays, view detailed information about cast and crew, book seats for performances, and share their thoughts on a community fan wall.

## 🚀 Features

- **User Authentication**: Secure Login and Registration screens.
- **Browse Plays**: A dynamic home screen listing various theater performances.
- **Detailed Play Information**: View synopsis, duration, and cast/crew details for each play.
- **Seat Booking**: Interactive seat selection and booking system with instant confirmation.
- **Fan Wall**: A community space to read and post comments about your favorite plays.
- **Content Management**: An interface for authorized users to upload new play details.

## 🛠️ Tech Stack

- **Language**: [Kotlin](https://kotlinlang.org/)
- **UI Framework**: [Jetpack Compose](https://developer.android.com/jetpack/compose)
- **Architecture**: MVVM (Model-View-ViewModel)
- **Asynchronous Programming**: [Kotlin Coroutines & Flow](https://kotlinlang.org/docs/coroutines-overview.html)
- **Image Loading**: [Coil](https://coil-kt.github.io/coil/compose/)
- **UI Components**: Material Design 3

## 📂 Project Structure

- `com.example.nammamela`: Main application logic and Compose UI screens.
    - `data`: Contains models (`Play`, `Comment`, `Booking`), repository, and `ViewModel`.
    - `ui.theme`: Material 3 theme definitions (Color, Type, Shape).

## 🏗️ Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/NammaMela.git
   ```
2. **Open in Android Studio**:
   Open the root folder in Android Studio (Ladybug or newer recommended).
3. **Build & Run**:
   Select the `app` module and run it on an emulator or a physical device (API 24+).

## 📸 Screenshots

*(Add screenshots of your app here to make it more appealing!)*

---
Developed as a showcase of modern Android development practices.
