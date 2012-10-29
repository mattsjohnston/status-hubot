# Status
A simple status manager script for [Hubot](https://github.com/github/hubot)
## Usage
### Going "Away"
When you set yourself as away, people mentioning your name will be notified with your away message.

	> hubot away out for a quick skinny-dip
Now, when someone mentions your name in the chatroom hubot will respond:

	Matt is away: out for a quick skinny-dip

#### Shortcut

For a shortcut, use hubot a <your_away_message>

### Returning

To return from being away, use hubot return. You can also use the shortcut, `hubot r`

### Setting your status

When you’re not going anyway, but you still want to let people know what you’re up to, use `hubot status <your_status>`.

	> hubot status jammin' out to some One Direction!
### Viewing statuses

To see others’ statuses either use `hubot status <user>` to see <users>'s status, or use `hubot statuses` to see everyone’s statuses.