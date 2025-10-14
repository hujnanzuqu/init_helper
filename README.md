Real-time Code Collaboration

```javascript
// collab-server.js
socket.on('codeChange', (data) => {
  broadcastToRoom(data.room, 'codeUpdate', data);
});
```

**Features:**
- Live cursor positions
- Concurrent editing
- Change history
- Conflict resolution

Deploy: `docker-compose up`
Tech: Socket.io + React + Node

# PR Merge: 2025-10-15 - feature/merge-3624
