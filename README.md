# tf2-aws-vpc

This repository contains a [Terraform][] project that builds [Scenario 2: VPC
with Public and Private Subnets][scenario_two] from the [AWS documentation][].

## Usage

`variables.tf` holds variables which should be overriden with valid ones.

### Plan

```
tf plan -var-file variables.tf 
```

### Apply

```
tf apply -var-file variables.tf 
```

### Destroy

```
tf destroy -var-file variables.tf 
```

### Sources

[Terraform]: http://terraform.io
[scenario_two]: http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Scenario2.html
[AWS documentation]: http://aws.amazon.com/documentation/
