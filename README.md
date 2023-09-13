# Homework 3: Multi-threading and Multi-processing

This project demonstrates the power of multi-threading and multi-processing in Python. The homework is divided into two parts:

## Part 1: Multi-threading (Directory Organizer)

**Goal**: Sort files in the specified folder by extensions using multiple threads.

- **Description**: This program processes a folder, organizing its files based on file extensions. To speed up the processing of large directories with many nested folders and files, the program utilizes multi-threading. The most time-consuming tasks, such as moving files and listing the contents of directories, are handled by separate threads or a pool of threads.

## Part 2: Multi-processing (Factorize Function)

**Goal**: Implement the `factorize` function that takes a list of numbers and returns a list of numbers which are factors of the input numbers.

- **Description**: This part requires the implementation of a synchronous version of the `factorize` function. After measuring its performance, the function is then optimized using multi-processing to utilize multiple CPU cores. The performance of this parallelized version is also measured.

- **Usage**: The function can be tested using the provided test assertions:

    ```python
    a, b, c, d  = factorize(128, 255, 99999, 10651060)
    ```

## Getting Started

1. For the directory organizer, execute the script related to Part 1 and provide the path to the folder you want to organize.
2. For the factorize function, execute the script related to Part 2 and observe the console for performance metrics.

## Contributors

- [Dmytro Klymenko]

## License

This project is open source and available under the [MIT License](LICENSE).
