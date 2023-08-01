# Thread Channel Commands

After setup bot, BOXy will make thread after every message send in one channel, this feature is usually used for channels such as suggestions and Q\&A

{% hint style="warning" %}
* This feature can only be set on one channel in every guild
* The bot has a 10-second slowmode to create each thread channel for one person
{% endhint %}

{% hint style="info" %}
It is suggested to set 10 seconds slow mode in the selected channel to prevent spam and avoid content problems
{% endhint %}

### Example of how it works

![config thread system](../.gitbook/assets/2022-03-06-18-13-27.gif)

### Commands setup

Add thread channel

```
/config server option:Set Thread System channel channel:<mention channel>
```

Remove thread channel

```
/config server option:Remove Thread System channel channel:<mention channel>
```
