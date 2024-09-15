# CV-Segmenter
Building a functionality to automatically segment a PDF CV into distinct sections: Objective, Work and Employment, Education and Training, Skills, and Accomplishments.

# Workflow
**Extract text from PDFs**: Use PDFPlumber or PyMuPDF to extract the text while preserving structure.
**Preprocess text:** Clean the text using techniques like tokenization, stopword removal, and lemmatization (use spaCy).
**Segment and classify**: Use a combination of Regex for detecting obvious sections (like dates for work experience) and fine-tune a BERT-based model for classifying more complex sections.
**Evaluate and refine**: Use metrics like accuracy and F1-score, and apply rule-based post-processing to improve results.

# Technologies used
We'll combine **PDFPlumber** for PDF extraction, **spaCy** for text processing, **BERT-based models** for classification, and **Regex** for some manual text segmentation.

