# IP Filter Application

This repository contains a C++ application for processing and filtering a list of IP addresses.

## Task Description
The goal of the task is to implement an application that reads IP addresses from standard input, processes them, and outputs the results. Each input line consists of three fields separated by a tab character and terminated by a newline. The format is as follows:

text1 \t text2 \t text3 \n

The application loads the list of IP addresses into memory and sorts them in reverse lexicographical order based on their byte representation. The sorting is done numerically, not as strings.

## Sorting Example
Input:

1.1.1.1
1.2.1.1
1.10.1.1

Sorted Output:

1.10.1.1
1.2.1.1
1.1.1.1

After sorting, the application outputs the following:
1. Full list of addresses after sorting.
2. List of addresses with the first byte equal to 1.
3. List of addresses with the first byte equal to 46 and the second byte equal to 70.
4. List of addresses with any byte equal to 46.

## Implementation
The C++ source code provided in the repository should be modified to use C++14/C++17 features where possible. Ensure that the necessary functionality is implemented.

### Building and Running

## Unit Tests
Additional exercises include adding unit tests using a preferred testing framework, such as GoogleTest. Ensure that the ip_filter package, containing the executable ip_filter, is published as a release in the repository.

