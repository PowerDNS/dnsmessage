# The PowerDNS DNSMessage protobuf format

This repository contains the [protobuf] message format used by the protobuf
logging feature in [PowerDNS and dnsdist].

See the relevant [PowerDNS Recursor documentation] and [dnsdist documentation]
for details.

## Contributing

Any changes to this protobuf need to be accepted in this repository first,
before they are used in the PowerDNS server implementations.
The [PowerDNS and dnsdist] repository contains a vendored copy of this file
that must not be directly updated.

## License

The protobuf description and all supporting tools in this repository are
licensed under the MIT license.


[PowerDNS and dnsdist]: https://github.com/PowerDNS/pdns
[protobuf]: https://developers.google.com/protocol-buffers
[PowerDNS Recursor documentation]: https://docs.powerdns.com/recursor/lua-config/protobuf.html
[dnsdist documentation]: https://dnsdist.org/reference/protobuf.html
