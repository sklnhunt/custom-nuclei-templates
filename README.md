# Nuclei Templates

* List of custom YAML based nuclei templates created to detect vulnerabilities in the web applications, APIs.

### Running Nuclei Templates with Nuclei

* Install nuclei from [here](https://github.com/projectdiscovery/nuclei)

* Run nuclei with target domain

```
nuclei -u https://target.com -t cross-origin-resource-sharing.yaml
```

* Run nuclei with list of URLs

```
nuclei -l URLslist.txt -t custom-nuclei-templates/
```


---
#### To Do
- [ ] Add more templates related to web and mobile specific vulnerabilities.
- [ ] Add templates for source code review.
