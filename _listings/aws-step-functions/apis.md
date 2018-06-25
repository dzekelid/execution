---
name: AWS Step Functions
x-slug: aws-step-functions
description: AWS Step Functions makes it easy to coordinate the components of distributed
  applications and microservices using visual workflows. Building applications from
  individual components that each perform a discrete function lets you scale and change
  applications quickly. Step Functions is a reliable way to coordinate components
  and step through the functions of your application. Step Functions provides a graphical
  console to arrange and visualize the components of your application as a series
  of steps. This makes it simple to build and run multi-step applications. Step Functions
  automatically triggers and tracks each step, and retries when there are errors,
  so your application executes in order and as expected. Step Functions logs the state
  of each step, so when things do go wrong, you can diagnose and debug problems quickly.
  You can change and add steps without even writing code, so you can easily evolve
  your application and innovate faster.AWS Step Functions manages the operations and
  underlying infrastructure for you to help ensure your application is available at
  any scale.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Execution
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Step Functions API Describe Execution
  x-api-slug: aws-step-functions-api
  description: Describes an execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=DescribeExecution
  tags: Execution
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/actiondescribeexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/actiondescribeexecution-get-openapi.md
- name: AWS Step Functions API Get Execution History
  x-api-slug: aws-step-functions-api
  description: Returns the history of the specified execution as a list of events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=GetExecutionHistory
  tags: Execution
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/actiongetexecutionhistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/actiongetexecutionhistory-get-openapi.md
- name: AWS Step Functions API Stop Execution
  x-api-slug: aws-step-functions-api
  description: Stops an execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=StopExecution
  tags: Execution
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/actionstopexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/actionstopexecution-get-openapi.md
- name: AWS Step Functions API
  x-api-slug: aws-step-functions-api
  description: AWS Step Functions makes it easy to coordinate the components of distributed
    applications and microservices using visual workflows. Building applications from
    individual components that each perform a discrete function lets you scale and
    change applications quickly. Step Functions is a reliable way to coordinate components
    and step through the functions of your application. Step Functions provides a
    graphical console to arrange and visualize the components of your application
    as a series of steps. This makes it simple to build and run multi-step applications.
    Step Functions automatically triggers and tracks each step, and retries when there
    are errors, so your application executes in order and as expected. Step Functions
    logs the state of each step, so when things do go wrong, you can diagnose and
    debug problems quickly. You can change and add steps without even writing code,
    so you can easily evolve your application and innovate faster.AWS Step Functions
    manages the operations and underlying infrastructure for you to help ensure your
    application is available at any scale.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: :///
  tags: Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/aws-step-functions/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/step-functions/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/step-functions/getting-started/
- type: x-how-it-works
  url: https://aws.amazon.com/step-functions/#howitworks
- type: x-pricing
  url: https://aws.amazon.com/step-functions/pricing/
- type: x-website
  url: https://aws.amazon.com/step-functions/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---