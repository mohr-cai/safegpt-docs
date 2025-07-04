# BusinessGPT Dokumentation

Dieses Repository enthält die Dokumentation für BusinessGPT powered by Eraneos. Die Dokumentation umfasst:

- Produktfunktionen und -fähigkeiten
- Erste Schritte Anleitungen

### Entwicklung

Installieren Sie die [Mintlify CLI](https://www.npmjs.com/package/mintlify), um Dokumentationsänderungen lokal zu überprüfen. Verwenden Sie zur Installation den folgenden Befehl

```
npm i -g mintlify
```

Führen Sie den folgenden Befehl im Stammverzeichnis Ihrer Dokumentation aus (wo sich docs.json befindet)

```
mintlify dev
```

### Änderungen veröffentlichen

Installieren Sie unsere Github App, um Änderungen von Ihrem Repository automatisch in Ihr Deployment zu übertragen. Änderungen werden nach dem Push zum Standardbranch automatisch in die Produktion übernommen. Den Link zur Installation finden Sie in Ihrem Dashboard.

#### Fehlerbehebung

- Mintlify dev läuft nicht - Führen Sie `mintlify install` aus, um die Abhängigkeiten neu zu installieren.
- Seite wird als 404 geladen - Stellen Sie sicher, dass Sie in einem Ordner mit `docs.json` arbeiten
