# SQLite Clone in C with Ruby Unit Tests

This project implements a simple SQLite clone using the C language for the database logic and Ruby for unit tests.

## Project Structure

- **Languages Used**: C, Ruby
- **Package Manager**: Bundler (for Ruby)
- **Recommended IDE**: CLion 2024.2.2

## Main Files

- `main.c`: Contains the main database logic.
- `spec/database_spec.rb`: Contains the unit tests for the database.

## Features

- **Insertion**: Insert new rows into the database.
- **Selection**: Select and display all rows from the database.
- **B-Tree**: Print the structure of the B-Tree used to store data.
- **Constants**: Display the constants used in the database.

## Commands

### Meta Commands

- `.exit`: Exit the program.
- `.constants`: Display constants.
- `.btree`: Display the B-Tree structure.
- `.help`: Display this help message.

### SQL Commands

- `insert <id> <username> <email>`: Insert a new row.
- `select`: Select all rows.

## Execution

To run the program, compile `main.c` and run the executable, providing a filename for the database:

```sh
gcc main.c -o main
./main database.db
```

To run the tests, use Bundler:

```sh
bundle install
bundle exec rspec
```

## Authors

- **RikiLaNeko**: Lead Developer
