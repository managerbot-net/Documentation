---
description: 'Parameters between `[ ]` are mandatory, and `< >` are optional.'
---

# Guild Moderation

## Set Language

{% hint style="success" %}
@Manager\#9545 **setlang \[languageShortcut\]**
{% endhint %}

{% hint style="info" %}
Sets bot communicating language in the guild
{% endhint %}

```text
@Manager#9545 setlang ENG
```

![](../.gitbook/assets/setlang.PNG)

## Prefix

{% hint style="success" %}
@Manager\#9545 **prefix \[prefix\]**
{% endhint %}

{% hint style="info" %}
Sets bot prefix in the guild
{% endhint %}

![](../.gitbook/assets/prefix.PNG)

```text
@Manager#9545 prefix /
```

## Purge

{% hint style="success" %}
@Manager\#9545 **purge \[messageCount\]**
{% endhint %}

{% hint style="info" %}
Purges specified amount of messages in the text channel
{% endhint %}

```text
@Manager#9545 purge 10
```

![](../.gitbook/assets/purge.PNG)

## Boost Playtime

{% hint style="success" %}
@Manager\#9545 **boost playtime \[value\]**
{% endhint %}

{% hint style="info" %}
Sets playtime booster
{% endhint %}

```text
@Manager#9545 boost playtime 1.5
```

![](../.gitbook/assets/boostplaytime%20%281%29.PNG)

## Audit

### Audit Create

{% hint style="success" %}
@Manager\#9545 **audit create \[channel\]**
{% endhint %}

{% hint style="info" %}
Create new audit log configuration
{% endhint %}

```text
@Manager#9545 audit create #audit-channel
```

![](../.gitbook/assets/auditcreate.PNG)

### Audit Remove

{% hint style="success" %}
@Manager\#9545 **audit remove**
{% endhint %}

{% hint style="info" %}
Removes audit configuration
{% endhint %}

```text
@Manager#9545 audit remove
```

![](../.gitbook/assets/auditremove.PNG)

### Audit Channel

{% hint style="success" %}
@Manager\#9545 **audit channel \[channel\]**
{% endhint %}

{% hint style="info" %}
Changes the audit channel.
{% endhint %}

```text
@Manager#9545 audit channel #audit-channel
```

![](../.gitbook/assets/auditchannel.PNG)

### Audit Modify

{% hint style="success" %}
@Manager\#9545 **audit modify \[logType\]**
{% endhint %}

{% hint style="info" %}
Modify log type value
{% endhint %}

```text
@Manager#9545 audit modify UserJoinedChannel
```

![](../.gitbook/assets/auditmodify.PNG)

### Audit Value

{% hint style="success" %}
@Manager\#9545 **audit value \[logType\]**
{% endhint %}

{% hint style="info" %}
Gives you the true/false value of the state
{% endhint %}

```text
@Manager#9545 audit value UserJoinedGuild
```

![](../.gitbook/assets/auditvalue.PNG)

### Audit Values

{% hint style="success" %}
@Manager\#9545 **audit values**
{% endhint %}

{% hint style="info" %}
Gives you all the values of Log states
{% endhint %}

```text
@Manager#9545 audit values
```

![](../.gitbook/assets/auditvalues.PNG)

## Communication Channel

### Communication Channel Add

{% hint style="success" %}
@Manager\#9545 **communicationChannel add \[channel\]**
{% endhint %}

{% hint style="info" %}
Sets channel as bot communication channel
{% endhint %}

```text
@Manager#9545 communicationChannel add #channel
```

![](../.gitbook/assets/communicationchanneladd.PNG)

### Communication Channel Remove

{% hint style="success" %}
@Manager\#9545 **communicationChannel remove \[channel\]**
{% endhint %}

{% hint style="info" %}
Removes channel from bot communication channels
{% endhint %}

```text
@Manager#9545 communicationChannel remove #channel
```

![](../.gitbook/assets/communicationchannelremove.PNG)

### Communication Channel Show

{% hint style="success" %}
@Manager\#9545 **communicationChannel show**
{% endhint %}

{% hint style="info" %}
Shows bot communication channels
{% endhint %}

```text
@Manager#9545 communicationChannel show
```

![](../.gitbook/assets/communicationchannelshow.PNG)

### Communication Channel Main

{% hint style="success" %}
@Manager\#9545 **communicationChannel main \[channel\]**
{% endhint %}

{% hint style="info" %}
Sets channel as a main bot communication channel
{% endhint %}

```text
@Manager#9545 communicationChannel main #channel
```

![](../.gitbook/assets/communicationchannelmain.PNG)

## Default Messages

### Default Messages Add

#### Default Messages Add Welcome

{% hint style="success" %}
@Manager\#9545 **defaultMessages add welcome \[message\]**
{% endhint %}

{% hint style="info" %}
Adds a welcome message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages add welcome Hello!
```

![](../.gitbook/assets/defaultmessagesaddwelcome.PNG)

#### Default Messages Add Leave

{% hint style="success" %}
@Manager\#9545 **defaultMessages add leave \[message\]**
{% endhint %}

{% hint style="info" %}
Adds a leave message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages add leave "Bye!"
```

![](../.gitbook/assets/defaultmessagesaddleave.PNG)

### Default Messages Remove

#### Default Messages Remove Welcome

{% hint style="success" %}
@Manager\#9545 **defaultMessages remove welcome**
{% endhint %}

{% hint style="info" %}
Removes a welcome message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages remove welcome
```

![](../.gitbook/assets/defaultmessagesremovewelcome.PNG)

#### Default Messages Remove Leave

{% hint style="success" %}
@Manager\#9545 **defaultMessages remove leave**
{% endhint %}

{% hint style="info" %}
Removes a leave message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages remove leave
```

![](../.gitbook/assets/defaultmessagesremoveleave.PNG)

### Default Messages Show

{% hint style="success" %}
@Manager\#9545 **defaultMessages show**
{% endhint %}

{% hint style="info" %}
Shows welcome and leave messages
{% endhint %}

```text
@Manager#9545 defaultMessages show
```

![](../.gitbook/assets/defaultmessagesshow.PNG)

## Game Sales Notifications

### Game Sales Notifications Channel

#### Game Sales Notifications Channel Add

{% hint style="success" %}
@Manager\#9545 **gamesalesnotifications channel add \[channel\]**
{% endhint %}

{% hint style="info" %}
Adds a channel to post game sales notifications
{% endhint %}

```text
@Manager#9545 gamesalesnotifications channel add #channel
```

![](../.gitbook/assets/gamesalesnotificationschanneladd.PNG)

#### Game Sales Notifications Channel Remove

{% hint style="success" %}
@Manager\#9545 **gamesalesnotifications channel remove**
{% endhint %}

{% hint style="info" %}
Removes the channel from game sales notifications channel list
{% endhint %}

```text
@Manager#9545 gamesalesnotifications channel remove
```

![](../.gitbook/assets/gamesalesnotificationschannelremove.PNG)

### Game Sales Notifications Role

#### Game Sales Notifications Role Add

{% hint style="success" %}
@Manager\#9545 **gamesalesnotifications role add \[role\]**
{% endhint %}

{% hint style="info" %}
Adds a role to sending notifications
{% endhint %}

```text
@Manager#9545 gamesalesnotifications role add @Role
```

![](../.gitbook/assets/gamesalesnotificationsroleadd.PNG)

#### Game Sales Notifications Role Remove

{% hint style="success" %}
@Manager\#9545 **gamesalesnotifications role remove**
{% endhint %}

{% hint style="info" %}
Removes the role from game sales notification roles.
{% endhint %}

```text
@Manager#9545 gamesalesnotifications role remove
```

![](../.gitbook/assets/gamesalesnotificationsroleremove.PNG)

### Game Sales Notifications Show

{% hint style="success" %}
@Manager\#9545 **gamesalesnotifications show**
{% endhint %}

{% hint style="info" %}
Shows game sales notifications settings
{% endhint %}

```text
@Manager#9545 gamesalesnotifications show
```

![](../.gitbook/assets/gamesalesnotificationsshow.PNG)

