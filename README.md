# Sentence Analysis Algorithm

## 📌 Project Overview
This project implements a simple character-by-character algorithm that analyzes a sentence ending with a period (`.`). The algorithm processes each character individually and computes key statistics about the sentence.

## 🎯 Objectives
The algorithm determines:

- **Sentence Length** – Total number of characters (including spaces and the final period).
- **Word Count** – Total number of words (words are separated by a single space).
- **Vowel Count** – Total number of vowels (`a, e, i, o, u`, both lowercase and uppercase).

## ⚙️ Approach
- The sentence is read **one character at a time**.
- Three counters are maintained:
  - `length`
  - `words`
  - `vowels`
- The algorithm stops when the period (`.`) is reached.
- Word count is determined by counting spaces and adding one.

## 🧠 Key Concepts
- Loop control using a sentinel value (`.`)
- Character-by-character processing
- Conditional counting using counters
- Basic string analysis logic

## ✅ Output
The program outputs:
- Total number of characters
- Total number of words
- Total number of vowels

---

This project demonstrates fundamental algorithm design principles including iteration, condition checking, and counter-based computation.