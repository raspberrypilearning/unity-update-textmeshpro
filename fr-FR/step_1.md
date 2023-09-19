Tu peux utiliser la méthode `SetText` pour mettre à jour le texte qui est affiché par un GameObject TextMeshPro.

Soit tu ajoutes un nouveau script, soit tu mets à jour un script existant avec une variable pour stocker l'objet TextMeshPro et tu utilises `SetText` pour modifier le texte. Tu devras ajouter `using TMPro` à ton script.

--- code ---
---
language: cs
---
using TMPro;

public class MiseajourTexte: MonoBehaviour
{
  public TMP_Text messageTexte;

  void Update() // Ou une autre méthode
  {
    messageTexte.SetText("Nouveau message");
  }
}
--- /code ---


Fais glisser le GameObject TextMeshPro que tu veux mettre à jour depuis la fenêtre Hierarchy vers la propriété de script correspondante dans l'Inspector. 

