# Pipex - 42 Project

## Overview
Pipex is a project at 42 School that involves recreating the functionality of the shell command `pipe` using low-level Unix system calls. The goal is to create a simple command-line program that emulates the behavior of the following shell command:

## How to Use (Mandatory)
Follow these steps to use Pipex for the mandatory part, which involves executing two commands in succession:

1. **Clone this repository:**
   ```bash
   ./pipex file1 "cmd1" "cmd2" file2

## Example
./pipex infile "ls -l" "grep a1" outfile

## How to Use (Bonus)
Follow these steps to use Pipex for the bonus part, which allows for an arbitrary number of commands:

1. **Clone this repository:**
   ```bash
   ./pipex file1 "cmd1" "cmd2" ... "cmdn" file2

## Example
./pipex infile "ls -l" "grep a1" "sort -r" outfile