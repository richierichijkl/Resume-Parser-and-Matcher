# Resume Matcher using Flask

A simple web app to match and rank resumes based on their similarity to a given job description using **TF-IDF** and **cosine similarity**.

---

## Tech Stack

| Layer         | Technologies Used                                            |
|---------------|--------------------------------------------------------------|
| **Frontend**  | HTML, CSS, Bootstrap 4                                       |
| **Backend**   | Python, Flask                                                |
| **Parsing**   | `docx2txt` (DOCX), `PyPDF2` (PDF), built-in `open()` for TXT |
| **ML/NLP**    | `scikit-learn` (TF-IDF, Cosine Similarity)                   |
| **Web Server**| Flask’s built-in dev server (can switch to Gunicorn)         |
| **Environment** | Conda (local env inside project folder)                   |

---

## Features

- Upload multiple resumes (.pdf, .docx, .txt)
- Enter a job description
- Ranks resumes based on similarity to the job description
- Displays top 5 matching resumes with similarity scores
- Clean UI using Bootstrap

---

## Contact

- GitHub: [@richierichijkl](https://github.com/richierichijkl)
- Email: rc28122003@gmail.com

