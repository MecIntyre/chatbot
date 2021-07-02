<h1>Beschreibung</h1>

Ein Chatbot mit verschiedenen Oberflächen. Beispiel für objektorientierte Programmierung und die Verwendung von Frameworks.
Zusätzlich: Verwendung von Docker und CI/CD für Test und Verteilung.

<h1>Installation</h1>

  git clone https://github.com/JoergEF/chatbot_new
  cd chatbot_new
  mkdir v3/model

<h1>Benutzung</h1>

	from chatbot_ai import chatbot_ai
	bot = chatbot_ai(jsonfile)
	bot.set_Message(eingabe)
	ausgabe = bot.get_Response()
  
