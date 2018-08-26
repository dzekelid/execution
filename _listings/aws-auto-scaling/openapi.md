---
swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 1
info:
  title: AWS Auto Scaling API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ExecutePolicy:
    get:
      summary: Execute Policy
      description: Executes the specified policy.
      operationId: executePolicy
      x-api-path-slug: actionexecutepolicy-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name or Amazon Resource Name (ARN) of the Auto Scaling group
        type: string
      - in: query
        name: BreachThreshold
        description: The breach threshold for the alarm
        type: string
      - in: query
        name: HonorCooldown
        description: If this parameter is true, Auto Scaling waits for the cooldown
          period to complete before executing the policy
        type: string
      - in: query
        name: MetricValue
        description: The metric value to compare to BreachThreshold
        type: string
      - in: query
        name: PolicyName
        description: The name or ARN of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
---