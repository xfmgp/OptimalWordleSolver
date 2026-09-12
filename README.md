# Instructions

1. Upload your own custom solution_words txt, if any, to the /words folder
   
3. Head to words.rs under the /src folder and edit the txt paths accordingly
   
    &emsp;`guess_words.txt` contains the original 12972 valid Wordle guesses (which WordleCup uses)
   
    &emsp;`guess_words_2.txt` contains the current 14855 valid Wordle guesses

4. Return to the repo root and select 'Code', then 'Codespaces', and finally 'Create codespace on main'
   
6. Once you're redirected, run the following commands:
   
    &emsp;```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```
   
    &emsp;Enter '1' when prompted
   
    &emsp;```source "$HOME/.cargo/env"```
   
    &emsp;```rustup default nightly```

    &emsp;```cargo run```

A `solutions.txt` will be saved to the repo root
