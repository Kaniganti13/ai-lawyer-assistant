# AI Lawyer Assistant ⚖️

An intelligent JavaFX-based desktop application that helps users analyze legal cases, generate structured legal arguments, and draft counter-arguments using AI.

---
### Download Full Project Here:

https://drive.google.com/drive/folders/1ALfJua5k1Y9FoxzSCmkGOuTagfKds9Rh?usp=drive_link

---


## 🚀 Features

- 📝 Enter legal case summaries manually
- 📂 Upload legal documents (PDF, DOCX, TXT)
- 🤖 AI-powered legal case analysis
- 💬 Generate counter-arguments automatically
- 🌍 Multi-language legal analysis support
- 📄 Document parsing and text extraction
- 🎨 Modern JavaFX desktop interface
- 💾 Export-ready legal analysis

---

## 🛠️ Technologies Used

- Java 17
- JavaFX
- Maven
- OkHttp
- Gson
- Apache PDFBox
- Apache POI
- OpenAI / Gemini API

---

## 📁 Project Structure

```text
major_pro/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/ailawyer/
│   │   │       ├── App.java
│   │   │       ├── controller/
│   │   │       ├── model/
│   │   │       └── service/
│   │   └── resources/
│   │       ├── fxml/
│   │       └── css/
├── pom.xml
└── README.md
```

---

## ⚙️ Prerequisites

Before running the project, install:

- Java 17 or higher
- Maven 3.6 or higher
- VS Code / IntelliJ IDEA

Check versions:

```bash
java -version
mvn -version
```

---

## 🔑 API Configuration

Open:

```text
src/main/java/com/ailawyer/service/AIService.java
```

Update your API key:

```java
private static final String API_KEY = "YOUR_API_KEY_HERE";
```

⚠️ Never upload API keys to GitHub.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Kaniganti13/ai-lawyer-assistant.git
```

### 2. Navigate to Project Folder

```bash
cd major_pro
```

### 3. Build the Project

```bash
mvn clean install
```

### 4. Run the Application

```bash
mvn javafx:run
```

---

## 📥 Download Full Project Files

Some AI speech recognition model files are very large and exceed GitHub's recommended upload limits.

To keep the repository lightweight and maintain faster cloning and better performance, the complete project files including AI models are provided through Google Drive.


## 💡 How It Works

1. Enter legal case details
2. Upload supporting legal documents
3. Click “Analyze Case”
4. AI generates legal arguments and reasoning
5. Generate counter-arguments if needed
6. Export and use generated analysis

---

## 🔒 Security Notes

- Never commit API keys
- Use environment variables for sensitive credentials
- Keep `.env` and config files private

---

## 🌟 Future Enhancements

- Voice input/output
- Case law database integration
- Collaboration features
- AI citation generator
- Court filing preparation
- Advanced legal analytics

---

## ⭐ Support

If you like this project, consider giving it a star on GitHub.
