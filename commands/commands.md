# Commands

{% hint style="info" %}
**Good to know:** BOXy commands are all in slash command format.
{% endhint %}

### Utility**:**

<details>

<summary>Instagram downloader</summary>

**Download the post or story from Instagram by sending a link**

`/instagram downloader link:<copy link from instagram>`

* If the file is larger than the 25MB(limit of Discord), it will send a download link

</details>

### **Information commands:**

<details>

<summary>Avatar</summary>

**You can view the avatar and banner of either yourself or another user.**

To view your own avatar

```
/avatar 
```

To view another user's avatar

```
/avatar target:<mention user>
```

</details>

<details>

<summary><strong>User</strong></summary>

**You can view information about yourself or another user. This includes when the account was created, when the account joined the current server, what roles the account has in the current server, and more!**

To view your own user account information

```
/user
```

To view another user's account information

```
/user target:<mention user> 
```

</details>

<details>

<summary><strong>Server</strong></summary>

**You can view information about the current server. This includes the server name, who owns the server, when the server was created, and more!**

```
/server
```

</details>

<details>

<summary>stats</summary>

**You can request some statistics about BOXy. This includes how many servers BOXy is in, how much memory BOXy is using, top server list, and more!**

```
/stats
```

</details>

<details>

<summary>Invite</summary>

**You can view the bot invite link with this code**

```
/invite
```

</details>

### Moderator **commands:**

<details>

<summary>Ban &#x26; Unban</summary>

**You can ban a member from your server. They will not be able to rejoin until they are unbanned. This will log a moderation action. You can also add an optional reason**

Ban a member

```
/ban option:Ban target:<mention user>
```

```
/ban option:Ban target:<mention user> reason:<reason>
```

**You can unban a member. This will log a moderation action. You can also add an optional reason.**

Unban a member

```
/ban option:Unban target:<userID>
```

```
/ban option:Unban target:<userID> reason:<reason>
```

</details>

<details>

<summary>Kick</summary>

**You can kick a member from your server. They will be able to rejoin the server with an invite link. This will log a moderation action. You can also add an optional reason.**

Ban a member

```
/kick target:<mention user>
```

```
/kick target:<mention user> reason:<reason>
```



</details>

<details>

<summary>Timeout (add / remove)</summary>

**you can timeout a member so they cannot type in your channels. This will log a moderation action. You can also add an optional reason and time limit.**

Timeout a member

```
/timeout option:Add target:<mention user> 
```

```
/timeout option:Add target:<mention user> duration:<custom time> reason:<reason>
```

_❕If you don't enter a specific_ duration\_, it will be set on two hours automatically.\_

Remove timeout

```
/timeout option:Remove target:<mention user> 
```

```
/timeout option:Add target:<mention user> reason:<reason>
```

</details>

### Configuration commands

<details>

<summary>Config moderator log</summary>

**you can list all moderation logs for a user. This will include all moderation actions given to them by a human and bot moderator.**

Add moderator log

```
/config server option:Set Moderator log channel channel:<mention channel>
```

Remove moderator log

```
/config server option:Remove Moderator log channel channel:<mention channel>
```

#### change bot prefix:

```
/config bot prefix:<What do you want to change the prefix to?>
```

</details>

### Thread Channel Commands

{% content-ref url="thread-channel-commands.md" %}
[thread-channel-commands.md](thread-channel-commands.md)
{% endcontent-ref %}

### Configuration Self Assignable Roles

{% content-ref url="self-assignable-roles.md" %}
[self-assignable-roles.md](self-assignable-roles.md)
{% endcontent-ref %}
