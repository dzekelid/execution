---
name: Firebase
x-slug: firebase
description: Firebase is a mobile platform that gives developers the tools and infrastructure
  to build better apps and grow successful businesses.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
x-kinRank: "9"
x-alexaRank: "1"
tags: Execution
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/apis.md
specificationVersion: "0.14"
apis:
- name: Firebase Create Execution
  x-api-slug: firebase
  description: |-
    Creates an Execution.

    The returned Execution will have the id set.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - NOT_FOUND - if the containing History does not exist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////{projectId}/histories/{historyId}/executions
  tags: Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/projectidhistorieshistoryidexecutions-post-openapi.md
- name: Firebase Get Execution
  x-api-slug: firebase
  description: |-
    Gets an Execution.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - NOT_FOUND - if the Execution does not exist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////{projectId}/histories/{historyId}/executions/{executionId}
  tags: Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/projectidhistorieshistoryidexecutionsexecutionid-get-openapi.md
- name: Firebase Update Execution
  x-api-slug: firebase
  description: |-
    Updates an existing Execution with the supplied partial entity.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if the requested state transition is illegal - NOT_FOUND - if the containing History does not exist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////{projectId}/histories/{historyId}/executions/{executionId}
  tags: Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/projectidhistorieshistoryidexecutionsexecutionid-patch-openapi.md
- name: Firebase Get Execution Steps
  x-api-slug: firebase
  description: |-
    Lists Steps for a given Execution.

    The steps are sorted by creation_time in descending order. The step_id key will be used to order the steps with the same creation_time.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to read project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if an argument in the request happens to be invalid; e.g. if an attempt is made to list the children of a nonexistent Step - NOT_FOUND - if the containing Execution does not exist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////{projectId}/histories/{historyId}/executions/{executionId}/steps
  tags: Execution Step
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/projectidhistorieshistoryidexecutionsexecutionidsteps-get-openapi.md
- name: Firebase Create Execution Steps
  x-api-slug: firebase
  description: |-
    Creates a Step.

    The returned Step will have the id set.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to write to project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if the step is too large (more than 10Mib) - NOT_FOUND - if the containing Execution does not exist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////{projectId}/histories/{historyId}/executions/{executionId}/steps
  tags: Execution Step
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/projectidhistorieshistoryidexecutionsexecutionidsteps-post-openapi.md
- name: Firebase Get Execution Step
  x-api-slug: firebase
  description: |-
    Gets a Step.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to read project - INVALID_ARGUMENT - if the request is malformed - NOT_FOUND - if the Step does not exist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////{projectId}/histories/{historyId}/executions/{executionId}/steps/{stepId}
  tags: Execution Step
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/projectidhistorieshistoryidexecutionsexecutionidstepsstepid-get-openapi.md
- name: Firebase Update Execution Step
  x-api-slug: firebase
  description: |-
    Updates an existing Step with the supplied partial entity.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to write project - INVALID_ARGUMENT - if the request is malformed - FAILED_PRECONDITION - if the requested state transition is illegal (e.g try to upload a duplicate xml file), if the updated step is too large (more than 10Mib) - NOT_FOUND - if the containing Execution does not exist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////{projectId}/histories/{historyId}/executions/{executionId}/steps/{stepId}
  tags: Execution Step
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/projectidhistorieshistoryidexecutionsexecutionidstepsstepid-patch-openapi.md
- name: Firebase
  x-api-slug: firebase
  description: Firebase is a mobile platform that gives developers the tools and infrastructure
    to build better apps and grow successful businesses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Execution
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/execution/master/_listings/firebase/openapi.md
x-common:
- type: x-website
  url: https://Firebase.google.com
- type: x-blog
  url: https://firebase.googleblog.com/
- type: x-blog-rss
  url: http://firebase.googleblog.com/feeds/posts/default?alt=rss
- type: x-case-studies
  url: https://firebase.google.com/customers/
- type: x-change-log
  url: https://firebase.google.com/support/releases
- type: x-code
  url: https://firebase.google.com/docs/libraries/
- type: x-crunchbase
  url: https://crunchbase.com/organization/google
- type: x-documentation
  url: https://firebase.google.com/docs/
- type: x-faq
  url: https://firebase.google.com/support/faq/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/firebase-talk
- type: x-github
  url: https://github.com/firebase
- type: x-pricing
  url: https://firebase.google.com/pricing/
- type: x-pricing
  url: https://adwords.google.com/home/pricing/
- type: x-slack
  url: https://firebase.community/
- type: x-submit-bug
  url: https://firebase.google.com/support/contact/bugs-features
- type: x-support
  url: https://firebase.google.com/support/
- type: x-twitter
  url: https://twitter.com/Google
- type: x-twitter
  url: https://twitter.com/firebase
- type: x-website
  url: https://firebase.google.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---