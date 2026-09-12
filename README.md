# Instructions

1. Upload your own custom solution_words txt, if any, to the /words folder
2. Head to words.rs under the /src folder and edit the txt paths accordingly\\
    &nbsp`guess_words.txt` contains the original 12972 valid Wordle guesses (which WordleCup uses)\
    &nbsp`guess_words_2.txt` contains the current 14855 valid Wordle guesses
4. Return to the repo root and select 'Code', then 'Codespaces', and finally 'Create codespace on main'
5. Once you're redirected, run the following commands:\\
    &nbsp```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```\\
    &nbspEnter '1' when promopted\\
    &nbsp```source "$HOME/.cargo/env"```\\
    &nbsp```rustup default nightly```\\
    &nbsp```cargo run```
