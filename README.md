# TSTNT Packages

Official package registry for the [TSTNT](https://github.com/tstnt-lang) programming language.  
**v0.9.0** — 120+ packages

## Install

```bash
tstnt pkg install <name>
tstnt pkg uninstall <name>
tstnt pkg list
tstnt pkg search [query]
```

## Usage

```
use "logger"
use "ansi"
use "ansi/effects"    # multi-file package

do main {
    logger.info("Starting...")
    print(ansi.rgb(255, 100, 0, "Orange!"))
    print(effects.rainbow("TSTNT"))
}
```

---

## All Packages

### Terminal & UI
| Package | Files | Description |
|---------|-------|-------------|
| ansi | main, effects | ANSI escape codes, cursor, true color RGB, text effects |
| tui | main, widgets | Terminal UI: boxes, progress bars, badges, status bar |
| terminal-ui | main, table | Headers, sections, alerts, formatted tables |
| color-scheme | main, palettes | Themes: default, dark, monokai, nord, solarized |
| colors | main | Terminal colors via term module |
| colors-extra | main | rainbow, gradient, highlight |
| color2-pkg | main | RGB/hex colors, gradient text, ocean, fire effects |
| banner | main | info_banner, success_banner, warn_banner, tip |
| ascii-art | main | box, double_box, banner, center, separator |
| figlet | main | Big ASCII text |
| braille | main | Text to braille |

### Forms & Input
| Package | Files | Description |
|---------|-------|-------------|
| forms | main, validators | Text/number/select fields + validation rules |
| prompt | main, spinner | Styled ask/confirm/choice + animated spinner |
| menu-builder | main, navigation | Menu items with icons, hints + screen navigation |
| cli-tools | main, args | Styled CLI output + argument parsing |

### Data & Storage
| Package | Files | Description |
|---------|-------|-------------|
| migrate | main, helpers | Run/rollback migrations, create/drop tables |
| seed | main, generators | Seed DB with data, insert_many, truncate |
| config | main | Load .env / .json, require keys |
| config-schema | main, loader | Define schema, validate types, merge configs |
| cache | main | Key-value cache with TTL |
| notes | main | Save/get/search notes |
| todo | main | Persistent todo list |
| graph | main | Nodes/edges graph storage |
| tree | main | Tree structure with children/parent |
| ini-parser | main | Parse/get/save INI config files |
| toml-parser | main | Parse TOML config files |
| json-schema | main | Define and validate JSON-like schemas |

### Numbers & Math
| Package | Files | Description |
|---------|-------|-------------|
| number-format | main, currency | thousands, fixed, ordinal, bytes_human, roman |
| math-extra | main | factorial, fib, gcd, lcm, is_prime, clamp |
| stats | main | mean, median, variance, std_dev, mode, percentile |
| matrix | main | 2D matrix: new, get, transpose, identity |
| distance | main | km/miles, m/ft, haversine |
| temperature | main | C/F/K conversions |
| currency | main | Convert between currencies |
| money | main | add/sub/percent/tax/discount |
| formula | main | compound interest, BMI, kinetic energy |

### Strings & Text
| Package | Files | Description |
|---------|-------|-------------|
| string-format | main, templates | truncate, wrap, snake_case, camel_case, mustache |
| strings-extra | main | slugify, pad, repeat_str, count_char |
| string-builder | main | append, prepend, repeat_append |
| template-engine | main | render, render_all, render_loop |
| markdown | main | h1-h3, bold, italic, code, link, table |
| morse | main | Text to morse code |
| i18n | main | Translations, plural forms |
| l10n | main | Locale-aware formatting, plural |
| image-text | main | speech_bubble, thought_bubble, shadow_text |
| xml-builder | main | tag, attr_tag, escape, wrap, rss_item |
| html-builder | main, style | HTML generation + inline styles |

### Network & HTTP
| Package | Files | Description |
|---------|-------|-------------|
| http-client | main | get, post, get_json |
| http-server-pkg | main, request | Route registration, request parsing |
| websocket-pkg | main, protocol | WebSocket simulation + frame protocol |
| url-parser | main | parse, get_host, get_path, encode |
| query-string | main | parse, get, build, has |
| port-scanner | main | scan ports, check if open |
| network-info | main | hostname, is_online, local_ip |

### Security & Auth
| Package | Files | Description |
|---------|-------|-------------|
| auth | main | register, login, change_password |
| session | main | create, get_user, valid, destroy |
| jwt | main | create, verify, payload |
| password | main | strength, generate, hash_pwd, verify |
| crypto-utils | main | sha256, base64, hex, hmac, random_token |
| crypto-advanced | main | PBKDF2, HMAC, OTP, token generation |
| base64-pkg | main | encode, decode, encode_url |
| rate-limiter | main | allow, remaining, reset |
| circuit-breaker | main | open/closed state, failure tracking |
| cookie | main | set, get, delete, to_header |

### Telegram
| Package | Files | Description |
|---------|-------|-------------|
| tg-bot | main | bot_start, bot_run, reply helpers |
| tg-rpg | main | Telegram RPG engine with DB |
| tg-admin | main, commands | Admin management, banning, broadcasting |

### Games
| Package | Files | Description |
|---------|-------|-------------|
| game-2d | main, render | Vec2, Rect, collision, ASCII canvas, draw_line |
| game-rpg | main, items | Hero stats, combat, XP, item inventory |
| rpg-engine | main | Player/Enemy structs, calc_damage, heal |

### Visualization
| Package | Files | Description |
|---------|-------|-------------|
| data-viz | main | Bar chart, pie chart, sparkline, line chart |
| format-table | main | Simple, box, CSV table rendering |
| table | main | Print formatted ASCII tables |
| qr-text | main | ASCII QR-like code generator |

### Utils & Tools
| Package | Files | Description |
|---------|-------|-------------|
| logger | main | info, warn, error, debug, success, fatal |
| benchmark-suite | main, suite | run, print_result, compare, suite runner |
| test-data | main, fixtures | random arrays, user/product fixtures |
| fake-data | main, content | Names, emails, lorem ipsum, URLs, colors |
| file-watcher | main, events | Poll file changes, event log |
| zip-utils | main | compress, extract, list, validate |
| date-utils | main | timestamp, format, days_since, duration_str |
| datetime | main | now_sec, format_time, sleep_sec |
| stopwatch | main | start, stop, lap, print_elapsed |
| timer-pkg | main | new, elapsed, measure, format |
| countdown | main | run, format |
| calendar | main | days_in_month, is_leap, quarter |
| scheduler | main | delay, cron_match |
| version-check | main | compare, is_newer, bump_patch/minor/major |
| update-notifier | main | check and display update banner |
| env-check | main | require keys, is_prod/dev/test |
| system-info | main | os, arch, cpus, cwd, home, pid |
| memory-usage | main | total_mb, free_mb, used_pct |
| disk-usage | main | free_gb, used_pct, dir_size |
| cpu-usage | main | count, load, usage_pct |
| git-utils | main | status, commit, push, log, clone |
| cli | main | arg, flag, option, usage |
| dotenv | main | load, get_or |

### Patterns & Architecture
| Package | Files | Description |
|---------|-------|-------------|
| functional | main | compose, pipe, curry, memoize, identity |
| pipeline | main | run, tap, branch, catch_pipeline |
| pipeline-async | main | run_async, parallel, waterfall |
| event-bus | main | on, off, handlers, events |
| pub-sub | main | subscribe, publish, last_message |
| observable | main | create, get, set, watch |
| hooks | main | before/after hooks |
| state-machine | main | new_machine, transition, add_transition |
| middleware | main | use_mw, run_stack, log/auth/cors |
| plugin-system | main | register, enable, disable, list |
| worker-pool | main | new_pool, submit, stats |
| retry | main | times, with_backoff |
| timeout | main | run_with_timeout |
| promise-like | main | resolve, reject, then |
| async-queue | main | new, enqueue, dequeue, size |
| queue-pkg | main | push, pop, peek, size |
| stack-pkg | main | push, pop, peek, size |
| linked-list | main | append, get, size, to_array |
| map-reduce | main | mr_map, mr_filter, mr_reduce |

### Data Structures
| Package | Files | Description |
|---------|-------|-------------|
| array-extra | main | any_match, all_match, count_val, head, tail |
| validation | main | is_email, is_url, is_number |
| validation-extra | main, rules | is_phone, is_ipv4, is_semver, rule engine |
| diff | main | lines_added, lines_removed, summary |
| patch | main | apply, make_patch, revert |

### i18n
| Package | Files | Description |
|---------|-------|-------------|
| i18n | main | set_lang, t(), add translations |
| l10n | main | localize, format_number, plural |

### Misc
| Package | Files | Description |
|---------|-------|-------------|
| router | main | get/post/put/delete, resolve |
| simple-http | main | response, ok, not_found, json_response |
| repl-tools | main | run_session, history_repl |
| spinner | main | tick, done, fail |
| loading-dots | main | animate, once, done |
| progress-bar | main | render, print_bar |

---

*Built for TSTNT v0.9.0+ — [github.com/tstnt-lang](https://github.com/tstnt-lang)*
