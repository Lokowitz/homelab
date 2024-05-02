Notification script for Openmediavault to Gotify.

1. Place the "gotify" file in /usr/share/openmediavault/notification/sink.d on your OMV system.
2. Repleace "<URL>" and "<TOKEN>" in the script
3. Make file executable (chmod +x gotify)
4. Activate notifications via smtp.


Make sure you have curl installed.

Based on this documentations:
- https://gotify.net/docs/pushmsg
- https://gotify.net/docs/more-pushmsg#bash-using-curl-and-markdown
- https://docs.openmediavault.org/en/latest/administration/general/notifications.html#third-party-notifications
