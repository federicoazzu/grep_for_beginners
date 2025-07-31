# grep_for_beginners

The basic search text 

This project is developed in **Rust** based on the following resources:

- 📺 [YouTube Video Tutorial](https://www.youtube.com/watch?v=PX4dEky1pxA)
- 💻 [Original Repository (main.rs)](https://github.com/federicoazzu/grep_for_beginners/blob/main/main.rs)

---

## How to Run

You can run the program in two main ways:

### 1. Run with a single file
```bash
cargo run -- bob text1.txt
```

### 2. Run with multiple files and the `-i` option
```bash
cargo run -- bob text1.txt text2.txt -i
```

---

## Arguments

1. **Text to search** (e.g. `bob`)
2. **Data file(s)** - at least one `.txt` file
3. Additional option(s):
   - `-i` : enable ignore-case

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
