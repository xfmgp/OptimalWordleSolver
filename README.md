# Instructions

1. Fork your own copy of [nkoppel/OptimalWordleSolver](https://github.com/nkoppel/OptimalWordleSolver)

2. Upload your own custom `solution_words_<descriptor>.txt`, if any, to /words
   
3. In `words.rs`, under /src, edit the txt paths accordingly
   
    &emsp;`guess_words.txt` contains the original 12972 valid Wordle guesses (which WordleCup uses)
   
    &emsp;`guess_words_2.txt` contains the current 14855 valid Wordle guesses

5. Return to (root) and select 'Code' > 'Codespaces' > 'Create codespace on main'
   
6. Once you're redirected to vscode.dev, run the following commands:
   
    &emsp;```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```
   
    &emsp;Enter '1' when prompted
   
    &emsp;```source "$HOME/.cargo/env"```
   
    &emsp;```rustup default nightly```

    &emsp;```cargo run```

7. While it computes, rename /web to /docs and change `full_solution_compressed.txt` to `solution.txt` in `ui.js`

8. Move the output `solution.txt` from (root) to /docs/solutions and 'Commit & Push'

When deploying to GitHub Pages, select /docs under 
... Build and deployment > Branch
