swagger: "2.0"
x-collection-name: Azure Blockchain Workbench
x-complete: 1
info:
  title: Azure Blockchain Workbench REST API
  description: the-azure-blockchain-workbench-rest-api-is-a-workbench-extensibility-point-which-allows-developers-to-create-and-manage-blockchain-applications-manage-users-and-organizations-within-a-consortium-integrate-blockchain-applications-into-services-and-platforms-perform-transactions-on-a-blockchain-and-retrieve-transactional-and-contract-data-from-a-blockchain-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/contracts/{contractId}/actions:
    post:
      summary: Post Contracts Actions
      description: |-
        Executes an action for the specified smart contract instance and action ID. Users are only able to execute
                     the action given the current state of the specified smart contract instance and the user's associated application role
                     or smart contract instance role.
      operationId: ContractActionPost
      x-api-path-slug: apiv1contractscontractidactions-post
      parameters:
      - in: body
        name: actionInformation
        description: Parameters for a particular action
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contractId
        description: The id of the contract
      responses:
        200:
          description: OK
      tags:
      - Contracts
      - Actions