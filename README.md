# Jarvis Beta

Jarvis ist ein deutschsprachiger Sprachassistent für Windows 11: „Hey Jarvis“ sagen, Frage stellen, Antwort hören. Er läuft lokal auf deinem PC (Ollama) und optional über kostenlose Cloud-Modelle (OpenRouter).

**Download:** [Releases](../../releases/latest) → `JarvisSetup-0.9.0-beta.exe` doppelklicken. Die Einrichtung führt dich durch alles.

## Voraussetzungen
- Windows 11, Mikrofon, Internet für die Einrichtung
- Lokal: NVIDIA-Grafikkarte mit mindestens 6 GB (empfohlen 8 GB), etwa 35 GB freier Platz
- Nur Cloud: kein Grafikkarten-Anspruch, dafür ein kostenloses [OpenRouter](https://openrouter.ai)-Konto und ein eigener Schlüssel

## Hinweise
- Die Datei ist nicht signiert. Zeigt Windows „Der Computer wurde durch Windows geschützt“: **Weitere Informationen → Trotzdem ausführen**.
- Die Stimme (Microsoft Edge-TTS) braucht Internet.
- Kostenlose OpenRouter-Modelle können Eingaben protokollieren. Die Cloud ist standardmäßig aus und nur nach deiner Zustimmung aktiv.
- Jarvis kann Apps öffnen, Tasten drücken und den PC herunterfahren; riskante Aktionen fragt er vorher ab. Nutzung auf eigene Verantwortung, Beta ohne Gewähr.
- Deine Daten liegen in `%LOCALAPPDATA%\Jarvis` und `Dokumente\Jarvis-Vault`; Deinstallieren lässt sie stehen.
- Probleme? `%LOCALAPPDATA%\Jarvis\jarvis.log` mitschicken.

Der Quellcode ist (noch) nicht öffentlich.
