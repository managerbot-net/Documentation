# Bot Moderation

## Bot Joined Message

{% hint style="success" %}
@Manager\#9545 **botJoinedMessage &lt;textChannel&gt;**
{% endhint %}

{% hint style="info" %}
 Sends a welcome message
{% endhint %}

```text
@Manager#9545 botJoinedMessage  #channel
```

### Ping

{% hint style="success" %}
@Manager\#9545 **ping**
{% endhint %}

{% hint style="info" %}
Shows bot's Latency
{% endhint %}

### Shutdown

{% hint style="success" %}
@Manager\#9545 **shutdown**
{% endhint %}

{% hint style="info" %}
Shut downs the bot
{% endhint %}

### Maintenance

{% hint style="success" %}
@Manager\#9545 **maintenance &lt;scope&gt; &lt;status&gt;**
{% endhint %}

{% hint style="info" %}
Sets maintenance status
{% endhint %}

```text
@Manager#9545 maintenance global enabled
```

### Report Add

{% hint style="success" %}
@Manager\#9545 **report add &lt;description&gt;**
{% endhint %}

{% hint style="info" %}
Adds a report to a bug or an user
{% endhint %}

```text
@Manager#9545 report add Bot is not working.
```

### Report Close

{% hint style="success" %}
@Manager\#9545 **report close &lt;reportId&gt; &lt;isValid&gt; &lt;response&gt;**
{% endhint %}

{% hint style="info" %}
Closes the report
{% endhint %}

```text
@Manager#9545 report close 1 true Bug found
```

### Report Claim

{% hint style="success" %}
@Manager\#9545 **report claim &lt;reportId&gt; &lt;amount&gt;**
{% endhint %}

{% hint style="info" %}
Gives an user a reward for a reporting
{% endhint %}

```text
@Manager#9545 report claim 1 15
```