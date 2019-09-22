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
@Manager#9545 purge 1000
```

![](../.gitbook/assets/prefix%20%281%29.PNG)

## Boost Playtime

{% hint style="success" %}
@Manager\#9545 **playtime \[value\]**
{% endhint %}

{% hint style="info" %}
Sets playtime booster
{% endhint %}

```text
@Manager#9545 boost playtime 1.5
```

## Audit

### Audit Set

{% hint style="success" %}
@Manager\#9545 **audit set \[channel\]**
{% endhint %}

{% hint style="info" %}
Sets channel for an audit log
{% endhint %}

```text
@Manager#9545 audit set #channel
```

### Audit Remove

{% hint style="success" %}
@Manager\#9545 **audit remove \[channel\]**
{% endhint %}

{% hint style="info" %}
Changes channel of the audit log
{% endhint %}

```text
@Manager#9545 audit remove #channel
```

### Audit Move

{% hint style="success" %}
@Manager\#9545 **audit move \[channel\]**
{% endhint %}

{% hint style="info" %}
Changes the audit channel.
{% endhint %}

```text
@Manager#9545 audit move LogType
```

### Audit Modify

{% hint style="success" %}
@Manager\#9545 **audit modify \[logType\]**
{% endhint %}

{% hint style="info" %}
Modify log type value
{% endhint %}

```text
@Manager#9545 audit modify Administrator
```

### Audit Value

{% hint style="success" %}
@Manager\#9545 **audit value \[logType\]**
{% endhint %}

{% hint style="info" %}
Gives you the true/false value of the state
{% endhint %}

```text
@Manager#9545 audit value Administrator
```

### Audit Values

{% hint style="success" %}
@Manager\#9545 **audit values**
{% endhint %}

{% hint style="info" %}
Gives you all the values of Log states
{% endhint %}

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

### Communication Channel Show

{% hint style="success" %}
@Manager\#9545 **communicationChannel show**
{% endhint %}

{% hint style="info" %}
Shows bot communication channels
{% endhint %}

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

## Default Messages

### Default Messages Add Welcome

{% hint style="success" %}
@Manager\#9545 **defaultMessages add welcome \[message\]**
{% endhint %}

{% hint style="info" %}
Adds a welcome message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages add welcome Hello!
```

### Default Messages Add Leave

{% hint style="success" %}
@Manager\#9545 **defaultMessages add leave \[message\]**
{% endhint %}

{% hint style="info" %}
Adds a leave message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages add leave "Bye!"
```

### Default Messages Remove Welcome

{% hint style="success" %}
@Manager\#9545 **defaultMessages remove welcome**
{% endhint %}

{% hint style="info" %}
Removes a welcome message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages remove welcome
```

### Default Messages Remove Leave

{% hint style="success" %}
@Manager\#9545 **defaultMessages remove leave**
{% endhint %}

{% hint style="info" %}
Removes a leave message for newly joined users
{% endhint %}

```text
@Manager#9545 defaultMessages remove leave
```

## Game Sales Notifications

### Game Sales Notifications Channel

#### Game Sales Notifications Channel Add

{% hint style="success" %}
@Manager\#9545 **gamesales channel add \[channel\]**
{% endhint %}

{% hint style="info" %}
Adds a channel to post game sales notifications
{% endhint %}

```text
@Manager#9545 gamesales channel add #channel
```

#### Game Sales Notifications Channel Remove

{% hint style="success" %}
@Manager\#9545 **gamesales channel remove**
{% endhint %}

{% hint style="info" %}
Removes the channel from game sales notifications channel list
{% endhint %}

### Game Sales Notifications Role

#### Game Sales Notifications Role Add

{% hint style="success" %}
@Manager\#9545 **gamesales role add \[role\]**
{% endhint %}

{% hint style="info" %}
Adds a role to sending notifications
{% endhint %}

```text
@Manager#9545 gamesales role add @Role
```

#### Game Sales Notifications Role Remove

{% hint style="success" %}
@Manager\#9545 **gamesales role remove**
{% endhint %}

{% hint style="info" %}
Removes the role from game sales notification roles.
{% endhint %}

