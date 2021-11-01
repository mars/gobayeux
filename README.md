# gobayeux

🍴 Forked from [sigmavirus24/gobayeux](https://github.com/sigmavirus24/gobayeux), because that library is missing a recent version release, and the author's status says "🌴 Taking a break from F/OSS indefinitely".

Bayeux protocol library compatible with [CometD](https://cometd.org/)
and [Faye](https://faye.jcoglan.com/) servers.

### Documentation

- [API Reference](https://pkg.go.dev/github.com/sigmavirus24/gobayeux)
- [Protocol specification](https://docs.cometd.org/current/reference/#_bayeux)

### Installation

```bash
go get github.com/mars/gobayeux
```

### Status

Library provides a basic set of features to start getting notification over `long-polling` transport.

### Protocol compliance

- [x] Handshake
- [x] Connect/Disconnect
- [x] Subscribe/Unsubscribe
- [ ] Publish and Delivery event messages
- [x] The long-polling transport
- [ ] The callback-polling transport
- [ ] The websocket transport

### Authors

- @sigmavirus24
- @L11R

### License

Apache 2.0