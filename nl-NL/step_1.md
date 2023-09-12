You can use the `SetText` method to update the text that is displayed by a TextMeshPro GameObject.

Either add a new script or update an existing one with a variable to store the TextMeshPro object and use `SetText` to change the text. You will need to add `using TMPro` to your script.

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


Drag the TextMeshPro GameObject that you want to update from the Hierarchy window to the corresponding script property in the Inspector. 

