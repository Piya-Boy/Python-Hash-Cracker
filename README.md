
# Python-Hash-Cracker

Python hash cracker built for learning purposes. It supports several hash formats with options like number bruteforce and verbose mode.

![Alt text](img2.JPG?raw=true "Screenshot")

## Command Line Options

The command line interface is straightforward. Here are the available options:

- `-h [hash]`: Specify the hash to crack.
- `-t [type]`: Specify the hash type (e.g., md5, sha1).
- `-w [wordlist]`: Use a wordlist file for cracking.
- `-n [numbers bruteforce]`: Use numbers bruteforce in place of a wordlist.
- `-v [verbose]`: Enable verbose mode, which may slow down cracking time.
- `-i [help and info]`: Display help and information.

## Versions

### Version 1

Run the script with a specified wordlist file:
```bash
python Hash-Cracker-v1.py -h <hash> -t <type> -w <Wordlist.txt> -v
```

Download the wordlist for Version 1: [Wordlist v1]([Wordlist.zip](https://prtcollege-my.sharepoint.com/:u:/g/personal/6329030161_prtc_ac_th/EbBN6QpqV5dPlAhVL5GXD7wB0IQmXfv8_AlXVqmkUYVPzw?e=4ervZZ))

### Version 2

Run the script with automatic processing of wordlists from the `wordlist` folder (no need to specify a wordlist file):
```bash
python Hash-Cracker-v2.py -h <hash> -t <type> -v
```

Download the wordlist for Version 2: [Wordlist v2] [wordlist (1).zip](https://prtcollege-my.sharepoint.com/:u:/g/personal/6329030161_prtc_ac_th/Ec9_75lr-vpFvBNq2yNds2sBgTBbfICYY5mmz7n_kiZQFw?e=tQaHv0)

### Changes in Version 2

- **Automatic Wordlist Processing**: Version 2 no longer requires specifying a wordlist file. It automatically processes wordlists from the `wordlist` folder.

## Examples

**Help Command:**
```bash
python Hash-Cracker-v1.py -i
```

**Hash Cracking with Wordlist and Verbose Mode (Version 1):**
```bash
python Hash-Cracker-v1.py -h 7406e17d2e30b05b7220a800fad53a22 -t md5 -w Wordlist.txt -v
```

**Hash Cracking with Automatic Wordlist Processing and Verbose Mode (Version 2):**
```bash
python Hash-Cracker-v2.py -h 7406e17d2e30b05b7220a800fad53a22 -t md5 -v
```

**Numbers Bruteforce Fast (Version 1):**
```bash
python Hash-Cracker-v1.py -h 7406e17d2e30b05b7220a800fad53a22 -t md5 -n
```

## Platforms

The command line tool has been tested and works with:
- iOS
- Windows (7/8/10/11)
- Unix
- OS X

## Enjoy!
```

Replace `link-to-wordlist-v1` and `link-to-wordlist-v2` with the actual URLs where the wordlists can be downloaded. If you need help finding or setting up the download links, let me know!
