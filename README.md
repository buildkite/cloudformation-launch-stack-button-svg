# Cloudformation "Launch Stack" button in SVG

A nice, resolution independent, SVG version of the [AWS CloudFormation "Launch Stack" button](https://blogs.aws.amazon.com/application-management/post/Tx2YSVJV4VMPBHI/Construct-Your-Own-Launch-Stack-URL) :tada:

[![AWS CloudFormation Launch Stack SVG Button](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](launch-stack.svg)

Initially made for the [Elastic CI Stack for AWS](https://github.com/buildkite/elastic-ci-stack-for-aws).

## Usage

You can use it in GitHub Readmes like so:

```markdown
![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=buildkite&templateURL=https://s3.amazonaws.com/my-great-stack.json)
```

or with plain ol’ HTML:

```html
<a href="https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=buildkite&templateURL=https://s3.amazonaws.com/my-great-stack.json"><img alt="Launch Stack" src="https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg"></a>
```

## Source

[Launch Stack.sketch](Launch Stack.sketch) (Sketch 3)

## Licence

See [LICENSE](LICENSE) (MIT)