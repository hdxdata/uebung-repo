# GitHub Übungstutorial: Kompletter Git-Workflow

## Inhalt

1. Repository erstellen
2. Repository klonen
3. Branch erstellen
4. Änderungen committen
5. Branch pushen
6. Pull Request erstellen
7. Pull Request mergen
8. Branch löschen

## 1. Repository auf GitHub erstellen

1. Gehe zu github.com
2. Klicke auf **New Repository**
3. Gib einen Namen ein, z.B. uebung-repo
4. Wähle **Public** oder **Private**

## 2. Repository lokal klonen
```
git clone https://github.com/hdxdata/uebung-repo.git
cd uebung-repo
```

## 3. Neuen Branch erstellen
```
git checkout -b feature-xyz
```

## 4. Änderungen vornehmen und committen
```
echo "print('Hello World')" > main.py
git add main.py
git commit -m "Feature: main.py hinzugefügt"
```

## 5. Branch zu GitHub pushen
```
git push origin feature-xyz
```

## 6. Pull Request erstellen

Gehe auf GitHub:
- GitHub erkennt den neuen Branch
- Klicke auf **Compare & pull request**
- Füge Titel und Beschreibung hinzu
- Klicke auf **Create pull request**

## 7. Pull request mergen

Nach Review:
- Klicke auf **Merge pull request**
- Bestätige mit **Confirm merge**

## 8. Branch löschen
```
git branch -d feature-xyz # lokal löschen
git push origin --delete feature-xyz # auf GitHub löschen
```
