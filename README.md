# 🔍 Motif Finder in DNA Sequences

This project automates the process of finding **motifs** (specific patterns) **within DNA sequences**. The script reads sequences from a FASTA file, identifies motifs with a customizable number of mismatches, and saves the results to an output file.

---

## 📋 **Table of Contents**
- [Project Description]
- [Technologies Used]
- [Installation]
- [Usage]
- [Example Data]
- [MOST Important Note]

---

## 📝 **Project Description**

The project performs the following tasks:
1. **Reads DNA sequences** from a FASTA file.
2. **Finds motifs** in each sequence with a specified number of allowed mismatches.
3. **Generates a report** with:
   - The positions where the motif starts in the sequence.
   - The count of each found motif.
4. **Saves the results** to an output file.

---

## 🔧 **Technologies Used**

The project is implemented in **Python** with the following libraries:
- **Biopython** — for working with FASTA files.
- **collections** — for handling data structures like dictionaries.

---

## 🚀 **Installation**

1. Clone the repository from GitHub:
   git clone **https://github.com/Elskene-Sashina/Course---Python-for-Data-analysis-in-Science.-Project-3.git**

2. Install biopython library:
**pip insall biopython**

---

## ⚙️ **Usage**

1.Place your FASTA file in the project directory.

2.Open the script and modify the following placeholders in the **rusulting()** function:

sequences = open_file(**#'PUT HERE YOUR FASTA FILE.fasta'**)

motif = **#'PUT HERE MOTIF THAT YOU NEED'**

possible_mistakes = #int(**'PUT HERE HOW MANY MISTAKES COULD BE IN MOTIF'**)

save_to_file(result, **'PUT THE NAME FOR RESULTING FILE'**)

3.The results will be saved to the specified output file.

---

## 📊 **Example Data**

- [Input File ('PUT HERE YOUR FASTA FILE.fasta'):]

\>Example DNA sequence

ATGGCCATTGTAATGGGCCGCTGAAAGGGTGCCCGATAG


- [Output File:]

Positions of motif starts:

10, 20

Count of each motif:

Motif 'CGTACG': 2 times

---

## 🔍 **MOST Important Note**

Ensure you specify all necessary parameters before running the script. You need to provide:

1. **The input FASTA file**.
2. **The motif** you are searching for.
3. The allowed **number of mismatches**.
4. The **output file name**.

Here, you must specify the name of your input FASTA file.

Good luck! 🍀
