#GoCD YAML based pipeline definitions 
This repository conatins sample Kubernetes build and deploy pipeline definitions. 

These samples use the [GoCD YAML Config plug](https://github.com/tomzo/gocd-yaml-config-plugin). You need to add this snipped to your GoCD XML configuration:
```xml
<config-repos>
  <config-repo plugin="yaml.config.plugin">
    <git url="https://github.com/tomzo/gocd-yaml-config-example.git" />
  </config-repo>
</config-repos>
```
