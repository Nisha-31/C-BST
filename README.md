AVL Tree with IP Address Management

Overview

This project implements an AVL tree to manage and organize IPv4 addresses and their corresponding aliases. It includes functionalities for adding, updating, deleting, and searching for IP addresses, as well as displaying logs and validating inputs. The program is written in C and uses standard libraries for file handling, string manipulation, and memory management.

Features

Add Address: Insert a new IP address and its alias into the AVL tree.

Lookup Address: Search for an IP address by its alias.

Update Address: Modify an existing alias or IP address.

Delete Address: Remove an alias and its associated IP address from the tree.

Display List: Show all IP addresses and aliases in the tree in sorted order.

Display Aliases for Location: Display aliases matching a given location-based IP segment.

Error Log: View errors encountered during file reading or invalid input handling.

Quit: Exit the program.


Usage

Compilation

To compile the program: gcc -o avl_tree source.c 

Execution

Run the compiled executable: ./avl_tree

Input File Format

The input file (CS531_Inet.txt) should contain IP addresses and aliases, one per line, in the following format:

192.168.0.1 alias1
10.0.0.5 al


Requirements

GCC compiler.
Input file: CS531_Inet.txt with valid IP and alias entries.
