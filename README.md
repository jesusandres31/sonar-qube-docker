# Run SonarQube in Docker

### login
- usr: admin
- pss: admin

### bugfix sonar not starting:
`https://stackoverflow.com/questions/51445846/elasticsearch-max-virtual-memory-areas-vm-max-map-count-65530-is-too-low-inc`

### run:
- install "sonar-scanner" in localhost
- add "sonar-scanner" to your path var
- add "sonar-project.properties" file in root path of the project
- run "sonar-scanner"

### "sonar-project.properties" example:
```
sonar.projectKey=yourproject
sonar.projectName=yourproject
sonar.projectVersion=0.1
sonar.sources=src/
sonar.user=admin
sonar.password=root
```

