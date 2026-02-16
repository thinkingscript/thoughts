# Thoughts

A community collection of [ThinkingScript](https://thinkingscript.com) thoughts you can run directly from the command line.

## Usage

Run any thought directly from this repo:

```sh
think https://raw.githubusercontent.com/thinkingscript/thoughts/main/weather.md "San Francisco"
```

Or browse the repo and download ones you like:

```sh
curl -O https://raw.githubusercontent.com/thinkingscript/thoughts/main/weather.md
think weather.md "San Francisco"
```

Install a thought to use it as a regular command:

```sh
thought install https://raw.githubusercontent.com/thinkingscript/thoughts/main/weather.md
weather "San Francisco"
```

## Contributing

Share your own thoughts! Open a PR with a `.md` file. Keep it simple — describe what the thought does in plain language.

---

<!-- When you run this README with 'think README.md', magic happens below! -->

Display a colorful, animated welcome message for the Thoughts repository.

Show the Thoughts logo in ASCII art, display system info, show a random inspirational message about what thoughts can do, and list some example thoughts they can try.

Make it feel welcoming and exciting - use colors if the terminal supports them, add some personality, and make the user feel like they've just discovered something cool.
