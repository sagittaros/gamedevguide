# Bash

## Colors and Formatting

* [ANSI Escape Codes](https://www.wikiwand.com/en/ANSI_escape_code)
  ![terminal-ansi-escape-codes.png](../_assets/terminal-ansi-escape-codes.png)
  * `\e`:  0x1b ascii escape character 
  * `\e[38;5;(n)m`: Select foreground color
  * `\e[48;5;(n)m`: Select background color
    * *0..7*:  standard colors (e.g. `\e[30–37m`)
    * *8..15*:  high intensity colors (e.g. `\e[90–97m`)
    * *16..231*:  6 × 6 × 6 cube (216 colors): 16 + 36 × r + 6 × g + b (0 ≤ r, g, b ≤ 5)
    * *232..255*:  grayscale from black to white in 24 steps
* [More details](https://misc.flogisoft.com/bash/tip_colors_and_formatting)
