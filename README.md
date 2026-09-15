1. Fork your own copy of [nkoppel/OptimalWordleSolver](https://github.com/nkoppel/OptimalWordleSolver)

2. Upload your own custom list of guess and solution words to `/words`, if any
   
   Under `/src`, edit the txt paths in `words.rs` accordingly

4. Return to the **repo** root and select **Code** > **Codespaces** > **Create codespace on main**

5. Once you're redirected to the Codespace, run the following commands: 
   ```
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```
   Enter `1` when prompted
   ```
   source "$HOME/.cargo/env"
   ```
   ```
   rustup default nightly
   ```
   ```
   cargo run
   ```

6. Download the output `solution.txt` from the Codespace and upload it to [ylarp.github.io/wordle](https://ylarp.github.io/wordle)

   Use `//` for single-line comments or `/* */` for multi-line comments in `solution.txt`
