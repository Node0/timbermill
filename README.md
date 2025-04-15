# Project Timbermill

**OCR-powered chat session renderer that slices long conversations into paginated, searchable PDFs.**

Timbermill processes full-length ChatGPT-style conversation screenshots or PDFs by cutting them into equal-length pages at logical whitespace breaks using OpenCV. Once segmented, each page is either OCR’d individually before assembly or assembled into a unified PDF with embedded searchable text, depending on pipeline strategy. This project aims to streamline the archival and export of mobile LLM chat logs, especially from iOS where traditional exports are cumbersome. It is designed for short-lived, high-utility deployment.
