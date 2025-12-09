# Todo List

A Move smart contract that implements a simple todo list management system on the Sui blockchain.

## Project Structure

- **sources/todo_list.move** - Main module containing the todo list implementation
- **tests/todo_list_tests.move** - Test suite for the todo list functionality
- **Move.toml** - Package manifest and configuration

## Features

The `todo_list` module provides the following functionality:

- **TodoList**: A struct that stores a vector of todo items
- **new(ctx)**: Create a new empty todo list
- **add(list, item)**: Add a new todo item to the list
- **remove(list, index)**: Remove and return a todo item by index
- **length(list)**: Get the number of items in the list
- **delete(list)**: Delete the todo list and clean up its resources

## Building

To build the project, run:

```sh
move build
```

## Testing

To run the test suite, execute:

```sh
move test
```

## Development

This project uses Move 2024.beta edition. For more information about Move and Sui, visit:
- [Sui Documentation](https://docs.sui.io)
- [Move Language Guide](https://move-language.github.io/)
