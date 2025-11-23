## ✅[MegaLinter](https://megalinter.io/9.1.0) analysis: Success



| Descriptor  |                                               Linter                                                |Files|Fixed|Errors|Warnings|Elapsed time|
|-------------|-----------------------------------------------------------------------------------------------------|----:|----:|-----:|-------:|-----------:|
|✅ ACTION    |[actionlint](https://megalinter.io/9.1.0/descriptors/action_actionlint)                              |    2|     |     0|       0|       0.24s|
|✅ COPYPASTE |[jscpd](https://megalinter.io/9.1.0/descriptors/copypaste_jscpd)                                     |  yes|     |    no|      no|       0.93s|
|✅ JSON      |[jsonlint](https://megalinter.io/9.1.0/descriptors/json_jsonlint)                                    |    1|     |     0|       0|       0.14s|
|✅ JSON      |[prettier](https://megalinter.io/9.1.0/descriptors/json_prettier)                                    |    1|    0|     0|       0|       0.28s|
|✅ JSON      |[v8r](https://megalinter.io/9.1.0/descriptors/json_v8r)                                              |    1|     |     0|       0|       2.61s|
|✅ MARKDOWN  |[markdownlint](https://megalinter.io/9.1.0/descriptors/markdown_markdownlint)                        |   24|    0|     0|       0|       0.83s|
|✅ MARKDOWN  |[markdown-table-formatter](https://megalinter.io/9.1.0/descriptors/markdown_markdown_table_formatter)|   24|    0|     0|       0|       0.27s|
|✅ REPOSITORY|[gitleaks](https://megalinter.io/9.1.0/descriptors/repository_gitleaks)                              |  yes|     |    no|      no|       0.11s|
|✅ REPOSITORY|[git_diff](https://megalinter.io/9.1.0/descriptors/repository_git_diff)                              |  yes|     |    no|      no|       0.01s|
|✅ REPOSITORY|[grype](https://megalinter.io/9.1.0/descriptors/repository_grype)                                    |  yes|     |    no|      no|      26.42s|
|✅ REPOSITORY|[secretlint](https://megalinter.io/9.1.0/descriptors/repository_secretlint)                          |  yes|     |    no|      no|       0.51s|
|✅ REPOSITORY|[syft](https://megalinter.io/9.1.0/descriptors/repository_syft)                                      |  yes|     |    no|      no|       0.99s|
|✅ REPOSITORY|[trivy](https://megalinter.io/9.1.0/descriptors/repository_trivy)                                    |  yes|     |    no|      no|       4.73s|
|✅ REPOSITORY|[trivy-sbom](https://megalinter.io/9.1.0/descriptors/repository_trivy_sbom)                          |  yes|     |    no|      no|        0.1s|
|✅ REPOSITORY|[trufflehog](https://megalinter.io/9.1.0/descriptors/repository_trufflehog)                          |  yes|     |    no|      no|       2.17s|
|✅ SPELL     |[lychee](https://megalinter.io/9.1.0/descriptors/spell_lychee)                                       |   30|     |     0|       0|       1.47s|
|✅ YAML      |[prettier](https://megalinter.io/9.1.0/descriptors/yaml_prettier)                                    |    5|    0|     0|       0|       0.39s|
|✅ YAML      |[v8r](https://megalinter.io/9.1.0/descriptors/yaml_v8r)                                              |    5|     |     0|       0|       4.52s|
|✅ YAML      |[yamllint](https://megalinter.io/9.1.0/descriptors/yaml_yamllint)                                    |    5|     |     0|       0|       0.29s|

See detailed reports in MegaLinter artifacts


Your project could benefit from a custom flavor, which would allow you to run only the linters you need, and thus improve runtime performances. (Skip this info by defining `FLAVOR_SUGGESTIONS: false`)

  - Documentation: [Custom Flavors](https://megalinter.io/9.1.0/custom-flavors/)
  - Command: `npx mega-linter-runner@9.1.0 --custom-flavor-setup --custom-flavor-linters ACTION_ACTIONLINT,COPYPASTE_JSCPD,JSON_JSONLINT,JSON_V8R,JSON_PRETTIER,MARKDOWN_MARKDOWNLINT,MARKDOWN_MARKDOWN_TABLE_FORMATTER,REPOSITORY_GIT_DIFF,REPOSITORY_GITLEAKS,REPOSITORY_GRYPE,REPOSITORY_SECRETLINT,REPOSITORY_SYFT,REPOSITORY_TRIVY,REPOSITORY_TRIVY_SBOM,REPOSITORY_TRUFFLEHOG,SPELL_LYCHEE,YAML_PRETTIER,YAML_YAMLLINT,YAML_V8R`

[![MegaLinter is graciously provided by OX Security](https://raw.githubusercontent.com/oxsecurity/megalinter/main/docs/assets/images/ox-banner.png)](https://www.ox.security/?ref=megalinter)