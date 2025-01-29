<h1 align="center">
  <br>
  <img src="https://github.com/hei-templates/hei-synd-report/blob/51e8aea5b38bb51cba041bfc0ab769cc12f1a865/img/hei-en.svg" alt="HEI-Vs Logo" width="350">
  <br>
  HEI-Vs Engineering School - Systems Engineering
  <br>
</h1>
<div align="center">
  <br>
  <img src="https://github.com/hei-templates/hei-synd-report/blob/51e8aea5b38bb51cba041bfc0ab769cc12f1a865/img/synd-light.svg" alt="Industrial Systems Logo" width="350">
  <br>
</div>

![GitHub Repo stars](https://img.shields.io/github/stars/hei-templates/hei-synd-report)
![GitHub Release](https://img.shields.io/github/v/release/hei-templates/hei-synd-report?include_prereleases)

This is the official template for a students report or project or lab report for the [HEI-Vs Engineering School](https://synd.hevs.io) in Sion, Switzerland. More templates can the found in our [GitHub organization](https://github.com/hei-templates)

![](img/https://github.com/hei-templates/hei-synd-report/blob/51e8aea5b38bb51cba041bfc0ab769cc12f1a865/img/sample.png)

## Using the template

1. In the `Typst` Univers select the `hei-synd-report` template. Locally you can use the Typst CLI  to initialise the project:

   ```bash
   # from the typst universe
   typst init @preview/hei-synd-report:0.1.0

   # only if installed locally
   typst init @local/hei-synd-report:0.1.0
   ```

2. Fill in the metadata in the `metadata.typ` file.

3. Write your content in the `report.typ` file as well as the other files in the `main` folder.

## Usage

In order to build the `Typst` document locally you can use one of the following command:

```bash
# Create pdf
typst compile report.typ

# Create pdf and watch for changes
typst watch report.typ
```

## Features

- [x] All metadata is optional
- [x] Title page
- [x] Table of contents
- [x] Table of figures
- [x] Table of tables
- [x] Table of listings
- [x] Table of equations
- [x] Custom Boxes
- [x] Sourcecode with codelst
- [x] Glossary and Acronyms with Glossarium
- [x] Bibliography
- [x] Draft and Final Typesetting
- [x] Content help
   - [x] Introduction
   - [x] Analysis
   - [x] Design
   - [x] Implementation
   - [x] Validation
   - [x] Conclusion
- [ ] Wavedrom diagrams
- [ ] PlantUML diagrams

## Help

If you need help writting your document look at the [Typst documentation](https://typst.app/docs/) or if ou need more help with the template specifics look at the document [Guide-to-Typst](https://github.com/hei-templates/hei-synd-report/blob/51e8aea5b38bb51cba041bfc0ab769cc12f1a865/guide-to-typst.pdf).

## Contributing

We welcome contributions from students and faculty members of HEI-Vs Engineering School. If you would like to contribute to any of the repositories in this organization, please follow these steps:

1. Fork the repository you want to contribute to.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your branch to your forked repository.
5. Open a pull request in the original repository and describe your changes.

Please ensure that you follow the code of conduct and guidelines for contributing as outlined in each repository.

## Issues and Support

If you encounter any issues or have questions regarding the course or any of the repositories, please feel free to open an issue in the respective repository. Our team will be happy to assist you.

## Changelog

All notable changes to this project are documented in the [CHANGELOG.md](./CHANGELOG.md) file.

## Find us on

[hevs.ch](https://synd.hevs.io) &nbsp;&middot;&nbsp;
LinkedIn [HEI-Vs](https://www.linkedin.com/showcase/school-of-engineering-valais-wallis/) &nbsp;&middot;&nbsp;
LinkedIn [HES-SO Valais-Wallis](https://www.linkedin.com/groups/104343/) &nbsp;&middot;&nbsp;
Youtube [HES-SO Valais-Wallis](https://www.youtube.com/user/HESSOVS)
Twitter [@hessovalais](https://twitter.com/hessovalais) &nbsp;&middot;&nbsp;
Facebook [@hessovalais](https://www.facebook.com/hessovalais) &nbsp;&middot;&nbsp;
