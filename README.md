# Oopsinator

> Get roasted for your typos.

**Oopsinator** is a shell add-on that insults you every time you mistype a command, turning every "command not found" into a teachable (and laughable) moment. Why just get an error when you could get roasted?

---

## 🐚 Supported Shells

Oopsinator works out-of-the-box with **Zsh**, **Bash**, and **Fish**.  
Just copy-paste the provided function into your shell’s configuration file and enjoy the roast.

---

### ⚡️ Quick Setup

#### Zsh

Add the contents of this file to your `~/.zshrc`:
[`OopsinatorZSH`](functions/zshrc)

#### Bash

Add the contents of this file to your `~/.bashrc`:
[`OopsinatorBASH`](functions/bashrc)

#### Fish

Add the contents of this file to your `~/.config/fish/functions/fish_command_not_found.fish`:
[`OopsinatorFISH`](functions/fish_command_not_found.fish)

---

## ✨ Features

- **Savage Insults:** Every mistyped command earns a random insult.
- **Lightweight:** No dependencies, just shell functions.
- **Customizable:** Edit the insults to match your humor or pain tolerance.

---

## 🤬 Customization

Open the function file for your shell and add, remove, or rewrite the insults in the insult list/array. Make it as mild or as brutal as you like.

---

## 📝 Example Output

```sh
$ sl
Oops! 'sl' is not a command, genius. Try 'ls' next time.
```

---

## 📜 License

MIT — roast yourself and your friends freely!

---

Made by [xZepyx](https://github.com/xZepyx). PRs and new insults welcome!
