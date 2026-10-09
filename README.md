# Lab 5 - Product Detail Screen Application

A modern, responsive Product Detail Screen application built with Flutter & Material 3. This application demonstrates essential Flutter layout techniques, interactive UI components, state management, and clean code structure.

## 📱 Features

- **Product Cover Image & Floating Bookmark Button**: Uses `Stack`, `Container`, `ClipRRect`, and `CircleAvatar` with bookmarking state toggle.
- **Category Badges**: Custom chips utilizing `Wrap` layout to display tags dynamically.
- **Product Information**: Displays product title, star rating badge, price, and item description using structured `Row` and `Column` widgets.
- **Quantity Counter**: Interactive item quantity selector with state management (`setState`).
- **Sticky Bottom Action Bar**: Pin-to-bottom "Add to Cart" button inside `SafeArea` with floating `SnackBar` user notifications.
- **Responsive & Overflow-Safe**: Built with `SingleChildScrollView` and `Expanded` widgets to prevent `RenderFlex` overflow errors on smaller screens.

## 🛠️ Built With

- **Flutter**: ^3.13.2 (Dart SDK)
- **Material Design 3**: Enhanced UI components and modern styling

## 🚀 Getting Started

### Prerequisites

Ensure you have installed:
- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- Android Studio / VS Code with Flutter extension
- Android Emulator / Physical Device

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/POTATOMEN228/lab5.git
   cd lab5
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the application:**
   ```bash
   flutter run
   ```

## 📂 Project Structure

```
lib/
└── main.dart          # Main application entry point & ProductDetailScreen implementation
assets/
└── images/            # Asset folder for product images
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
