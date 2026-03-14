# TSTNT Packages

Official package registry for the [TSTNT](https://github.com/tstnt) programming language.

## Install

```bash
tstnt pkg install <package-name>
```

## Available Packages

| Package | Description |
|---------|-------------|
| colors | Terminal colors: red, green, blue, bold... |
| math-extra | factorial, fib, gcd, lcm, is_prime... |
| strings-extra | slugify, pad, repeat_str, count_char... |
| dotenv | Load .env files |
| rpg-engine | RPG game structs and helpers |
| validation | is_email, is_url, is_number... |
| array-extra | any_match, all_match, count_val... |
| datetime | now_sec, format_time, sleep_sec... |
| cli | arg, flag, usage... |
| http-client | get, post, get_json... |
| tg-bot | bot_start, bot_run, reply... |

## Usage

```
use "colors"
use "math-extra"

do main {
    print(red("Hello!"))
    print(factorial(10))
}
```

## Add a package

Create a folder `my-package/main.tstnt` and submit a PR.
