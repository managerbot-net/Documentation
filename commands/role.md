---
description: 'Parameters between [ ] are mandatory, and < > are optional.'
---

# Role

### Role Info

{% hint style="success" %}
@Manager\#9545 **roleinfo \[role\]**
{% endhint %}

{% hint style="info" %}
Shows permissions for specified role
{% endhint %}

```text
@Manager#9545 roleinfo @Member
```

![](../.gitbook/assets/roleinfo.PNG)

### Role Difference

{% hint style="success" %}
@Manager\#9545 **roledifference \[role1\] \[role2\]**
{% endhint %}

{% hint style="info" %}
Shows two different roles permissions
{% endhint %}

```text
@Manager#9545 roledifference @Dedicated @Pro
```

![](../.gitbook/assets/roledifference.PNG)

## Role

### **Role**

{% hint style="success" %}
@Manager\#9545 **role \[role\]**  
@Manager\#9545 **role \[user\] \[role\]**
{% endhint %}

{% hint style="info" %}
Assigns the self-assignable role
{% endhint %}

```text
@Manager#9545 role @Gamer
```

![](../.gitbook/assets/role.PNG)

### Role Show

{% hint style="success" %}
@Manager\#9545 **role show**
{% endhint %}

{% hint style="info" %}
Shows all the self-assignable roles
{% endhint %}

```text
@Manager#9545 role show
```

![](../.gitbook/assets/roleshow.PNG)

### **Role Add**

{% hint style="success" %}
@Manager\#9545 **role add \[role\] \[emote\]**
{% endhint %}

{% hint style="info" %}
Adds a self assignable role
{% endhint %}

```text
@Manager#9545 role add @GTA
```

![](../.gitbook/assets/roleadd.PNG)

### **Role Remove**

{% hint style="success" %}
@Manager\#9545 **role remove \[role\]**
{% endhint %}

{% hint style="info" %}
Removes a self assignable role
{% endhint %}

```text
@Manager#9545 roler remove @GTA
```

![](../.gitbook/assets/roleremove.PNG)

## Moderation Rank

### **Moderation Rank Add**

{% hint style="success" %}
@Manager\#9545 **moderationRank add \[role\] \[position\]**
{% endhint %}

{% hint style="info" %}
Adds a role to moderation rank
{% endhint %}

```text
@Manager#9545 moderationRank add @Administrator 1
```

### **Moderation Rank Remove**

{% hint style="success" %}
@Manager\#9545 **moderationRank remove \[role\]**
{% endhint %}

{% hint style="info" %}
Removes a role from moderation rank
{% endhint %}

```text
@Manager#9545 moderationRank remove @Moderator
```

### Moderation Rank Show

{% hint style="success" %}
@Manager\#9545 **moderationRank show**
{% endhint %}

{% hint style="info" %}
Shows all moderation roles in a guild
{% endhint %}

```text
@Manager#9545 moderationrank show
```

### Moderation Add Name

{% hint style="success" %}
@Manager\#9545 **moderationRank addName \[position\] \[name\]**
{% endhint %}

{% hint style="info" %}
Adds a name of rank in moderation roles
{% endhint %}

```text
@Manager#9545 moderationRank addName 3 Staff-Category
```

### Moderation Rank Remove Name

{% hint style="success" %}
@Manager\#9545 **moderationRank remName \[position\]**
{% endhint %}

{% hint style="info" %}
Removes a role from moderation rank
{% endhint %}

```text
@Manager#9545 moderationRank remName 3
```

### Moderation Rank Promote

{% hint style="success" %}
@Manager\#9545 **moderationRank promote \[user\]**
{% endhint %}

{% hint style="info" %}
Promotes user to the next moderation role.
{% endhint %}

```text
@Manager#9545 moderationrank promote @SirSecurity#0959
```

### Moderation Rank Demote

{% hint style="success" %}
@Manager\#9545 **moderationRank demote \[user\]**
{% endhint %}

{% hint style="info" %}
Demotes user to the previous moderation role.
{% endhint %}

```text
@Manager#9545 modertionRank demote @SirSecurity#0959
```

## Default Roles

### Default Roles Add

{% hint style="success" %}
@Manager\#9545 **defaultRoles add \[name\]**
{% endhint %}

{% hint style="info" %}
Sets a role as a default role.
{% endhint %}

```text
@Manager#9545 defaultRoles add @GTA
```

### Default Roles Remove

{% hint style="success" %}
@Manager\#9545 **defaultRoles remove \[name\]**
{% endhint %}

{% hint style="info" %}
Removes a role from default roles.
{% endhint %}

```text
@Manager#9545 defaultRoles remove @GTA
```

### Default Roles Show

{% hint style="success" %}
@Manager\#9545 **defaultRoles show**
{% endhint %}

{% hint style="info" %}
Shows all moderation roles in a guild.
{% endhint %}

```text
@Manager#9545 defaultRoles show
```

## Leveling Roles

### Leveling Role Add

{% hint style="success" %}
@Manager\#9545 **levelingRole add \[role\] \[hours\]**
{% endhint %}

{% hint style="info" %}
Adds a leveling role.
{% endhint %}

```text
@Manager#9545 levelingRole add @Guest 5
```

### Leveling Roles Remove

{% hint style="success" %}
@Manager\#9545 **levelingRole remove \[role\]**
{% endhint %}

{% hint style="info" %}
Removes a role from leveling roles.
{% endhint %}

```text
@Manager#9545 levelingRole remove @Guest
```

### Leveling Role Insert

{% hint style="success" %}
@Manager\#9545 **levelingRole insert \[role\] \[position\] \[hours\]**
{% endhint %}

{% hint style="info" %}
Inserts a role to leveling roles
{% endhint %}

```text
@Manager#9545 insert @Pro 3 300
```

### Leveling Role Show

{% hint style="success" %}
@Manager\#9545 **levelingRole show**
{% endhint %}

{% hint style="info" %}
Shows leveling roles.
{% endhint %}

## Dj Role

### DJ Role Add

{% hint style="success" %}
@Manager\#9545 **djrole add \[user\]**
{% endhint %}

{% hint style="info" %}
Adds a dj role to an user.
{% endhint %}

```text
@Manager#9545 djrole add @SirSecurity#0959
```

### DJ Role Remove

{% hint style="success" %}
@Manager\#9545 **djrole remove \[user\]**
{% endhint %}

{% hint style="info" %}
Removes an user's dj role.
{% endhint %}

```text
@Manager#9545 djrole remove @SirSecurity#0959
```

### DJ Role Set

{% hint style="success" %}
@Manager\#9545 **djrole set \[role\]**
{% endhint %}

{% hint style="info" %}
Sets guild dj role.
{% endhint %}

```text
@Manager#9545 djrole set @Dj
```

### DJ Role Delete

{% hint style="success" %}
@Manager\#9545 **djrole delete \[role\]**
{% endhint %}

{% hint style="info" %}
Removes guild dj role.
{% endhint %}

```text
@Manager#9545 djrole delete @Dj
```

### DJ Role Show

{% hint style="success" %}
@Manager\#9545 **djrole show**
{% endhint %}

{% hint style="info" %}
Shows all guild dj roles.
{% endhint %}

```text
@Manager#9545 djrole show
```

