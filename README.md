What are the benefits of commits?
Die Verwendung von Commit-Scopes vereinfacht das Design Ihrer Anwendungsprogramme durch einen geringeren Bedarf an Fehlerbehebungsroutinen und verkürzt Ihre Codierungs- und Testphasen.

Is there another way to verify a commit was created?
Sie können GPG verwenden, um Commits mit einem selbst erzeugten GPG-Schlüssel zu signieren.

How to check if a file is tracked and if not, then track it?
können Sie den folgenden Befehl verwenden
    git ls-files --error-unmatch <filename>

git add <filename>
git commit -m "Commit message"

In which situation should you use `git diff`?
    Unveränderte Änderungen anzeigen
    Commits vergleichen
    Änderungen vor dem Commit überprüfen
    Branches vergleichen

How do you create a patch with `git diff`?
    git diff > my_patch.patch
    git apply my_patch.patch