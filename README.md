# Meal Prep - Recipe and Meal Planning App

A Flutter application for recipe browsing, meal planning, and dietary filtering.

## Features

- **Browse Recipes:** View a categorized list of meals and recipes.
- **Meal Details:** See ingredients, steps, and more for each recipe.
- **Favorite Meals:** Mark meals as favorites for quick access.
- **Dietary Filters:** Filter recipes by dietary preferences:
  - Gluten-free
  - Lactose-free
  - Vegetarian
  - Vegan
- **Tabbed Navigation:** Easily switch between categories and favorites.
- **Meal Planning:** Organize and plan your meals.

## Getting Started

This project is built with [Flutter](https://flutter.dev/).

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- A suitable IDE (VS Code, Android Studio, etc.)

### Running the App

1. Clone this repository:
   ```bash
   git clone https://github.com/Motupallisailohith/Recipe_and_Meal_Planning_Madp1.git
   cd Recipe_and_Meal_Planning_Madp1
   ```
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Run on your device/emulator:
   ```bash
   flutter run
   ```

## Project Structure

- `lib/main.dart`: Entry point and main app logic.
- `lib/categories_screen.dart`: Displays categories for browsing meals.
- `lib/category_meals_screen.dart`: Shows meals in a selected category.
- `lib/meal_detail_screen.dart`: Shows detailed info for a meal.
- `lib/tabs_screen.dart`: Tabbed navigation between screens.
- `lib/filters_screen.dart`: Set dietary filters.
- `lib/dummy_data.dart`: Sample data for meals and categories.
- `lib/meal.dart`: Model for meal data.

## Resources

- [Flutter Documentation](https://docs.flutter.dev/)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Useful Flutter samples](https://docs.flutter.dev/cookbook)

## License

This project is licensed under the terms of the repository LICENSE file.
