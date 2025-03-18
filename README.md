
# Blackcoffer Data Extraction and NLP Text Analysis Assignment

## 📌 Objective
This project focuses on extracting text content from a list of article URLs and performing sentiment and readability analysis. The task includes calculating various linguistic metrics like sentiment scores, readability scores, and other text-based variables.

The analysis follows the methodology outlined in the `Text Analysis.docx`.

---

## 📂 Project Structure
```
├── env/                        # Python virtual environment (optional)
├── MasterDictionary/          # Contains positive and negative word lists
├── StopWords/                 # Contains stop words lists
├── Input.xlsx                 # Contains URLs and URL_IDs
├── Output Data Structure.xlsx # Defines output format
├── Output Data.xlsx           # Final output with all metrics
├── requirements.txt           # List of Python libraries needed
├── Text Analysis.docx         # Methodology document
├── Objective.docx             # Assignment objective
├── notebook.ipynb             # Jupyter Notebook with the complete solution
```

---

## 🛠 Technologies & Libraries Used
- Python 3.x
- BeautifulSoup
- Requests
- NLTK
- TextBlob
- Pandas
- Openpyxl
- Regex (re module)

---

## ⚙️ Methodology Overview (as per Text Analysis Document)
1. **Sentiment Analysis**
   - Clean text using stop words
   - Use Master Dictionary for positive and negative words
   - Calculate:
     - Positive Score
     - Negative Score
     - Polarity Score
     - Subjectivity Score

2. **Readability Analysis**
   - Compute Average Sentence Length
   - Calculate Percentage of Complex Words
   - Compute Fog Index

3. **Linguistic Metrics**
   - Complex Word Count
   - Word Count (cleaned)
   - Syllable Count per Word
   - Personal Pronouns Count (`I`, `we`, `my`, `ours`, `us`)
   - Average Word Length

---

## 📈 Output
The final output is saved in `Output Data.xlsx` with all the computed metrics following the structure provided in `Output Data Structure.xlsx`.

Example Metrics:
| URL_ID | URL | Positive Score | Negative Score | Polarity Score | Subjectivity Score | Avg Word Length |
|-------|-----|---------------|---------------|---------------|--------------------|-----------------|
| 101   | example.com | 32 | 12 | 0.45 | 0.28 | 4.8 |

---

## ✅ How to Run
1. **Install Dependencies**:
```bash
pip install -r requirements.txt
```

2. **Run the Notebook**:
```bash
jupyter notebook notebook.ipynb
```
Alternatively, if converted to a Python script:
```bash
python your_script.py
```

3. **Output**:
- Extracted `.txt` files (optional)
- Final `Output Data.xlsx`

---

## 📥 Deliverables Included
✅ Python / Jupyter Notebook file (`notebook.ipynb`)  
✅ Final output file (`Output Data.xlsx`)  
✅ `requirements.txt`  
✅ This `README.md` file  
✅ `Text Analysis.docx` explaining the methodology  

---

## 🚀 Submission Note
You can push this project to GitHub or zip the entire folder and share the link as per Blackcoffer's instructions.

Submission Form: [Blackcoffer Test Submission](https://forms.gle/nvWAgrCBdq1JkKou8)

---

## 👨‍💻 Author
Your Name

---

## 📌 References
- [Blackcoffer Official Website](https://blackcoffer.com)
