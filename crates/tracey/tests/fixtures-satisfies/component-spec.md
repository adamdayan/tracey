# Component Requirements

c[comp.decoder]
The decoder SHALL parse input within 10ms.
<!-- r[satisfies sys.latency] -->

c[comp.encoder]
The encoder SHALL serialize output within 10ms.
<!-- r[satisfies sys.latency] -->

c[comp.queue]
The queue SHALL buffer at least 2000 messages.
<!-- r[satisfies sys.throughput] -->
