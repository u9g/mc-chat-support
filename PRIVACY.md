# MC Chat Privacy Policy

MC Chat connects your phone to Minecraft Java Edition servers so you can read and send chat. This page explains what the app and its backend handle.

## What is processed

- **Server connection.** When you join a server, the app opens the connection from your phone. A backend run by the developer (mcchat.u9g.dev) performs the Minecraft protocol on your behalf and relays the traffic through your phone, so the server sees your phone's IP address. The backend handles the server address you entered, your player name, and the chat messages you send and receive, for as long as the session lasts.
- **Microsoft sign-in.** Signing in happens on Microsoft's website through the standard device-code flow. MC Chat never sees your password. The resulting Microsoft, Xbox Live, and Minecraft tokens are kept by the backend, tied to a random identifier generated on your device, so you can rejoin servers without signing in again. Signing out from the app's Settings removes that account from the device.
- **Offline names.** An offline name is only sent to the server you join.

## What is not collected

MC Chat has no analytics, advertising, or tracking SDKs. Chat messages are not stored after the session ends. Nothing is sold or shared with third parties beyond the Minecraft server you chose to join and Microsoft during sign-in.

## Operational logs

The backend keeps short-lived technical logs (connection errors, session start and end) to keep the service running. They are not used for profiling.

## Deletion and questions

To have the stored sign-in tokens for your device deleted, or for any other question, email [mc-chat@u9g.dev](mailto:mc-chat@u9g.dev).

MC Chat is not an official Minecraft product and is not approved by or associated with Mojang or Microsoft.
