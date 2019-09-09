⚠️ *DEPRECATED* ⚠️ This connector is now built in to [opsdroid core](https://docs.opsdroid.dev/en/latest/connectors/webexteams/) and renamed it to webexteams. This repository only exists for backward compatibility and will be removed.

# opsdroid connector cisco spark

A connector for [opsdroid](https://github.com/opsdroid/opsdroid) to interact with [Cisco Spark](https://www.ciscospark.com/).

## Usage

**This connector requires that the opsdroid web server is internet facing.**

 - Visit https://developer.ciscospark.com and log in
 - Go to "My Apps"
 - Click the plus button to create a new app and select "Create a Bot"
 - Fill in the details and click "Add Bot"
 - Scroll down and find your access token

## Configuration

```yaml
connectors:
  - name: ciscospark
    # required
    webhook-url: http(s)://<host>:<port>  # Url for Spark to connect to your bot
    access-token: <your bot access token>  # Your access token
```
