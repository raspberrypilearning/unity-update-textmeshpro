Je kunt de methode `SetText` gebruiken om de tekst bij te werken die wordt weergegeven door een TextMeshPro Gameobject.

Voeg een nieuw script toe of werk een bestaand script bij met een variabele om het TextMeshPro-object op te slaan en gebruik `SetText` om de tekst te wijzigen. Je moet `using TMPro` aan je script toevoegen.

--- code ---
---
language: cs
---
using TMPro;

public class TextUpdater: MonoBehaviour
{ public TMP_Text messageText;

  void Update() // Or other method
  {
    messageText.SetText("New message");
  }
} --- /code ---


Sleep het TextMeshPro GameObject dat je wilt bijwerken van het Hierarchy venster naar de bijbehorende scripteigenschap in de Inspector. 

