# Roman to Integer Converter

A simple Python solution for LeetCode problem #13: Roman to Integer.

## Problem
Roman numerals are represented by seven symbols: I, V, X, L, C, D, M.

| Symbol | Value |
|--------|-------|
| I      | 1     |
| V      | 5     |
| X      | 10    |
| L      | 50    |
| C      | 100   |
| D      | 500   |
| M      | 1000  |

## Solution Approach
This solution uses the **backward iteration** method:
- Process the string from right to left
- If current value &lt; previous value → subtract
- Otherwise → add

## Usage

``bash
python roman_to_integer.py


