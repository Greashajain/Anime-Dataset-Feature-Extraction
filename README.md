# Anime-Dataset-Feature-Extraction
Extracted meaningful features like episode count, airing period, and total runtime in months from an anime dataset using Python and pandas.


This project demonstrates how to extract meaningful features from an anime dataset using Python and pandas. The original dataset includes anime titles with embedded metadata such as episode count and airing dates. By parsing these strings, we create clean, structured columns ready for analysis.

---

## 📁 Dataset

- File: `anime.csv`


## 🛠️ Technologies Used

- Python 3.x
- pandas
- datetime
- dateutil (for `relativedelta`)


## 🔍 Features Extracted

- **Episodes**: Extracted from the title using string parsing.
- **Total Time**: Start and end airing dates extracted after the episode info.
- **Months**: Calculated duration of airing using Python’s `datetime` and `dateutil`.
