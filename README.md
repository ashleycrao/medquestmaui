# medquestmaui

Dose Quest is an interactive pharmacology study app for first-year nursing students. It includes a curated starter set of 100 generic medication exemplars grouped by body system. This is a teaching selection, not an official NCLEX top-100 ranking.

## Open the app

Serve the repository as a static site (for example, with GitHub Pages) and open index.html in a modern browser. ES modules may not run when index.html is opened directly as a local file. The app has a medication library, body-system filters, flashcard practice, a short NCLEX-style nursing-safety quiz, patient teach-back practice, and an instructor activity snapshot.

Student names and progress are stored only in local browser storage on the device. This prototype does not provide authenticated student accounts or shared instructor analytics.

## Medication selection sources

- [2026 NCLEX-RN Test Plan (NCSBN)](https://www.ncsbn.org/public-files/2026_RN_Test%20Plan_English-F.pdf): test domains, including pharmacological/parenteral therapies and safe handling of high-risk medications. NCSBN does not publish a fixed medication list.
- [Nursing Pharmacology, 2e (Open RN / NCBI Bookshelf)](https://www.ncbi.nlm.nih.gov/books/NBK595000/): open nursing pharmacology textbook updated to the 2023 NCLEX-RN/PN plans.
- [Essential NCLEX Meds by Class (NURSING.com)](https://academy.nursing.com/lesson/01-04-essential-nclex-meds-by-class/): nursing education class/exemplar cross-check.
- [ISMP High-Alert Medications in Acute Care Settings (2024)](https://www.ismp.org/system/files/resources/2024-01/ISMP_HighAlert_AcuteCare_List_010924_MS5760.pdf): informs highlighted high-alert exemplars.
- [DailyMed](https://dailymed.nlm.nih.gov/dailymed/) and [FDA prescription labeling FAQ](https://www.fda.gov/drugs/fdas-labeling-resources-human-prescription-drugs/frequently-asked-questions-about-labeling-prescription-medicines): current product labeling and boxed-warning verification.

## Review before classroom use

The starter list is curated for study coverage. Medication-specific nursing checks, common side effects, red flags, boxed warnings, and patient teaching should be verified against the exact current product label and reviewed by the course instructor and pharmacist. This app is for education, not clinical decision-making.

Before using identifiable student data, replace local-only storage with a privacy-reviewed backend and establish class access, consent, retention, and security practices. The teach-back demo does not save audio; browser speech transcription behavior depends on browser settings and implementation.
