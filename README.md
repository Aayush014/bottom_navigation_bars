# Snake Animation Bottom Navigation Bar in Flutter

This Flutter project showcases a bottom navigation bar with a snake-like animation effect. The animation creates a smooth transition between the selected items, adding a unique and visually appealing interaction in your app.

## Features

- Custom bottom navigation bar
- Snake-like animation on item selection
- Easy to integrate and customize

## Demo
Include a GIF or image here to showcase the animation effect.<br></br>
<img src = "https://github.com/Aayush014/bottom_navigation_bars/assets/133498952/fe4e8457-d482-4b7b-b6d6-b2dba92d2f75" height=10% >


## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart: [Install Dart](https://dart.dev/get-dart)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Aayush014/bottom_navigation_bars.git
    ```

2. Install dependencies:
    ```bash
    flutter pub get
    ```

3. Run the app:
    ```bash
    flutter run
    ```

## Usage

To integrate the snake animation bottom navigation bar into your own project, follow these steps:


1. Copy the `snake_bottom_navbar.dart` file into your project.

2. Import the file in your `main.dart` or relevant screen:
    ```dart
    import 'path/to/snake_bottom_navbar.dart';
    ```

3. Use the `SnakeBottomNavBar` widget in your `Scaffold`:
    ```dart
    Scaffold(
      body: // Your main content here
      bottomNavigationBar: SnakeNavigationBar.color(),
    );
    ```

4. Customize the items and behavior as needed:
    ```dart
    SnakeNavigationBar(
      items: [
        BottomNavigationBarItem(
              icon: Icon(Icons.notifications), label: 'tickets'),
          BottomNavigationBarItem(
              icon: Icon(Icons.calendar_month), label: 'calendar'),
          BottomNavigationBarItem(
              icon: Icon(Icons.home), label: 'home'),
          BottomNavigationBarItem(
              icon: Icon(Icons.podcasts), label: 'microphone'),
          BottomNavigationBarItem(
              icon: Icon(Icons.search), label: 'search'),
      ],
      // Other customization options
    );
    ```

## Customization

You can customize the navigation bar to fit your needs by modifying the SnakeBottomNavBar widget. Key properties include:

- items: List of BottomNavigationBarItem
- currentIndex: The index of the currently selected item
- onTap: Callback function when an item is tapped
- backgroundColor: Background color of the navigation bar
- snakeColor: Color of the snake animation

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

1. Fork the repository
2. Create your feature branch (git checkout -b feature/new-feature)
3. Commit your changes (git commit -m 'Add new feature')
4. Push to the branch (git push origin feature/new-feature)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the unique navigation bar designs in modern mobile apps.
- Thanks to the Flutter community for continuous support and inspiration.

## Contact

For any inquiries or feedback, feel free to contact me at [aayushpatel01411@gmail.com].
