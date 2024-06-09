# private-repo

- Create Personal Access Token
- Add entry to  `~/.m2/settings.xml`
```
<settings>
<servers>
  <server>
    <id>github</id>
    <username>VeitWeber</username>
    <password>PERSONAL_ACCESS_TOKEN</password>
  </server>
</servers>
</settings>
```

## Sybase JDBC Driver (jconn4)
### Deploy
`mvn deploy:deploy-file -DgroupId=jdbc.sybase -DartifactId=jconn4 -Dversion=16.0 -Dpackaging=jar -Dfile=/Users/veit/Library/CloudStorage/Dropbox/development/source/abx/jconn4.jar -Durl=https://maven.pkg.github.com/VeitWeber/private-repo -DrepositoryId=github`
### Use


