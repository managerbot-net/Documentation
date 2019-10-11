---
description: 'Parameters between [ ] are mandatory, and < > are optional.'
---

# User Moderation

## Accept Rules

{% hint style="success" %}
@Manager\#9545 **acceptRules &lt;user&gt;**
{% endhint %}

{% hint style="info" %}
User confirms server rules
{% endhint %}

```text
@Manager#9545 acceptRules
```

![](../.gitbook/assets/acceptrules.PNG)

## Kick

{% hint style="success" %}
@Manager\#9545 **kick \[user\]**
{% endhint %}

{% hint style="info" %}
Kicks user out of server
{% endhint %}

```text
@Manager#9545 kick @SirSecurity#0959
```

## Ban

{% hint style="success" %}
@Manager\#9545 **ban \[user\]**
{% endhint %}

{% hint style="info" %}
Bans user in a server.
{% endhint %}

```text
@Manager#9545 ban @SirSecurity#0959
```

## Set Nick

{% hint style="success" %}
@Manager\#9545 **setnick \[nick\]**  
@Manager\#9545 **setnick \[user\] \[nick\]**
{% endhint %}

{% hint style="info" %}
Set user's nickname
{% endhint %}

```text
@Manager#9545 setnick Quentin
```

![](../.gitbook/assets/setnick.PNG)

## Reset Profile

{% hint style="success" %}
@Manager\#9545 **reset \[user\]**
{% endhint %}

{% hint style="info" %}
Resets user profile
{% endhint %}

```text
@Manager#9545 reset @SirSecurity#0959
```

## Playtime

### Playtime Add

{% hint style="success" %}
@Manager\#9545 **playtime add \[user\] \[hours\]**
{% endhint %}

{% hint style="info" %}
Add user playtime
{% endhint %}

```text
@Manager#9545 playtime add @SirSecurity#0959 15
```

![](../.gitbook/assets/playtimeadd.PNG)

### Playtime Remove

{% hint style="success" %}
@Manager\#9545 **playtime remove \[user\] \[hours\]**
{% endhint %}

{% hint style="info" %}
Remove user playtime
{% endhint %}

```text
@Manager#9545 playtime remove @SirSecurity#0959 15
```

![](../.gitbook/assets/playtimeremove.PNG)

## Warning

### Warning

{% hint style="success" %}
@Manager\#9545 **warning \[user\] &lt;reason&gt;**
{% endhint %}

{% hint style="info" %}
Give user a warning
{% endhint %}

```text
@Manager#9545 warning @SirSecurity#0959
```

![](../.gitbook/assets/warning.PNG)

### Warning Show

{% hint style="success" %}
@Manager\#9545 **warning show &lt;user&gt;**
{% endhint %}

{% hint style="info" %}
Show user's warnings
{% endhint %}

```text
@Manager#9545 warning show
```

![](../.gitbook/assets/warningshow.PNG)

### Warning Clear

{% hint style="success" %}
@Manager\#9545 **clear \[user\]**
{% endhint %}

{% hint style="info" %}
Clear all user warnings
{% endhint %}

```text
@Manager#9545 clear @SirSecurity#0959
```

![](../.gitbook/assets/warningclear.PNG)

## Punish

### Punish Add

{% hint style="success" %}
@Manager\#9545 **punish add \[user\] \[minutes\] &lt;reason&gt;**
{% endhint %}

{% hint style="info" %}
Prevents user from sending messages and speaking
{% endhint %}

```text
@Manager#9545 punish add @SirSecurity#0959 10
```

### Punish Remove

{% hint style="success" %}
@Manager\#9545 **punish remove \[user\] &lt;reason&gt;**
{% endhint %}

{% hint style="info" %}
Unpunishes the user
{% endhint %}

```text
@Manager#9545 punish remove @SirSecurity#0959
```

## Mute

### Mute Voice

{% hint style="success" %}
@Manager\#9545 **mute voice \[user\] \[minutes\]**
{% endhint %}

{% hint style="info" %}
Mutes user's microphone
{% endhint %}

```text
@Manager#9545 mute voice @SirSecurity#0959
```

![](../.gitbook/assets/mutevoice.PNG)

### Mute Chat

{% hint style="success" %}
@Manager\#9545 **mute chat \[user\] \[minutes\]**
{% endhint %}

{% hint style="info" %}
Mutes user's chat
{% endhint %}

```text
@Manager#9545 mute chat @SirSecurity#0959 5
```

![](../.gitbook/assets/mutechat.PNG)

## UnMute

### UnMute Voice

{% hint style="success" %}
@Manager\#9545 **unmute voice \[user\]**
{% endhint %}

{% hint style="info" %}
UnMutes user's microphone
{% endhint %}

```text
@Manager#9545 unmute voice @SirSecurity#0959
```

![](../.gitbook/assets/unmutevoice.PNG)

### UnMute Chat

{% hint style="success" %}
@Manager\#9545 **unmute chat \[user\]**
{% endhint %}

{% hint style="info" %}
UnMutes user's chat
{% endhint %}

```text
@Manager#9545 unmute chat @SirSecurity#0959
```

![](../.gitbook/assets/unmutechat.PNG)

## AFK

### AFK Warn

{% hint style="success" %}
@Manager\#9545 **afk warn \[user\]**
{% endhint %}

{% hint style="info" %}
Gives user an afk warning
{% endhint %}

```text
@Manager#9545 afk warn @SirSecurity#0959
```

![](../.gitbook/assets/afkwarn.PNG)

### AFK No

{% hint style="success" %}
@Manager\#9545 **afk no**
{% endhint %}

{% hint style="info" %}
Gives user an afk warning
{% endhint %}

```text
@Manager#9545 afk no
```

### AFK Remove

{% hint style="success" %}
@Manager\#9545 **afk remove \[user\]**
{% endhint %}

{% hint style="info" %}
Removes user all afk warnings
{% endhint %}

```text
@Manager#9545 afk remove @SirSecurity#0959
```

### AFK Show

{% hint style="success" %}
@Manager\#9545 **afk show &lt;user&gt;**
{% endhint %}

{% hint style="info" %}
Show user's all afk warnings
{% endhint %}

```text
@Manager#9545 afk show
```

![](../.gitbook/assets/afkshow.PNG)

### AFK Settings

{% hint style="success" %}
@Manager\#9545 **afk settings**
{% endhint %}

{% hint style="info" %}
Show current afk policies
{% endhint %}

```text
@Manager#9545 afk settings
```

![](../.gitbook/assets/afksettings.PNG)

### AFK Edit

