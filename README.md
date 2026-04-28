# Open-Source-Coding-

# 💰 BudgetBuddy

A smart personal expense tracking Android app built with modern Android development tools.

## 📱 Screenshots

> Login • Home • Expenses • Categories • Budget Goals • Expense Details

## ✨ Features

- 🔐 **User Authentication** — Register and login securely with email and password
- 💸 **Add Expenses** — Log expenses with title, amount, date, category and receipt photo
- 🗂️ **Categories** — Organise spending with custom emoji-based categories
- 📋 **View Expenses** — See all expenses with total banner and quick delete
- 🎯 **Budget Goals** — Set monthly budget limits with live progress tracking
- ⚠️ **Over-Budget Alerts** — Get warned instantly when you exceed your budget
- 🔍 **Expense Details** — View full details including receipt photo
- 📷 **Receipt Photos** — Attach photos to any expense for record keeping

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Kotlin** | Primary programming language |
| **Jetpack Compose** | Modern declarative UI |
| **MVVM Architecture** | Clean separation of concerns |
| **Room Database** | Local SQLite data storage |
| **Navigation Compose** | Screen routing and back stack |
| **StateFlow** | Reactive UI state management |
| **Coil** | Image loading for receipt photos |
| **DataStore** | Persistent session storage |
| **Material 3** | Google's latest design system |

## 🏗️ Project Structure

```
com.example.budgetbuddy
├── data/               # Room entities, DAOs, Database
│   ├── User.kt
│   ├── Category.kt
│   ├── Expense.kt
│   ├── BudgetGoal.kt
│   ├── BudgetDatabase.kt
│   ├── UserDao.kt
│   ├── CategoryDao.kt
│   ├── ExpenseDao.kt
│   └── BudgetGoalDao.kt
├── repository/         # Data abstraction layer
│   └── BudgetRepository.kt
├── viewmodel/          # UI state management
│   ├── AuthViewModel.kt
│   └── ExpenseViewModel.kt
├── screens/            # Jetpack Compose UI screens
│   ├── LoginScreen.kt
│   ├── RegisterScreen.kt
│   ├── HomeScreen.kt
│   ├── CategoriesScreen.kt
│   ├── AddExpenseScreen.kt
│   ├── ExpensesScreen.kt
│   ├── BudgetGoalsScreen.kt
│   └── ExpenseDetailScreen.kt
├── navigation/         # App navigation graph
│   └── AppNavigation.kt
└── ui/theme/           # Green Material 3 theme
```

## 🗄️ Database Design

- **Users** — Stores registered user accounts
- **Categories** — Custom emoji expense categories per user
- **Expenses** — Full expense records with photo support
- **BudgetGoals** — Monthly spending limits per user

## 🚀 Getting Started

### Prerequisites
- Android Studio (latest version)
- Android device or emulator running API 26+

### Installation
1. Clone the repository
```bash
   git clone https://github.com/yourusername/BudgetBuddy.git
```
2. Open in Android Studio
3. Sync Gradle files
4. Build and run on your device

## 🎨 Design

- **Primary color:** Green (`#388E3C`)
- **Design system:** Material 3
- **Min SDK:** API 26 (Android 8.0)
- **Target SDK:** API 35

## 👨‍💻 Author

Built from scratch as a beginner Android developer 💪

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
