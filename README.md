# chatbot_ai

### Beschreibung
in Chatbot mit verschiedenen Oberflächen. Beispiel für objektorientierte Programmierung und die Verwendung von Frameworks.
Zusätzlich: Verwendung von Docker und CI/CD für Test und Verteilung.

### Versionen
1. v3: Chatbot mit künstlicher Intelligenz

### Installation
```bash
git clone https://github.com/JoergEF/chatbot_ai
cd chatbot_ai
mkdir v3/model
```

### Benutzung
- v3:
```python
	from chatbot_ai import chatbot_ai
	bot = chatbot_ai(jsonfile)
	bot.set_Message(eingabe)
	ausgabe = bot.get_Response()
```

