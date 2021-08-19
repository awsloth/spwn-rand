# spwn-rand
A random library for the SPWN programming language

# How to use
```rust
// Import the library
random = import rand

// Can get and set seed to change outputs
seed = random.get_seed()
random.set_seed(134572)

// Gives a random number in the range (inclusive)
num = random.randint(0, 10)

// Chooses a random number from an array
num = random.choice([0, 1, 2, 3, 4])

// Shuffles an array
new_array = random.shuffle([0, 1, 2, 3, 4])

// Gives a random float between the values
num = random.random(0, 10)

// Works for float values too
num = random.random(0, 0.5)
```

# Version
Made with SPWN v0.0.6
