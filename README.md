# Instructions

1. Upload your own custom solution_words txt, if any, to the /words folder
2. Head to words.rs under the /src folder and edit the txt paths accordingly\
   `guess_words.txt` contains the original 12972 valid Wordle guesses (which WordleCup uses)\
   `guess_words_2.txt` contains the current 14855 valid Wordle guesses
4. Return to the repo root and select 'Code', then 'Codespaces', and finally 'Create codespace on main'
5. Once you're redirected, run the following commands:\
   ```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```\
   Enter '1' when promopted\
   ```source "$HOME/.cargo/env"```\
   ```rustup default nightly```\
   ```cargo run```
