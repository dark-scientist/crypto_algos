# Prithwin's Cipher Suite

A classy web-based application for classical cryptographic ciphers, featuring an elegant UI and multiple cipher implementations.

## Overview

This application transforms the original C-based cipher program into a modern, responsive web application. It maintains all the functionality of the original code while providing an intuitive and visually appealing user interface.

## Features

- **14 Classical Ciphers**: From simple substitution ciphers like Atbash and Caesar to more complex transposition ciphers like Rail Fence and Columnar.
- **Elegant UI**: Clean, modern interface with a responsive design that works on desktop and mobile devices.
- **Real-time Encryption**: Instant feedback as you type or adjust parameters.
- **Client-side Processing**: All encryption happens in the browser - no server needed.

## Included Ciphers

1. **Atbash Cipher** - A simple substitution cipher that replaces each letter with its mirror in the alphabet.
2. **Caesar Cipher** - Shifts each letter in the plaintext by a fixed number of positions down the alphabet.
3. **Affine Cipher** - Combines multiplication and addition in modular arithmetic.
4. **Vigenère Cipher** - Uses a keyword to determine varying shift values.
5. **Gronsfeld Cipher** - Similar to Vigenère but uses numeric digits as the key.
6. **Beaufort Cipher** - A reciprocal cipher where the key is used to determine reversed shifts.
7. **Auto Key Cipher** - Uses the plaintext itself as part of the key.
8. **Running Key Cipher** - Uses a long text (like a book passage) as the key.
9. **Hill Cipher** - Uses linear algebra with a matrix key for encryption.
10. **Rail Fence Cipher** - A transposition cipher that writes text in a zigzag pattern.
11. **Route Cipher** - Arranges text in a grid and reads it off in a specific pattern.
12. **Columnar Cipher** - Arranges text in a grid and reads off columns according to a key.
13. **Double Transposition Cipher** - Applies columnar transposition twice with different keys.
14. **Myszkowski Cipher** - A variation of columnar transposition with special handling for repeated letters in the key.

## How to Use

1. Save the entire HTML content to a file named `index.html`
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge)
3. Enter your text in the "Plaintext" field (default is "Prithwin")
4. Select a cipher method from the left sidebar
5. Adjust any parameters specific to the selected cipher
6. The encrypted result will be displayed automatically

## Implementation Details

- The application is contained in a single HTML file with embedded CSS and JavaScript
- No external dependencies or internet connection required
- All cipher algorithms are implemented in pure JavaScript
- Responsive design works on both desktop and mobile devices

## Credits

Created by Prithwin based on the original C implementation of classic cipher algorithms.

## License

Feel free to use, modify, and distribute this application for personal or educational purposes.

---

© 2025 Prithwin's Cipher Suite