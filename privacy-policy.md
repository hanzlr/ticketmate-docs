# Privacy Policy

**Effective Date:** June 22, 2026

This Privacy Policy explains how TicketMate ("the Bot") collects, uses, and stores your data. By using the Bot, you agree to this policy.

---

## 1. What Data We Collect

When TicketMate is used in a Discord server, the following data may be collected and stored:

| Data | Purpose |
|---|---|
| Discord server (guild) ID | Identify which server the Bot is configured for |
| Discord channel IDs | Store panel, archive, and ticket channel references |
| Discord user IDs and usernames | Track ticket ownership and user actions |
| Ticket status and timestamps | Manage open/closed ticket state |
| Message content (transcripts) | Generate ticket transcripts upon closing |

---

## 2. How We Use Your Data

The data collected is used **solely** to provide the Bot's core functionality:

- Creating and managing ticket channels
- Tracking ticket ownership and status
- Generating transcripts when a ticket is closed
- Restoring channels if they are accidentally deleted

We do **not** use your data for advertising, analytics, or any purpose beyond operating the Bot.

---

## 3. Data Storage

All data is stored securely in **Google Firebase Firestore**. Firebase is a third-party service governed by [Google's Privacy Policy](https://policies.google.com/privacy).

We do not store data on any other external servers.

---

## 4. Data Sharing

We do **not** sell, trade, or share your data with any third parties, except as required by law.

---

## 5. Data Retention

- **Server configuration data** is retained as long as the Bot remains in your server.
- **Ticket data** is retained indefinitely unless manually cleared.
- Server administrators can delete all stored data for their server at any time by running `/reset`.

> Note: Transcript threads in `#ticket-archive` exist within Discord and are subject to Discord's own data retention policies.

---

## 6. Your Rights

Depending on your location, you may have the right to:

- Access the data we hold about you
- Request deletion of your data
- Object to how your data is processed

To exercise these rights, please open an issue on our [GitHub repository](https://github.com/hanzlr/ticketmate-bot) or contact us directly.

---

## 7. Children's Privacy

TicketMate is not directed at children under the age of 13. We do not knowingly collect data from children under 13. If you believe a child has provided us with their data, please contact us and we will take steps to remove it.

---

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. The effective date at the top of this document will reflect the most recent update. Continued use of the Bot after changes constitutes your acceptance of the updated policy.

---

## 9. Contact

If you have any questions or concerns about this Privacy Policy, feel free to open an issue on our [GitHub repository](https://github.com/hanzlr/ticketmate-bot).
