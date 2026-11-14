# Digital_clock
# Digital Clock – C Programming

**A Real-Time Digital Clock Application Using C**

A simple command-line Digital Clock application developed using the C programming language. It displays the current system time and date in real time and allows users to choose between 12-hour and 24-hour time formats.

## Features

- **Real-Time Clock:** Displays the current system time.
- **Date Display:** Shows the current day, month, and year.
- **12-Hour Format:** Displays time with AM/PM.
- **24-Hour Format:** Displays time in 24-hour notation.
- **Auto Refresh:** Updates the clock every second.
- **Cross-Platform Screen Clearing:** Uses `cls` on Windows and `clear` on Linux/macOS.

## Technologies Used

- C Programming Language
- Standard C Libraries
- `time.h` – Date and time operations
- `stdlib.h` – System commands
- `unistd.h` – Sleep functionality

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/jubayer-jm/digital-clock.git
   ```

2. Navigate to the project directory:

   ```bash
   cd digital-clock
   ```

3. Compile the program:

   ```bash
   gcc main.c -o clock
   ```

4. Run the program:

   ```bash
   ./clock
   ```

   On Windows:

   ```bash
   clock.exe
   ```

## How It Works

1. The program asks the user to select a time format.
2. It retrieves the current system time using `time()` and `localtime()`.
3. The `strftime()` function formats the date and time.
4. The screen is cleared and the updated time and date are displayed.
5. The process repeats every second.

## Learning Outcomes

Through this project, I practiced:

- Functions in C
- Pointers and character arrays
- Structures (`struct tm`)
- Date and time handling
- Conditional compilation (`#ifdef`)
- Infinite loops and the `sleep()` function
- Basic system commands

## Author

**Jubayer Ahmed**

- GitHub: [jubayer-jm](https://github.com/jubayer-jm)

---

*This project was developed as part of my journey to improve my C programming and problem-solving skills.*
