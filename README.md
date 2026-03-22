# TSTNT Packages v1.5.0

275+ packages for the TSTNT programming language.

Install any package:
```bash
tstnt pkg install <name>
```

---

## Math & Science
| Package | Description |
|---------|-------------|
| `complex-numbers` | Complex number math: add, mul, div, abs, arg, pow |
| `linear-algebra` | Vectors, matrices: dot, cross, mul, transpose, identity |
| `statistics` | mean, median, variance, std_dev, percentile, IQR, correlation, z-score, histogram |
| `number-theory` | primes, GCD, LCM, factorize, Euler totient, power_mod, Fibonacci, perfect numbers |
| `formula` | Math formula evaluator |
| `entropy` | Shannon entropy, cross-entropy, KL divergence, mutual information |
| `astronomy` | Julian day, moon phase, sunrise/sunset, planet distances |
| `music-theory` | Notes, scales, chords, MIDI, frequencies, intervals |

## Machine Learning & AI
| Package | Description |
|---------|-------------|
| `neural` | sigmoid, relu, dot_product, layer_forward, mse_loss, normalize |
| `neural2` | Extended neural network utilities |
| `linear-regression` | fit, predict, R², MSE |
| `kmeans` | K-means clustering: fit, assign, step |
| `knn` | K-nearest neighbors classifier |
| `perceptron` | Single-layer perceptron: train, predict, accuracy |
| `genetic-algo` | Genetic algorithm: population, mutate, crossover, evolve |
| `decision-tree` | Decision tree classifier |
| `naive-bayes` | Naive Bayes classifier |
| `minimax` | Minimax with alpha-beta pruning, Tic-Tac-Toe |
| `q-learning` | Q-learning reinforcement learning |

## NLP & Text
| Package | Description |
|---------|-------------|
| `levenshtein` | Edit distance, string similarity, fuzzy match |
| `tokenizer` | Tokenize, word frequency, top words, n-grams, stopwords |
| `stemmer` | English word stemming |
| `tfidf` | TF-IDF text scoring |
| `jaccard` | Jaccard similarity, cosine similarity, Hamming distance |
| `string-distance` | Jaro, Jaro-Winkler similarity |
| `string-case` | camelCase, PascalCase, snake_case, kebab-case, Title Case |
| `string-validate` | palindrome, pangram, anagram, word count, reading time |
| `lorem` | Lorem ipsum text generation |
| `word-gen` | Random word and sentence generation |
| `markov` | Markov chain text generation |
| `regex-lite` | Glob matching, email/URL/IP/numeric validation |

## Data Structures
| Package | Description |
|---------|-------------|
| `heap` | Min-heap: push, pop, peek |
| `deque` | Double-ended queue |
| `segment-tree` | Range sum query, point update |
| `interval-tree` | Interval overlap queries, point queries |
| `bloom-filter` | Probabilistic set membership |
| `trie` | Prefix search, insert, has |
| `linked-list` | Linked list operations |
| `stack-pkg` | Stack: push, pop, peek |
| `queue-pkg` | Queue: enqueue, dequeue |
| `multimap` | Multi-value map |
| `lru` | LRU cache with capacity |
| `bitset` | Bit array: set, clear, AND, OR, NOT |

## Algorithms
| Package | Description |
|---------|-------------|
| `algorithms` | Binary search, BFS, Fibonacci, two_sum |
| `sorting` | Bubble, selection, insertion, counting sort, binary search |
| `graph` | Graph data structure |
| `graph-algorithms` | BFS, DFS, path finding, degree |
| `pathfinding` | Grid pathfinding, flood fill |
| `number-theory` | Primes, GCD, LCM, factorization |
| `genetic-algo` | Evolutionary optimization |
| `minimax` | Game tree search with alpha-beta |

## Cryptography & Encoding
| Package | Description |
|---------|-------------|
| `base32` | Base32 encode/validate |
| `base58` | Base58 encode (Bitcoin-style) |
| `base64-pkg` | Base64 encode/decode |
| `hmac` | HMAC sign and verify |
| `otp` | TOTP/OTP generation and verification |
| `crc` | CRC8, CRC16, CRC32 checksums |
| `crypto-utils` | SHA256, MD5, hashing utilities |
| `crypto-advanced` | Advanced cryptographic operations |
| `huffman` | Huffman entropy, compression ratio |
| `run-length` | RLE encode/decode |
| `entropy` | Information theory metrics |

## Games & Simulations
| Package | Description |
|---------|-------------|
| `chess` | Chess board, rendering |
| `dice` | D4/D6/D8/D10/D12/D20/D100, advantage/disadvantage |
| `cards` | Deck, shuffle, deal, Blackjack hand values |
| `sudoku` | Sudoku board, validation, rendering |
| `maze-gen` | Recursive maze generation and rendering |
| `minesweeper` | Minesweeper logic |
| `snake-game` | Snake game logic |
| `tetris-logic` | Tetris piece logic |
| `physics2d` | Rigid bodies, gravity, AABB/circle collision |
| `particles` | Particle emitter and update |
| `tilemap` | 2D tile map: get, set, fill, render, neighbors |
| `easing` | Easing functions: quad, cubic, sine, elastic, bounce |
| `vec2d` | 2D vector: add, scale, dot, norm, dist, lerp |

## UI & Terminal
| Package | Description |
|---------|-------------|
| `tui` | Basic TUI toolkit |
| `tui-pro` | Full TUI: box, menu, alerts, table |
| `ascii-table` | Formatted ASCII tables with sorting |
| `box-drawing` | Single/double box drawing, lines |
| `charts-ascii` | Bar chart, sparkline, line chart |
| `progress-bar` | Progress bar rendering |
| `progress-multi` | Multiple progress bars |
| `spinner` | Terminal spinner |
| `banner` | ASCII art banners |
| `figlet` | FIGlet-style text art |
| `ascii-art` | ASCII art utilities |
| `ansi` | ANSI escape codes |
| `colors-256` | 256-color terminal support |
| `color3` | True color RGB, gradients |
| `color-scheme` | Color scheme management |

## Colors
| Package | Description |
|---------|-------------|
| `color-convert` | hex↔rgb, rgb↔hsl, luminance, contrast ratio, mix |
| `color-palette` | Complementary, triadic, analogous, tetradic palettes |
| `colors-extra` | Extended color utilities |
| `color2-pkg` | Color formatting utilities |

## Data Formats
| Package | Description |
|---------|-------------|
| `csv-parser` | CSV parse, filter, column extraction |
| `json-schema` | JSON schema validation |
| `json-patch` | JSON patch operations |
| `yaml-lite` | Simple YAML key-value parser |
| `msgpack` | MessagePack encoding |
| `ini` | INI file parser |
| `ini-parser` | Extended INI support |
| `toml-parser` | TOML parser |
| `xml-builder` | XML building |
| `html-builder` | HTML building |
| `markdown` | Markdown processing |

## State Management
| Package | Description |
|---------|-------------|
| `store-manager` | Key-value store with merge, serialize |
| `reactive` | Reactive values with subscribers |
| `atom` | Atomic state with versioning |
| `undo-redo` | Undo/redo history |
| `history-manager` | History management |
| `event-sourcing` | Event sourcing with snapshots |
| `snapshot` | State snapshots |
| `memento` | Memento pattern |
| `time-travel` | Time-travel debugging |
| `event-replay` | Event replay |

## Design Patterns
| Package | Description |
|---------|-------------|
| `command-pattern` | Command with undo/redo history |
| `strategy-pattern` | Strategy registration and dispatch |
| `factory-pattern` | Factory pattern |
| `decorator-pattern` | Decorator pattern |
| `singleton` | Singleton pattern |
| `observer` | Observer pattern |
| `mediator` | Mediator pattern |
| `dependency-injection` | DI container |
| `actor` | Actor model with mailbox |
| `cqrs` | CQRS pattern |

## Finance & Math
| Package | Description |
|---------|-------------|
| `money-calc` | Money arithmetic, formatting, splitting |
| `tax` | Tax calculation, compound interest, loan payments, ROI |
| `unit-convert` | km↔miles, kg↔lbs, °C↔°F, bytes, degrees |
| `recipe-calc` | Recipe scaling, unit conversion, calories |
| `currency` | Currency operations |
| `money` | Money utilities |
| `distance` | Distance calculations |
| `temperature` | Temperature conversion |

## Utilities
| Package | Description |
|---------|-------------|
| `date-utils` | Date parsing and formatting |
| `timezone` | Timezone conversion, UTC offsets |
| `weather-fmt` | Weather formatting, feels-like, UV index |
| `roman-numerals` | Roman numeral conversion |
| `lorem` | Lorem ipsum generation |
| `nanoid` | Nano ID generation |
| `ulid` | ULID generation and validation |
| `uuid-v4` | UUID v4 generation |
| `slugify` | URL slug generation |
| `semver` | Semantic versioning |
| `version-check` | Version comparison |
| `dotenv-pkg` | .env file loading |
| `config` | Configuration management |
| `env-check` | Environment variable validation |

## Networking & Web
| Package | Description |
|---------|-------------|
| `http-server` | HTTP server with routing |
| `http-server-pkg` | Extended HTTP server |
| `simple-http` | Simple HTTP utilities |
| `http-client-utils` | HTTP client helpers |
| `router` | URL router |
| `websocket-pkg` | WebSocket support |
| `url-parser` | URL parsing |
| `query-string` | Query string parsing |
| `cookie` | Cookie handling |
| `session` | Session management |
| `jwt` | JWT tokens |
| `auth` | Authentication utilities |
| `rate-limiter` | Rate limiting |
| `middleware` | Middleware chain |

## Telegram
| Package | Description |
|---------|-------------|
| `tg-admin` | Telegram admin panel |
| `tg-rpg` | Telegram RPG engine |

## Database
| Package | Description |
|---------|-------------|
| `sql-orm` | ORM on top of sql module |
| `migrate` | Database migrations |
| `cache` | Caching layer |

## System & Process
| Package | Description |
|---------|-------------|
| `system-info` | System information |
| `process-list` | Process listing |
| `cpu-usage` | CPU usage monitoring |
| `memory-usage` | Memory usage |
| `disk-usage` | Disk usage |
| `network-info` | Network information |
| `port-scanner` | Port scanning |
| `file-utils` | File utilities |
| `file-watcher` | File change detection |
| `git-utils` | Git utilities |
| `zip-utils` | ZIP file handling |

## Async & Concurrency
| Package | Description |
|---------|-------------|
| `async-queue` | Async queue |
| `pipeline` | Data pipeline |
| `pipeline-async` | Async pipeline |
| `worker-pool` | Worker pool |
| `pub-sub` | Publish/subscribe |
| `pub-sub2` | Extended pub/sub |
| `event-bus` | Event bus |
| `event-emitter` | Event emitter |
| `channels` | Channel communication |
| `task-runner` | Task runner |
| `scheduler` | Job scheduler |
| `cron` | Cron-style scheduling |
| `timeout` | Timeout utilities |
| `timer-pkg` | Timer management |
| `retry` | Retry with backoff |
| `circuit-breaker` | Circuit breaker pattern |

## Testing & Benchmarking
| Package | Description |
|---------|-------------|
| `benchmark-suite` | Benchmarking utilities |
| `test-data` | Test data generation |
| `fake-data` | Fake data generation |
| `interview-prep` | Interview prep problems |

## Functional Programming
| Package | Description |
|---------|-------------|
| `functional` | compose, pipe, curry, memoize |
| `map-reduce` | MapReduce utilities |
| `observable` | Observable values |
| `hooks` | Hook system |
| `promise` | Promise-like async |
| `promise-like` | Promise utilities |
| `result-pkg` | Result/Option types |
| `plugin-system` | Plugin architecture |

## Low-Level
| Package | Description |
|---------|-------------|
| `circuit-logic` | Logic gates, half/full adder, MUX/DEMUX |
| `binary-ops` | Binary operations |
| `bitwise-utils` | Bitwise utilities |
| `flag-set` | Flag/bitmask management |
| `bitmask` | Bitmask operations |
| `pack-bits` | Bit packing |
| `run-length` | RLE compression |
| `huffman` | Huffman coding |
| `lz-compress` | LZ compression |

---

**275 packages** · MIT License · [github.com/tstnt-lang/packages](https://github.com/tstnt-lang/packages)
