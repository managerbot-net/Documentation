---
description: 'Parameters between [ ] are mandatory, and < > are optional.'
---

# Economy

## Buy

### Buy CustomRole

{% hint style="success" %}
@Manager\#9545 **buy customRole**
{% endhint %}

{% hint style="info" %}
Sells you a custom role which you can later edit.
{% endhint %}

```text
@Manager#9545 buy customRole
```

### Buy GuildRole

{% hint style="success" %}
@Manager\#9545 **buy guildRole**
{% endhint %}

{% hint style="info" %}
Sells you a guildRole which was set by guild Administrator.
{% endhint %}

```text
@Manager#9545 buy guildRole
```

## Money

### Money Add

{% hint style="success" %}
@Manager\#9545 **money add \[user\] \[amount\]**
{% endhint %}

{% hint style="info" %}
Adds player some amount of money.
{% endhint %}

```text
@Manager#9545 money add @SirSecurity#0959 10
```

![](../.gitbook/assets/moneyadd.PNG)

### Money Give

{% hint style="success" %}
@Manager\#9545 **money give \[user\] \[amount\]**
{% endhint %}

{% hint style="info" %}
Gives user money.
{% endhint %}

```text
@Manager#9545 money give @SirSecurity#0959 10
```

### Money Remove

{% hint style="success" %}
@Manager\#9545 **money remove \[user\] \[amount\]**
{% endhint %}

{% hint style="info" %}
Removes player's amount of money.
{% endhint %}

```text
@Manager#9545 remove @SirSecurity#0959 10
```

![](../.gitbook/assets/moneyremove.PNG)

### Money Show

{% hint style="success" %}
@Manager\#9545 **money show &lt;user&gt;**
{% endhint %}

{% hint style="info" %}
Shows how much money user has
{% endhint %}

```text
@Manager#9545 money show
```

![](../.gitbook/assets/moneyshow.PNG)

### Money Top

{% hint style="success" %}
@Manager\#9545 **money top &lt;count&gt;**
{% endhint %}

{% hint style="info" %}
Shows the richest users on the server.
{% endhint %}

```text
@Manager#9545 money top
```

![](../.gitbook/assets/moneytop.PNG)

## Shop

### Shop Add

#### Shop Add CustomRole

{% hint style="success" %}
@Manager\#9545 **shop add customRole \[price\]**
{% endhint %}

{% hint style="info" %}
Enables custom role selling.
{% endhint %}

```text
@Manager#9545 shop add customRole 150
```

#### Shop Add GuildRole

{% hint style="success" %}
@Manager\#9545 **shop add guildRole \[role\] \[price\] \[description\]**
{% endhint %}

{% hint style="info" %}
Adds new guild role to shop
{% endhint %}

```text
@Manager#9545 shop add guildRole @PlayerRole 150 Player role
```

### Shop Remove

#### Shop Remove CustomRole

{% hint style="success" %}
@Manager\#9545 **shop remove customRole**
{% endhint %}

{% hint style="info" %}
Disables custom role creating.
{% endhint %}

```text
@Manager#9545 shop remove customRole @PlayerRole
```

#### Shop Remove GuildRole

{% hint style="success" %}
@Manager\#9545 **shop remove guildRole \[role\]**
{% endhint %}

{% hint style="info" %}
Removes selected guild role from shop
{% endhint %}

```text
@Manager#9545 shop remove guildRole @PlayerRole
```

## Shop Offer

{% hint style="success" %}
@Manager\#9545 **shop offer**
{% endhint %}

{% hint style="info" %}
Shows current shop offer.
{% endhint %}

```text
@Manager#9545 shop offer
```

## Shop Detail

{% hint style="success" %}
@Manager\#9545 **shop detail \[itemId\]**
{% endhint %}

{% hint style="info" %}
Shows detailed information of shop item.
{% endhint %}

```text
@Manager#9545 shop detail 123
```