@title[Introduction]

# Jenkins Shared Libraries

#### DRY for pipelines

---

@title[Features]

## <span class="gold">Features</span>

#### Reusable pipeline functions
#### Simple Groovy functions
#### Multiple scopes (Global, group, project)
#### Uses method overriding

---

@title[Before & now]

### <span class="gold">Before</span>
```shell
$ cat Jenkinsfile.old | wc -l
210
```

### <span class="gold">Now</span>
```shell
$ cat Jenkinsfile | wc -l
60
```

---

### Code

Global shared library: [https://github.com/tv2/devops-pipeline-gradle-global-library](https://github.com/tv2/devops-pipeline-gradle-global-library)

BE shared library: [https://github.com/tv2/play-be-pipeline-library](https://github.com/tv2/play-be-pipeline-library)