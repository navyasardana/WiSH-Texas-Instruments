# Calculator Project

A simple four-operation calculator written in C. This is the Week 2 team exercise for WiSH 2026.

## Structure

```
calculator_project/
├── inc/
│   └── calculator.h    # Function declarations
├── src/
│   ├── main.c          # Entry point and main loop (team fills this in)
│   ├── add.c           # Addition      (one team member fills this in)
│   ├── subtract.c      # Subtraction   (one team member fills this in)
│   ├── multiply.c      # Multiplication (one team member fills this in)
│   ├── divide.c        # Division      (one team member fills this in)
│   └── menu.c          # Menu printer  (each team member adds their line here)
└── Makefile
```

## Build

Run from inside the `calculator_project/` directory:

```bash
make
```

## Run

```bash
./calculator
```

## Clean

```bash
make clean
```
