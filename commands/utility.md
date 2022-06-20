# Utility

| Name        | Usage                            | Description                                                     |
| ----------- | -------------------------------- | --------------------------------------------------------------- |
| Avatar      | `/avatar <user> <type>`          | Guild/global avatar of a user                                   |
| Banner      | `h!banner <user>`                | Banner of a user, if any                                        |
| Lock        | `/lock`                          | Lock the channel which the command is used in                   |
| Membercount | `/membercount`                   | Current guild member count                                      |
| Purge       | `/purge <amount>`                | Deletes the specified amount of messages in the current channel |
| Quote       | `h!quote <message link>`         | Quotes a provided message                                       |
| Reminder    | `/reminder <duration> <message>` | Reminds a user of a message after a specified duration          |
| Say         | `/say <message>`                 | Sends a requested message through the bot                       |
| Serverinfo  | `/serverinfo`                    | General information about the current guild                     |
| Slowmode    | `/slowmode <length in seconds>`  | Sets the slowmode of the current channel                        |
| Whois       | `h!whois [user]`                 | General information about the requested user                    |
| Unlock      | `/unlock`                        | Unlocks the current channel                                     |

{% hint style="info" %}
With the `/reminder` command, you must append `s/m/h` to the duration, to provide seconds, minutes, or hours.
{% endhint %}

{% hint style="info" %}
To reset channel slowmode, use `/slowmode 0`.
{% endhint %}

{% hint style="info" %}
Hexagon is not responsible for messages sent with the `/say` command.
{% endhint %}
