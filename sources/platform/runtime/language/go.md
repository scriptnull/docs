page_main_title: Go Language Overview
main_section: Platform
sub_section: Job Runtime
sub_sub_section: Languages
page_title: Go Language Overview

# GO Job Images

Job Images for GO are available for multiple language / operating system versions. Each language-os combination
is published in Docker hub as an image with a specific tag. The Docker hub account where we publish these images is drydock.

If you specify the language and os in Shippable.yml, the platform automatically selects the right image for you. However,
you can also boot the job runtime with any image.

## Supported OS Versions
Language versions are available on the drydock links specified below for these OS versions.

|OS version| Docker image name | Tags |
|----------|------------|-----|
|Ubuntu 14.04|[drydock/u14golall](https://hub.docker.com/r/drydock/u14golall)|v5.7.3  v5.6.1  v5.5.1  v5.4.1  v5.3.2 |
|Ubuntu 16.04|[drydock/u16golall](https://hub.docker.com/r/drydock/u16golall)|v5.7.3  v5.6.1  v5.5.1  v5.4.1  v5.3.2 |

## Supported Language Versions
This table helps you choose the right tag for the language version that you are interested in and the
AMI that you should set for your subscription.

| Version  |  Tags    | Supported OS| Available AMIs|  
|----------|---------|-----------|---------------------|
|1.8.3   |   v5.7.3     | All | [v5.7.3](/platform/tutorial/runtime/ami-v573)   |
|1.7.6   |   v5.7.3    |  All | [v5.7.3](/platform/tutorial/runtime/ami-v573)  |
|1.7.5   |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |
|1.7     |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |
|1.6.4   |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |
|1.6     |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |  
|1.5.4   |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |
|1.5     |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |
|1.4     |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |
|1.3     |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |
|1.2     |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |    
|1.1     |  v5.6.1 and earlier |  All | [v5.6.1](/platform/tutorial/runtime/ami-v561) and earlier |