1. Fork your own copy of [nkoppel/OptimalWordleSolver](https://github.com/nkoppel/OptimalWordleSolver)

2. Upload your own custom list of guess and solution words to `/words`, if any
   
<dl><dd>Under `/src`, edit the txt paths in `words.rs` accordingly</dd></dl>

3. Return to (root) and select **Code > Codespaces > Create codespace on main**

4. Once you're redirected to the codespace, run the following commands:
   
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

5. Download the output `solution.txt` under the Explorer view and upload it to [ylarp.github.io/OptimalWordleSolver](https://ylarp.github.io/OptimalWordleSolver/)
