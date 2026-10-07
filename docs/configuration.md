# Configuration

Configuration depends on the current implementation of Ezra Management X.

## Recommended Configuration

Keep secrets in environment variables or an untracked configuration file.

Typical categories include:

- Telegram bot token
- Developer IDs
- Owner IDs
- Database settings
- Logging destination
- Private-access settings
- Runtime configuration

## Example

Use placeholders rather than real credentials:

```env
BOT_TOKEN=your_bot_token_here
DEVELOPER_IDS=your_developer_id
OWNER_IDS=your_owner_id
```

Never commit real tokens or credentials to GitHub.
