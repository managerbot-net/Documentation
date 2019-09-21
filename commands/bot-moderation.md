---
description: 'Parameters between `[ ]` are mandatory, and `< >` are optional.'
---

# Bot Moderation

## Bot Joined Message

{% hint style="success" %}
@Manager\#9545 **botJoinedMessage &lt;textChannel&gt;**
{% endhint %}

{% hint style="info" %}
Sends a welcome message
{% endhint %}

```text
@Manager#9545 botJoinedMessage
```

![](../.gitbook/assets/botjoinedmessage.PNG)

## Ping

{% hint style="success" %}
@Manager\#9545 **ping**
{% endhint %}

{% hint style="info" %}
Shows bot's Latency
{% endhint %}

![](../.gitbook/assets/ping.PNG)

## Shutdown

{% hint style="success" %}
@Manager\#9545 **shutdown**
{% endhint %}

{% hint style="info" %}
Shut downs the bot
{% endhint %}

![](../.gitbook/assets/shutdown.PNG)

## Maintenance

{% hint style="success" %}
@Manager\#9545 **maintenance \[scope\] \[status\]**
{% endhint %}

{% hint style="info" %}
Sets maintenance status
{% endhint %}

```text
@Manager#9545 maintenance global enabled
```

![](../.gitbook/assets/maintenance.PNG)

## Report

### Report Add

{% hint style="success" %}
@Manager\#9545 **report add \[description\]**
{% endhint %}

{% hint style="info" %}
Adds a report to a bug or an user
{% endhint %}

```text
@Manager#9545 report add Bot is not working.
```

![](../.gitbook/assets/reportadded.PNG)

![](../.gitbook/assets/reportaddedembed.PNG)

### Report Close

{% hint style="success" %}
@Manager\#9545 **report close \[reportId\] \[isValid\] &lt;response&gt;**
{% endhint %}

{% hint style="info" %}
Closes the report
{% endhint %}

```text
@Manager#9545 report close 1 true
```

![](../.gitbook/assets/reportclosed.PNG)

![](../.gitbook/assets/reportclosedembed.PNG)

### Report Claim

{% hint style="success" %}
@Manager\#9545 **report claim \[reportId\] &lt;amount&gt;**
{% endhint %}

{% hint style="info" %}
Gives an user a reward for a reporting
{% endhint %}

```text
@Manager#9545 report claim 1 15
```

![](../.gitbook/assets/reportclaimed.PNG)

![](../.gitbook/assets/reportclaimedembed.PNG)

