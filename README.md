# Hello World in Haskell

A minimal Haskell implementation of "Hello, World!".

## Installation

### macOS
```bash
brew install ghc
```

### Linux
```bash
sudo apt install ghc  # Ubuntu/Debian
sudo dnf install ghc  # Fedora/RHEL
```

### Windows
Download GHC from https://www.haskell.org/ghc/

## Running

```bash
ghc -o hello Main.hs
./hello
```

## Code Explanation

Uses IO monad with putStrLn for console output.
