# 🤖 ChatBot — C# / WinForms

A desktop chatbot built with **C# (WinForms)** and the **AIMLbot** library.
It comes with a large built-in AIML knowledge base covering everything from
personality chat, science and geography to movies, music and stories.

## ✨ Features
- Conversational AI using the classic AIML rule engine
- 40+ AIML knowledge files (ALICE-style knowledge base)
- Chat bubble UI with Bunifu controls
- Speech-friendly responses (System.Speech)

## 🛠️ Getting Started (Visual Studio)

1. Open `ChatBotProject.sln` in Visual Studio (2017+ / .NET Framework 4.6.1)
2. Restore NuGet packages if prompted
3. Press **F5** to build & run

The AIML knowledge files and required DLLs are copied automatically to the
output folder on build (see `ChatBotProject.csproj`).

## 📁 Structure
```
├── ChatBotProject.sln
└── ChatBotProject/
    ├── ChatBot.cs / Program.cs   # Main logic
    ├── bubble.cs                 # Chat bubble UI
    ├── aiml/                     # 40+ AIML knowledge files
    └── lib/                      # AIMLbot + Bunifu DLLs
```

## 📄 License
MIT
