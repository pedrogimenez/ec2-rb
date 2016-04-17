# ec2-rb
SSH into EC2 using the instance name

It uses the AWS credentials from `~/.aws/credentials`.

☝🏻 Don't forget to set the `AWS_REGION` env variable.

## Setup:

```sh
$ script/setup
```

## Usage:

```sh
$ AWS_REGION=eu-west-1 ec2 ssh instancename
$ AWS_REGION=eu-west-1 ec2 ip instancename
```
