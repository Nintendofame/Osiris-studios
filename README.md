# Kewlbeerd Live room foundation

This is the first room-flow slice for Kewlbeerd Live. It provides a small static client for creating a public scheduled room and finding an existing scheduled or live room.

## Supabase setup

1. Copy the project URL and public anon key into `config.js`.
2. Serve the repository as a static site.
3. Test room creation and lookup.

The database foundation is already present in Supabase: `live_sessions`, `live_feeds`, `room_chat_messages`, and `engagement_events`.

The next slice adds authenticated creator ownership, realtime presence, room chat, and the first media-feed adapter. Never place a service-role key in browser code.