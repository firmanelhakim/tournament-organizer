# 🏆 Tournament Mixer - Rotating Partner Round Robin Organizer
A simple, zero-dependency web application to automate the creation and management of "mixer" or "scramble" style round robin tournaments for social sports like pickleball, badminton, tennis, or paddle.
This tool eliminates the manual work of creating schedules, tracking scores, and calculating standings, allowing organizers to run a smooth, efficient, and enjoyable event for everyone.

## ✨ Key Features
 * Automated Schedule Generation: Creates a multi-round schedule using the "Split and Rotate" algorithm to ensure players have different partners and opponents.
 * Simple Setup: Just enter the number of players, courts, and a list of player names to get started.
 * Interactive Scoring: Easily enter scores for each match directly on the schedule.
 * Real-Time Leaderboard: The leaderboard updates instantly after each score submission.
 * Advanced Ranking: Players are ranked by Total Points, with automatic tie-breakers using Point Differential (Points For - Points Against).
 * Fully Self-Contained: Everything is in a single index.html file. No servers, no databases, no setup required.
 * Mobile-Friendly: The interface is responsive and works great on phones and tablets, making it perfect for on-the-go tournament management.

## 🚀 How to Use
 * Save the File: Save the provided code as index.html.
 * Open in Browser: Open the index.html file in any modern web browser (like Chrome, Firefox, or Safari).
 * Fill out the Setup Form:
   * Number of Players: Must be a multiple of 4 (e.g., 8, 12, 16).
   * Number of Courts: The number of games that can be played simultaneously.
   * Player Names: Paste or type the names of all participants, with each name on a new line.
 * Generate Tournament: Click the "Generate Tournament" button. The app will validate the inputs and create the schedule and leaderboard.
 * Run the Tournament:
   * Direct players to their assigned courts for each round as shown in the Schedule section.
   * As matches finish, enter the scores into the input boxes (e.g., 21 and 15) and click the Submit button for that match.
   * The Leaderboard will automatically update and re-sort with each score submission.

## ☁️ How to Host for Free
You can easily host this file online for free so that all participants can view the schedule and leaderboard from their own devices.
 * Rename the file to index.html.
 * Choose a hosting option:
   * Easiest Method (Drag & Drop):
     * Netlify Drop: Go to app.netlify.com/drop and drag your index.html file into the window. Netlify will give you a shareable link in seconds.
   * Most Popular Method (Version Control):
     * GitHub Pages:
       * Create a new public repository on GitHub.
       * Upload your index.html file to the repository.
       * In the repository settings, go to the "Pages" tab and enable GitHub Pages for your main branch.
       * GitHub will provide a public URL for your live application.

## 🛠️ Future Improvements
This is a great starting point, but here are some ideas for future enhancements:
 * Edit Scores: Add a button to allow the organizer to edit a score after it has been submitted.
 * Player Check-in: A system to mark players as "present" before generating the schedule.
 * Export Results: Add a "Print" or "Export to CSV" button for the final leaderboard.
 * Customizable Rules: Allow the organizer to change the points awarded for a win or loss.
 * Persistent Data: Use browser localStorage to save the tournament state, so if the page is refreshed, the data isn't lost.

## 📄 License
This project is open source and available under the MIT License.
