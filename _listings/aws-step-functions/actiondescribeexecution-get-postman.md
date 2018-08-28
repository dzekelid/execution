{
  "info": {
    "name": "AWS Step Functions API Describe Execution",
    "_postman_id": "7a486560-83f9-493f-816c-c69e6cc0eb10",
    "description": "Describes an execution.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activity",
      "item": [
        {
          "id": "2bb35e4d-93a4-491f-a163-2361bc2ca506",
          "name": "createActivity",
          "request": {
            "url": "http://example.com/api/?Action=CreateActivity?name=name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an activity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36026949-81ff-4506-ab8b-0d7808b66e91"
            }
          ]
        },
        {
          "id": "b1cbe1a2-ae22-4858-a3dd-09f38bcd52d3",
          "name": "deleteActivity",
          "request": {
            "url": "http://example.com/api/?Action=DeleteActivity?activityArn=activityArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an activity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80acd3d1-42c3-4698-a94c-63a8e2cb2cd3"
            }
          ]
        },
        {
          "id": "5fbc11f1-b877-4f4a-a6a9-eb5f318726aa",
          "name": "describeActivity",
          "request": {
            "url": "http://example.com/api/?Action=DescribeActivity?activityArn=activityArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes an activity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f2189e7-5c1a-469d-b04a-1d22d858d850"
            }
          ]
        }
      ]
    },
    {
      "name": "State Machine",
      "item": [
        {
          "id": "5af8a068-44d4-4f79-a190-2f4dffc05f1d",
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
              "id": "557e17ea-7895-4694-9931-9edb22348a90"
            }
          ]
        },
        {
          "id": "221d12ea-40b4-4022-b8f8-eb9029c78d82",
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
              "id": "2083a6f9-2c7b-4e13-805f-b303ed3634b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Execution",
      "item": [
        {
          "id": "f71e8d8f-8746-4c0e-a5aa-f768cb6a04a5",
          "name": "describeExecution",
          "request": {
            "url": "http://example.com/api/?Action=DescribeExecution?executionArn=executionArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes an execution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3caac11-a357-4311-83d0-94d2719d1f8f"
            }
          ]
        }
      ]
    }
  ]
}