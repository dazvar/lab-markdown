# Лабораторна робота №3
**Тема:** Markdown — створення документа, діаграми та публікація на GitHub  

**Короткий опис:**  
У цій лабораторній роботі ми створимо структурований документ у Markdown, навчимося додавати формули, таблиці та діаграми.  
Документ буде конвертований у формати HTML, DOCX та PDF, а також опублікований на GitHub.  
Markdown дозволяє зручно оформлювати текст і легко його оновлювати.  
Використання Mermaid допомагає візуалізувати процеси у вигляді діаграм.

---

## 1. My Favorite Books

1. "1984" — George Orwell  
2. "The Great Gatsby" — F. Scott Fitzgerald  
3. "To Kill a Mockingbird" — Harper Lee  
4. "The Catcher in the Rye" — J.D. Salinger  
5. "Pride and Prejudice" — Jane Austen  

---

## 2. Known Formulas

Інлайн приклад: $E = mc^2$  

Блочні формули:
$$
a^2 + b^2 = c^2
$$

Ще одна:
$$
\int_0^{\pi} \sin(x) \, dx = 2
$$

---

## 3. Simple Diagram (Mermaid)

```mermaid
flowchart TD
    A[Start] --> B[Write Markdown]
    B --> C{Add Formulas?}
    C -->|Yes| D[Insert LaTeX]
    C -->|No| E[Continue]
    D --> F[Add Diagram]
    E --> F
    F --> G[Export via Pandoc]
    G --> H[Publish on GitHub]

## 4. Table of Favorite Books

| № | Book Title | Author | Pages |
|---|-------------|---------|--------|
| 1 | 1984 | George Orwell | 328 |
| 2 | The Great Gatsby | F. Scott Fitzgerald | 218 |
| 3 | To Kill a Mockingbird | Harper Lee | 336 |
| 4 | The Catcher in the Rye | J.D. Salinger | 277 |
| 5 | Pride and Prejudice | Jane Austen | 432 |

---

## 5. Conclusions

During this lab work, I learned how to create documents in Markdown format, insert formulas, tables, and diagrams.  
Markdown is a convenient way to write documentation that can be easily converted to different formats and published on GitHub.  
Mermaid diagrams help visualize processes clearly and simply.
