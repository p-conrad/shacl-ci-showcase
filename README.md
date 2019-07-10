# SHACL CI Showcase

This is a sample repository to demonstrate the usage of Travis CI and GitLab CI with the
[SHAC-CI](https://github.com/fusion-jena/SHACL-CI) tool for automatic validation of ontologies.
This repository can be viewed both on [GitHub](https://github.com/p-conrad/shacl-ci-showcase) and
[GitLab](https://gitlab.com/p-conrad/shacl-ci-showcase). It contains a simple persons ontology with
according SHACL shapes, where the introduction of a new faulty individual causes a validation error.

To learn more about SHACL-CI and its purpose, please visit its
[source repository](https://github.com/fusion-jena/SHACL-CI).


## How to View the Test Results

* GitHub: Open the [commit section](https://github.com/p-conrad/shacl-ci-showcase/commits/add-dory)
  and click on the ✓ or X marks. There you can see more about the build details.
* GitLab: Open the [CI / CD](https://gitlab.com/p-conrad/shacl-ci-showcase/pipelines) section to
  view individual builds. Additionally, you can inspect individual failures by opening the
  [merge request](https://gitlab.com/p-conrad/shacl-ci-showcase/merge_requests/1).

## Authors

This repository is part of the SHAC-CI project, which has been authored by Peter Conrad with
guidance from [Jan Martin Keil](https://github.com/jmkeil), Friedrich Schiller University Jena.
