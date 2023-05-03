<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| application | Application name | N/A | true |
| cluster | Cluster name | N/A | true |
| debug | Debug mode | false | false |
| ecspresso-version | Ecspresso version | v2.1.0 | false |
| image | Docker image | N/A | true |
| image-tag | Docker image tag | N/A | true |
| operation | Operation (valid options - `deploy`, `destroy`) | deploy | true |
| region | AWS Region | N/A | true |
| taskdef-path | Task definition path | N/A | true |
| timeout | Ecspresso timeout | 5m | false |


## Outputs

| Name | Description |
|------|-------------|
| webapp-url | Web Application url |
<!-- markdownlint-restore -->
