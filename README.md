# Universal Web Crawler (.EXE Based)

This EXE crawls websites with dropdowns and tables — built using Selenium and packaged into a standalone EXE.

## 🧰 How to Use

1. Double-click `universal_crawler.exe`
2. Chrome will launch visibly
3. It will:
   - Select subject
   - Set term
   - Choose campus
   - Click "Search"
   - Extract table data from all paginated results
4. Saves to `output.xlsx`

## 🛠️ Configuration

Edit `config.json` to set:
- Target URL
- XPath for subject, button, table, pagination
- Output filename

## 🔄 Supported Features

- Headed Chrome
- Pagination
- Timeout handling
- Works across similar structured websites

---

To use on another site, update `config.json` with proper XPaths.
