# action-repo

This repository is used to generate GitHub events for the TechStax assessment.

## Setup Webhook

1. Go to Settings → Webhooks in this repository.
2. Click "Add webhook".
3. Set the Payload URL to your webhook endpoint, e.g. `http://<HOST>/webhook`.
4. Choose content type `application/json`.
5. Subscribe to "Push" and "Pull requests" events.
6. Save.

Now, when you push commits or open/merge pull requests, events will be sent to your webhook receiver.
