# Pub/Sub: Qwik Start - Console || **GSP096**

**Command:**

```bash
gcloud pubsub topics create MyTopic && \
gcloud pubsub subscriptions create MySub --topic=MyTopic && \
gcloud pubsub topics publish MyTopic --message="Hello World" && \
gcloud pubsub subscriptions pull --auto-ack MySub
```
