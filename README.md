# Nuclei Templates

* List of custom YAML based nuclei templates created to detect vulnerabilities in the web applications, APIs.

## Running Nuclei Templates with Nuclei

* Install nuclei from [here](https://github.com/projectdiscovery/nuclei)

* Run nuclei templates with target domain

```sh
nuclei -u https://target.com -t cross-origin-resource-sharing.yaml
```

* Run nuclei with list of URLs using templates

```sh
nuclei -l URLslist.txt -t custom-nuclei-templates/
```

* Run nuclei templates as worflows with multiple templates

```sh
nuclei -u https://example.com -w workflow/workflow.yaml
```

* Run workflow against list of URLs

```sh
nuclei -l URLslist.txt -w workflow/workflow.yaml
```

---
#### To Do
- [ ] Add more templates related to web and mobile specific vulnerabilities.
- [ ] Add templates for source code review.
