{
  "info": {
    "name": "AWS Step Functions API List Executions",
    "_postman_id": "59fb746d-5593-45f6-b4b0-b7db7c0e48c8",
    "description": "Lists the executions of a state machine that meet the filtering criteria.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "State Machine",
      "item": [
        {
          "id": "0c7b4485-ae15-49eb-bca5-662e3ecb8b14",
          "name": "createStateMachine",
          "request": {
            "url": "http://example.com/api/?Action=CreateStateMachine?definition=definition&name=name&roleArn=roleArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a state machine."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "004c4b38-1328-4aee-a661-576ca32e06f4"
            }
          ]
        },
        {
          "id": "19dfd108-63cd-4567-af34-56ca382e1769",
          "name": "deleteStateMachine",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStateMachine?stateMachineArn=stateMachineArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a state machine."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "adfb8759-2120-4e8b-9bd3-2f8ec8e27cc2"
            }
          ]
        },
        {
          "id": "5a38b4ad-adae-4c6e-86aa-1e0c66c192b0",
          "name": "describeStateMachine",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStateMachine?stateMachineArn=stateMachineArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a state machine."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e6f8a37-5db3-4e88-b53b-cb321cf710d4"
            }
          ]
        },
        {
          "id": "0c32ba79-1042-4662-b02c-1b9ff63ea402",
          "name": "listExecutions",
          "request": {
            "url": "http://example.com/api/?Action=ListExecutions?maxResults=maxResults&nextToken=nextToken&stateMachineArn=stateMachineArn&statusFilter=statusFilter",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the executions of a state machine that meet the filtering criteria."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56e565bf-257d-4f23-9a31-67b6166b551e"
            }
          ]
        }
      ]
    }
  ]
}