# report-template
Template for LaTeX coursework reports. Uses [cookiecutter](https://github.com/audreyr/cookiecutter) to create new projects with the template report easily. Based on [this](https://github.com/selimb/cookiecutter-latex-article) latex cookiecutter project, but with my personal styles/settings.

## Usage
`cookiecutter` is needed to generate the template

``` 
pip install cookiecutter
```
The report template can then be generated

```
cookiecutter https://github.com/12yuens2/report-template.git
```
Relevant information such as title/author can be filled in on the CLI or left blank for the defaults.

## TODO
In no particular order:
- [x] Organise `.sty` files into some directory rather than all top level
- [ ] Option for either monolithic `Report.tex` or split into `main.tex` with subfiles
- [ ] Sample entry in bibliography
- [ ] Sample entry in appendix
- [x] Import graph plotting macros from previous coursework
