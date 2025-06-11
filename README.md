# FASTA-Sequence-Downloader-from-UniProt-Python-Script-
A Python script to download FASTA sequences from UniProt using a list of accession IDs and save them into a single .fasta file. Useful for bioinformatics projects, sequence analysis, or protein annotation pipelines

# 🧬 FASTA Sequence Downloader from UniProt

This Python script automates the process of downloading protein sequences in FASTA format from the [UniProt](https://www.uniprot.org/) database using a list of UniProt accession IDs.

## 🚀 Features

- Accepts a list of UniProt accession IDs from a text file
- Fetches and saves the corresponding protein sequences
- Each sequence is saved as a separate `.fa` file

## 📁 File Structure

```
.
├── accession_ids.txt     # Input file with UniProt IDs (one per line)
├── fasta_downloader.py   # Python script for downloading
├── P12345.fa             # Output: downloaded FASTA files
└── ...
```

## 🛠️ Requirements

- Python 3.x
- `requests` library

Install the required library using:

```bash
pip install requests
```

## 💻 Usage

1. Clone the repository:

```bash
git clone https://github.com/Anjalivasudevan/FASTA-Sequence-Downloader-from-UniProt-Python-Script-.git
cd FASTA-Sequence-Downloader-from-UniProt-Python-Script-
```

2. Add UniProt IDs (one per line) to `accession_ids.txt`:

```
P69905
P68871
```

3. Run the script:

```bash
python fasta_downloader.py
```

4. Check the folder for the downloaded `.fa` files.

## ✅ Example Output

If `accession_ids.txt` contains:

```
P69905
P68871
```

You will get:

```
P69905.fa
P68871.fa
```

Each file contains a complete protein sequence in FASTA format.

## 🔧 Future Improvements

- Option to combine all sequences into a single multi-FASTA file
- Command-line arguments for input/output flexibility
- Improved error handling and logging

## 👩‍💻 Author

**Anjali Vasudevan**  
M.Sc. Computational Biology  
✨ Passionate about bioinformatics, data science, and automation

## 📜 License

This project is open-source under the MIT License.

