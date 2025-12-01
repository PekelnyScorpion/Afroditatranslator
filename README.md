# Afroditatranslator
překladač
# Afrodita Translator – Vosk jazykové modely

Tento repozitář obsahuje jazykové modely pro [Vosk API](https://alphacephei.com/vosk), určené pro použití v mobilních aplikacích (Android).  
Modely jsou optimalizované pro mobilní zařízení (*small varianty*) a poskytují offline rozpoznávání řeči.

## 📦 Obsah
- Různé jazyky (EN, CS, DE, …) ve variantě *small*, vhodné pro Android a Raspberry Pi.
- Každý jazykový model je dostupný jako samostatný soubor (ZIP) v sekci [Releases](../../releases).
- Po stažení se model automaticky rozbalí a načte v aplikaci.

## ⚖️ Licence
Všechny zde hostované modely jsou open‑source a distribuovány pod licencí **Apache 2.0**.  
Prosím respektujte podmínky licence při použití a distribuci.

## 🔗 Oficiální projekt
- GitHub: [alphacep/vosk-api](https://github.com/alphacep/vosk-api)
- Web: [https://alphacephei.com/vosk](https://alphacephei.com/vosk)

## 🚀 Použití v aplikaci
Uživatel klikne na jazyk → aplikace stáhne příslušný ZIP z GitHub Releases → rozbalí ho do interní paměti → model se automaticky načte do Vosk API.

Příklad mapy jazyků → URL:
```kotlin
val modelUrls = mapOf(
    "en" to "https://github.com/uzivatel/repo/releases/download/v1.0/vosk-model-en.zip",
    "cs" to "https://github.com/uzivatel/repo/releases/download/v1.0/vosk-model-cs.zip",
    "de" to "https://github.com/uzivatel/repo/releases/download/v1.0/vosk-model-de.zip"
)
