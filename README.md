# Tournament Creator

This is a simple HTML-based application for creating and managing single-elimination knockout tournaments. It allows users to input teams, generate match-ups, input match results, and progress through rounds of the tournament.

## Usage

1. **Add Teams:** Enter the names of the participating teams in the provided input field and click the "Add Team" button to add them to the list of teams.

2. **Start Tournament:** Once you've added at least 2 teams, click the "Start Tournament" button to begin the tournament. This will generate match-ups for the first round of the tournament.

3. **Input Match Results:** For each match-up, enter the scores for both teams in the respective input fields. Then, click the "OK" button to determine the winner of the match.

4. **Next Round:** After entering scores for all matches in the current round, click the "Next Round" button to proceed to the next round of the tournament. This will compile the winners of the current round and generate match-ups for the next round.

5. **Repeat:** Continue this process until the tournament is completed.

## Features

- **Dynamic Match Generation:** Match-ups are automatically generated based on the number of teams entered by the user.
- **Input Validation:** Checks are in place to ensure valid inputs, such as non-empty team names and valid match scores.
- **Single-Elimination Format:** The tournament follows a single-elimination knockout format, where teams are eliminated after losing a match.
- **Winner Display:** The winners of each match are displayed dynamically on the page.
- **Next Round Generation:** The application automatically generates match-ups for the next round based on the winners of the current round.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
