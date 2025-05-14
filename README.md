# 🕸️ MTWebCrawler (Java)

**MTWebCrawler** is a multithreaded Java-based web crawler that navigates through websites, extracts internal links, and prints page titles in real time. Each bot runs as its own thread, simulating how real-world crawlers index content efficiently and concurrently.

---

## ✅ Features

- Multithreaded crawling using custom bots  
- Extracts webpage titles and internal URLs  
- Supports multiple domains (ABC News, NPR, NYTimes, etc.)  
- Built with JSoup for reliable HTML parsing  
- Simple command-line execution

---

## 📦 Technologies Used

- **Java**  
- **JSoup 1.16.1** (external library for HTML parsing)  
- **Multithreading**

---

## 🗂️ Project Structure

```
MTWebCrawler/
├── lib/
│   └── jsoup-1.16.1.jar
├── src/
│   └── mtWebCrawler/
│       ├── Main.java
│       └── WebCrawler.java
├── screenshots/
│   ├── screenshot-1-start.png
│   ├── screenshot-2-crawling.png
│   ├── screenshot-4-diverse-links.png
│   └── screenshot-5-finish.png
├── .classpath
├── .project
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/Harris1250/MTWebCrawler.git
cd MTWebCrawler/src
```

### 2. Compile the Java code with JSoup
```bash
javac -cp ".;../lib/jsoup-1.16.1.jar" mtWebCrawler/*.java
```

### 3. Run the crawler
```bash
java -cp ".;../lib/jsoup-1.16.1.jar" mtWebCrawler.Main
```

---

## 📸 Screenshots

### 🧵 1. Crawler Compiled & Started
![Start](screenshots/screenshot-1-start.png)

### 🌐 2. Real-Time Crawling Output
![Crawling](screenshots/screenshot-2-crawling.png)

### 🔗 3. Link Coverage Across Domains
![Links](screenshots/screenshot-4-diverse-links.png)

### ✅ 4. Full Crawl Completion
![Finish](screenshots/screenshot-5-finish.png)

---

## 📊 Sample Output

```text
**Bot ID:1** Received Webpage at https://abcnews.go.com
ABC News - Breaking News, Latest News and Videos

**Bot ID:2** Received Webpage at https://npr.org
NPR - Breaking News, Analysis, Music, Arts & Podcasts

**Bot ID:3** Received Webpage at https://nytimes.com
The New York Times - US News, World News and Videos
```

---

## 🙌 Credits

- [JSoup](https://jsoup.org/) - Java HTML Parser  
- Developed by [Harris1250](https://github.com/Harris1250)

---

> “Scan fast. Index smart. Crawl deep.”
