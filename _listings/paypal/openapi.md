---
swagger: "2.0"
x-collection-name: PayPal
x-complete: 1
info:
  title: PayPal (Sandbox)
  description: bring-payments-to-apps-mobile-and-social-with-adaptive-payments-bsandbox-api-b
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AdaptivePayments/ExecutePayment:
    post:
      summary: Execute Payment
      description: The ExecutePayment API operation lets you execute a payment set
        up with the Pay API operation with the actionType CREATE. To pay receivers
        identified in the Pay call, set the pay key from the PayResponse message in
        the ExecutePaymentRequest message.
      operationId: AdaptivePayments.ExecutePayment.post
      x-api-path-slug: adaptivepaymentsexecutepayment-post
      responses:
        200:
          description: OK
      tags:
      - Payments
---