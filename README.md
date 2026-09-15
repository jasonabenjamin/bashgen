# bashgen

Generate Bash shell scripts from natural-language requests using AI.

## Requirements

- Linux or other Unix compatible
- Python 3  (comes with Linux)
- Internet connection
- A free.ai API key

## Setup

1. Sign up for a free account at Free.ai.
2. Get your API key from your Free.ai account.
3. Open `bashgen` and enter your API key where indicated:

```python
api_key = "YOUR_API_KEY"
```

4. Run `bashgen` with your request:

`chmod +x bashgen`

```bash
./bashgen "create a backup of my home directory"
```

### Options

```text
--help
--sh
--no-run
--save FILE
```

You must have a Free.ai API key for bashgen to work.
