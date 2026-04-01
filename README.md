# Dice Passphrase Generator
  
A Python-based implementation of the [EFF Dice-Generated Passphrase](https://www.eff.org/dice) method. This tool generates high-entropy passphrases by selecting random words from a curated list of approximately 7,700 unique words. The result is a password that is easy for a human to memorize but computationally "impossible" to crack via brute-force or dictionary attacks.

## Key Features:

- High Entropy: Uses the gold-standard EFF wordlist for maximum security.  
- Customizable Length: Choose the number of words based on your required security level.  
- Privacy-Centric: Runs entirely locally; no data ever leaves your machine.  

## Usage
```
$ python pass_gen.py 
[?] How many words: 6
flattery retread sacrament affecting unquote juice
```
