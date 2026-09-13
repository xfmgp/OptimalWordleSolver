# Instructions

1. Fork your own copy of [nkoppel/OptimalWordleSolver](https://github.com/nkoppel/OptimalWordleSolver)

2. Upload your own custom list of guess and solution words to /words, if any
   
&nbsp;&nbsp;&nbsp;&nbsp;2a. Under /src, edit the txt paths in `words.rs` accordingly

3. Return to (root) and select Code > Codespaces > Create codespace on main
   
4. Once you're redirected to the codespace, run the following commands:
   
    &emsp;```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```
   
    &emsp;Enter '1' when prompted
   
    &emsp;```source "$HOME/.cargo/env"```
   
    &emsp;```rustup default nightly```

    &emsp;```cargo run```

5. Download the output `solution.txt` under the Explorer view and upload it to [ylarp.github.io/OptimalWordleSolver](https://ylarp.github.io/OptimalWordleSolver/)
