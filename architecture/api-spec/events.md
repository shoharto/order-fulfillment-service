Publishing messages from order service to fulfillment service.
```sh
topicName = 'order_service';
 ```
Receiving messages using Pull from order service.

```sh
subscriptionName = 'delivery_order';
```
Publishing messages from fulfillment service to notification service.

```sh
topicName = 'notify_delivery';
```
Publishing messages from fulfillment service to refund service.

```sh
topicName = 'refund_order';
```
