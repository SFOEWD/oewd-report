# oewd-report

## Installing

If you are starting a new Quarto project, the template can be instantiated with the following command:

```bash
quarto use template SFOEWD/oewd-report
```

Otherwise, if you have an existing Quarto project:

```bash
quarto install template SFOEWD/oewd-report
```

Then update the YAML header of your Quarto document:

```YAML
format:
  oewd-report-html: default
```

Note that [the sficons extension](https://github.com/SFOEWD/sficons) is also included.
