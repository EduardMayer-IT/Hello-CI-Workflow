# Hello-CI-Workflow

Erstellung eines einfachen
GitHub-Workflows

Ziel: Erstelle einen einfachen GitHub-Workflow für ein neues Repository, der
automatisch bei jedem Push-Event auf dem Main-Branch ausgelöst wird. Der
Workflow soll zunächst eine Ausgabe "Hello, CI Workflow!" generieren und
anschließend um einen weiteren Schritt erweitert werden, der die Begrüßung
"Welcome to CI Workflow!" ausgibt.
Schritte:
1. GitHub-Repository erstellen: Erstelle ein neues GitHub-Repository für eine
einfache Anwendung.
2. GitHub Actions-Workflow erstellen:
a) Navigiere zur "Actions"-Registerkarte in deinem Repository.
b) Klicke auf "Set up a workflow yourself" und füge einen Workflow hinzu,
der automatisch bei jedem Push-Event auf dem Main-Branch ausgelöst
wird.
c) Füge den gegebenen einfachen Workflow hinzu.
3. Workflow testen (erster Schritt):
a) Mache eine kleine Änderung in deinem Repository, z.B., füge einen
Kommentar hinzu.
b) Commite und pushe die Änderungen.
c) Überprüfe den "Actions"-Tab, um sicherzustellen, dass der Workflow
automatisch gestartet wurde und die Ausgabe "Hello, CI Workflow!"
enthält.

4. Weiteren Schritt hinzufügen: Füge dem Workflow einen weiteren einfachen
Schritt hinzu, der eine Begrüßung ausgibt.
5. Workflow testen (zweiter Schritt):
a) Mache erneut eine kleine Änderung in deinem Repository.
b) Commite und pushe die Änderungen.
c) Überprüfe den "Actions"-Tab, um sicherzustellen, dass der Workflow
automatisch gestartet wurde und die Ausgaben "Hello, CI Workflow!"
und "Welcome to CI Workflow!" enthält.
############
Dieser Code definiert einen GitHub Actions Workflow namens "Einfacher CI Workflow". Der Workflow wird ausgelöst, wenn ein Push-Event auf dem Main-Branch des Repositories stattfindet.

Der Workflow besteht aus einem Job namens "build", der auf einem virtuellen Ubuntu-Server ausgeführt wird. Dieser Job enthält zwei Schritte:

1. Der erste Schritt, "Begrüßung 1", führt den Befehl `echo "Hello, CI Workflow!"` aus. Dieser Befehl gibt die Zeichenkette "Hello, CI Workflow!" in der Konsole aus.

2. Der zweite Schritt, "Begrüßung 3", führt den Befehl `echo "Welcome to CI Workflow!"` aus. Dieser Befehl gibt die Zeichenkette "Welcome to CI Workflow!" in der Konsole aus.

Es gibt einen Kommentar neben dem Namen des zweiten Schritts, der darauf hinweist, dass der Name des Schritts ursprünglich "Begrüßung 2" war und dann in "Begrüßung 3" geändert wurde, bevor er wieder rückgängig gemacht wurde. Es ist wichtig zu beachten, dass der Name des Schritts keine Auswirkungen auf die Ausführung des Workflows hat. Er dient lediglich dazu, den Schritt in der Workflow-Definition und in den Workflow-Logs zu identifizieren.