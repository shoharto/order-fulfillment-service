Publishing messages from order service to fulfillment service.
```sh
topicName = 'orders';
 ```
Receiving messages using Pull from order service.

```sh
subscriptionName = 'orders';
```
Publishing messages from fulfillment service to notification service.

```sh
topicName = 'notifications';

Payload
{
    
}

```
Publishing messages from fulfillment service to refund service.

```sh
topicName = 'refunds';
```
