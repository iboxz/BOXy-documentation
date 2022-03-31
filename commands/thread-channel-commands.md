# Thread Channel Commands

After setup bot, BOXy will make thread after every message send in one channel, this feature is usually used for channels such as suggestions and Q\&A

{% hint style="warning" %}
This feature can only be set on one channel in every guild
{% endhint %}

{% hint style="warning" %}
The bot has a 30-second slowmode to create each thread channel
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
