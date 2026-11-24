# PageForge

**A free word processor that runs in your web browser.** Write, format, review and export documents, including Word (.docx) files. Nothing is installed and nothing is uploaded: your documents stay on your own device.

Live app: **https://ashir-mansuri.github.io/pageforge/**

Created by **Ashir Mansuri**.

---

## Put it on GitHub Pages

1. Sign in to github.com and create a new **public** repository named `pageforge`.
2. Click **Add file › Upload files** and drag in all of these files (no folders are needed):
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md`, `LICENSE`
3. Click **Commit changes**.
4. Go to **Settings › Pages**. Under *Build and deployment*, choose **Deploy from a branch**, then branch **main** and folder **/ (root)**, and click **Save**.
5. Wait a minute or two, then open `https://ashir-mansuri.github.io/pageforge/`.

To update the app later, upload the new `index.html` over the old one. If the old version still shows, refresh the page twice: the app keeps an offline copy.

---

## What it does

| Area | Highlights |
|---|---|
| **Page setup and layout** | Real page view with live page breaks, A4/Letter/Legal and custom sizes, margins, portrait and landscape per section, section breaks, columns, headers and footers (first page, odd/even), page numbers in several formats, watermarks, page colour, page borders, line numbers, hyphenation |
| **Text and typography** | Fonts, sizes, colours, highlight, effects, character spacing, styles and style sets, themes, multilevel lists, heading numbering, drop caps, format painter, change case, paragraph spacing and indents, keep-with-next and widow control |
| **Tables, visuals and objects** | Tables with merge/split, header rows that repeat, table styles and formulas; pictures with cropping, filters and text wrapping; charts (10 types, with a data sheet or a linked Excel/CSV file); SmartArt; shapes; icons; text boxes; WordArt; equations (LaTeX or gallery); ink drawing; video links; symbols |
| **Long documents and academic work** | Table of contents, footnotes and endnotes, citations in APA, MLA, Chicago, Harvard and IEEE with a bibliography, BibTeX/RIS import, captions and table of figures, cross-references, index, table of authorities, bookmarks, navigation pane, combining chapters into a book |
| **Writing, proofing and AI** | Spelling and grammar checks, clarity and conciseness suggestions, readability scores, AutoCorrect, text predictions (press Tab), dictation including Indian languages, read aloud, transcription, accessibility checker, thesaurus, dictionary, Smart Lookup, translation, similarity check against your sources, and an optional AI assistant |
| **Review and collaboration** | Track changes, comments with replies and @mentions, accept/reject, markup views, compare two documents, combine reviews from several people, version history, sharing by email |
| **Automation, developer tools and mailings** | Find and replace with wildcards and formatting, content controls and fillable forms with XML/JSON/CSV data, macro recorder and script editor, batch-running macros on many files, mail merge from Excel/CSV/contacts with rules, envelopes and labels |
| **Security and file formats** | Password encryption (AES-256), password to modify, restrict editing, Document Inspector, sensitivity labels, digital signatures and signature lines; opens and saves .docx, .dotx, .odt, .rtf, .html, .md, .txt and PDF export; opens text from PDFs; offline use as an installable app |

Ready-made templates include a report, APA paper, resume, cover letter, letter, newsletter, brochure, invoice, meeting minutes, lesson plan, assignment form, legal agreement, proposal, memo, certificate and a mail-merge letter.

---

## Privacy

- Documents are saved inside your browser on your device (IndexedDB). They are not sent anywhere.
- Clearing your browser data deletes them, so use **File › Save** to download copies, or **File › Options › Back up all documents** now and then.
- A few optional tools contact free public services only when you use them: thesaurus (Datamuse), dictionary (dictionaryapi.dev), Smart Lookup (Wikipedia) and translation (MyMemory). Only the word or text you look up is sent.
- The AI assistant works offline for summaries and outlines. If you add your own Claude API key in **Options**, your text is sent to Anthropic when you ask the assistant. The key stays in your browser.

---

## Honest limits

- **No live co-editing.** People cannot type in the same document at the same time. Review works by sharing files, then using *Compare* or *Combine*.
- **Similarity check** compares your text only with sources you paste or open. It is not an internet plagiarism scanner.
- **PDF opening is text only.** Layout, images and scanned pages are not recovered.
- **Old binary .doc files** (Word 97–2003) cannot be opened. Save them as .docx first. PageForge can *save* a .doc that Word opens.
- **VBA macros** inside Word files are kept out and not run. PageForge macros use JavaScript.
- **3D models** are not supported.
- **Sensitivity labels and restrictions** are enforced inside PageForge only. Anyone with the file and another program can ignore them; use a password for real protection.
- **Digital signatures** prove the document has not changed since signing. They do not prove who the signer is, since there is no certificate authority.
- Word files keep almost everything, but very complex Word layouts may look slightly different when opened here.

---

## Works best in

Chrome, Edge or Brave on a computer. Firefox and Safari work too, but dictation and a few file features depend on the browser.

---

## Licence

MIT. See `LICENSE`.
