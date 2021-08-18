# spwn-rand
A random library for the SPWN programming language

# How to use
```rust
// Import the library
random = import rand

// Gives a random number in the range (inclusive)
num = random.randint(0, 10)

// Chooses a random number from an array
num = random.choice([0, 1, 2, 3, 4])

// Shuffles an array
new_array = random.shuffle([0, 1, 2, 3, 4])
```
