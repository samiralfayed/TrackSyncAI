# TrackSyncAI

# 🧠 TrackSync AI

**TrackSync AI** is a fully automated Python-based tool that identifies tracked changes in an English Microsoft Word document and intelligently applies those changes to a corresponding Chinese version of the same document — preserving revision history using Word’s "Track Changes" format.

---

## 🚀 Features

- ✅ **Tracked Change Extraction** from English DOCX (insertions & deletions)
- ✅ **AI-Powered Alignment** using multilingual sentence embeddings
- ✅ **Automated Translation** of tracked changes to Chinese
- ✅ **Fuzzy Matching** to improve alignment accuracy
- ✅ **Track Changes Applied** to the Chinese DOCX file using proper XML tags
- ✅ **Alignment Accuracy Report** printed for verification
- ✅ Fully Reproducible & Requires **No Manual Editing**

---

## 🧪 Example Use Case

### 📄 English Input:
> _The fund aims to provide **~~stable income~~ consistent income** over the long term._

### 🇨🇳 Chinese Input:
> _该基金旨在在长期内提供稳定的收益。_

### 🔁 Output:
> _该基金旨在在长期内提供 **~~稳定的收益~~ 一致的收益**。_  
(with Microsoft Word's Track Changes visible)

---

## 🛠️ Requirements

- Python 3.8+
- Internet connection (for model downloads & Google Translate)

### 📦 Dependencies

Install via:

```bash
pip install python-docx lxml sentence-transformers opencc-python-reimplemented googletrans==4.0.0rc1


📊 Output Sample
✅ Output file generated: Chinese_Tracked_Output.docx
🎯 Alignment Accuracy: 87.50%



