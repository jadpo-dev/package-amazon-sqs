# Changelog

## 1.0.1

- no change to what it offers

Checked against Amazon SQS's documentation for receiving and deleting a
message, and marked as reviewed. Nothing an app writes changes.

## 1.0.0

- first release

Reads an SQS queue through the `receiving` capability: each message becomes
the app's event, and is deleted once that event is kept.
