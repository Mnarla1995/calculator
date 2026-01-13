### 📱 Calculator
A simple yet well-structured calculator app built with **SwiftUI** using the **MVVM** architecture.

#### Features
- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Clear and responsive button layout
- Centralized styling for calculator buttons
- Clean separation of concerns using MVVM

#### Architecture Overview

**Model**
- `Calculator.swift` – Core calculation logic
- `ButtonType.swift` – Enum defining calculator button types
- `CalculatorButtonStyle.swift` – Styling logic for buttons

**View**
- `ContentView.swift` – Main calculator UI layout
- `CalculatorButton.swift` – Reusable button component

**ViewModel**
- `CalculatorViewModel.swift` – Handles user input, state, and interaction between View and Model

**App Entry Point**
- `CalculatorApp.swift`

**Assets**
- App icon and accent colors are managed via `Assets.xcassets`

#### Requirements
- Xcode 15 or later
- iOS 17+
- Swift 5.9+

#### How to Run
1. Open `Calculator/Calculator.xcodeproj`
2. Select an iOS simulator or device
3. Build and run the project
