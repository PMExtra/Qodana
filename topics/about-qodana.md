[//]: # (title: About Qodana)

[![official project](https://jb.gg/badges/official-flat-square.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub)

**Qodana** is a smart code quality platform by JetBrains best suited for working in teams. 
It can analyze code written in 60+ languages including Java, JavaScript, TypeScript, PHP, Kotlin, Python, Go, and C#. 

## Run %product% in your CI/CD pipeline or locally

Qodana provides native solutions for [](qodana-azure-pipelines.md), [CircleCI](circleci.md), [GitHub](github.md), and
[TeamCity](teamcity.md). With other CI/CD systems, you can use [Docker images](docker-images.md). 

To run %product% locally, you can use [Docker images](docker-images.md), the
[%product% CLI](https://github.com/jetbrains/qodana-cli) tool, and [JetBrains IDEs](qodana-ide-plugin.md).

You can inspect your code using the default [inspection profiles](inspection-profiles.md#Default+profiles), which requires
no configuration steps and lets you run %product% out of the box. You can also configure the default inspection profiles or
create your own inspection profile in the [YAML](custom-profiles.md) and [XML](custom-xml-profiles.md) formats.

Finally, you can go beyond the existing inspections and [extend %product%](extending-qodana.xml).

## Improve the quality of your software

%product% reports provide detailed description of concrete problems and code fragments that contain such problems,
as well as recommendations about how to solve such problems. Using these recommendations, you can improve the quality of
your product by preventing bugs in production and learning from the process. For more details, you can study the 
[](ui-overview.md) section.

## Optimize code reviews

%product% ensures your code is healthy before it even enters the review and testing phase. Achieve quick wins like fewer 
bugs, vulnerabilities, and conflicting licenses, and meet long-term goals like maintainable code that makes it easy to 
ship new features and implement changes.

The inspection report will be uploaded to Qodana Cloud, so that you can view it in detail. Besides that, you can 
study %product% reports using [JetBrains IDEs](qodana-ide-plugin.md) and [Visual Studio Code](vscode.md).

Besides that, in GitHub %product% can inspect [pull requests](github.md#Pull+request+quality+gate).

## Enforce coding standards

Using %product% as a [quality gate](quality-gate.xml), you can decide the number of problems to cause a build fail, plan 
the problems to be solved right away and postponed by putting them to a [baseline](baseline.xml), or automatically apply 
suggested [quick-fixes](quick-fix.md) to let your team save time.

## Share reports with other team members

[Qodana Cloud](https://qodana.cloud) helps you accumulate %product% reports and track the progress in your project(s) 
from a single point. Such reports are available for all members of your team(s). To become more familiar with Qodana 
Cloud, visit the [](cloud-about.xml) page.

## Take advantage of our pricing model

%product% license costs under the Ultimate and Ultimate Plus licenses depend on the number of active contributors, and 
this lets you inspect an unlimited number of code lines.  

You can also run %product% under the free Community license; however, in this case %product% functionality will be
restricted. To compare %product% licenses, you can visit the [](pricing.md) page.

## Next steps

- <a href="Quick-start.xml">Quick start guide</a>
- <a href="https://www.jetbrains.com/qodana/request-a-demo/">Request a demo</a>
- <a href="features.xml">%product% features</a>

## Contact us

If you would like to suggest a new feature or encounter unexpected behaviour, use the 
<a href="https://youtrack.jetbrains.com/newIssue?project=QD">issue tracker</a> or email the support team at
<a href="mailto:qodana-support@jetbrains.com">qodana-support@jetbrains.com</a>.

To actively participate in the Qodana community, join our [GitHub Discussions forum](https://github.com/JetBrains/Qodana/discussions).
