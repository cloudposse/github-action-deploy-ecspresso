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
| mirror\_to\_s3\_bucket | Mirror task definition to s3 bucket | N/A | false |
| operation | Operation (valid options - `deploy`, `destroy`) | deploy | true |
| region | AWS Region | N/A | true |
| taskdef-path | Task definition path | N/A | true |
| timeout | Ecspresso timeout | 5m | false |
| use\_partial\_taskdefinition | NOTE: Experimental. Load templated task definition from S3 bucket, which is created by the `ecs-service` component. This is useful when you want to manage the task definition in the infrastructure repository and the application repository. The infrastructure repository manages things like Volumes and EFS mounts, and the Application repository manages the application code and environment variables. | N/A | false |


## Outputs

| Name | Description |
|------|-------------|
| webapp-url | Web Application url |
<!-- markdownlint-restore -->
