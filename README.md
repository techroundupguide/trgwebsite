# Tech Roundup Guide

One-way discreet messaging for friends.

## Receiving

If you know **where** to look, **when** to look, and have the **key** —
you can read the message. Miss any one of the three and there's nothing there.

## Sending

### One-time setup
*(repeat only if you want to change your admin phrase)*

1. Open `sealer.html` in a browser and enter your phrase
2. Copy the output over the `const _d="..."` line in `index.html`
3. Publish `index.html`

### Every message

1. On the live site, enter your admin phrase where the search box is
2. Write the message, pick a key for your friend, set the day, time and duration
3. Copy or download the updated `index.html` and publish it
4. Send your friend the key and the opening time

Nothing is saved until you publish. Composing a message and closing the
console loses it.

## Notes

- Keep `sealer.html` private and off the host. It's the only way to change your phrase.
- Lose the phrase and the console can't be opened. There's no recovery.
- Message keys should be three or more unrelated words. Short keys can be guessed offline.
- All times are converted to UTC, so a window opens at the same moment everywhere.