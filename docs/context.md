Context
=======

This module is a component in the [DANS Data Station Architecture]{:target=_blank}.

[DANS Data Station Architecture]: https://dans-knaw.github.io/dans-datastation-architecture/

The `dd-sword2` service is the [DANS]{:target=_blank} implementation of the [SWORDv2]{:target=_blank} protocol. It is a rewrite in Java of the Scala-based
project [easy-sword2]{:target=_blank}. Like its predecessor, it does **not** implement the full SWORDv2 specifications. Also, since the SWORDv2 specs leave
various important issues up to the implementer, the service adds some features.

The best starting point for learning about `dd-sword2` is this document. Where appropriate, this document contains references to the
[SWORDv2 specifications document]{:target=_blank}. When reading the SWORDv2 docs, keep in mind that it is itself built on other specifications, and refers to
those often, especially:

* [AtomPub]{:target=_blank}
* [Atom]{:target=_blank}
* [HTTP]{:target=_blank}

[DANS]: https://www.dans.knaw.nl/

[SWORDv2]: https://sword.cottagelabs.com/previous-versions-of-sword/sword-v2/

[easy-sword2]: https://dans-knaw.github.io/easy-sword2/

[AtomPub]: https://www.ietf.org/rfc/rfc5023.html

[Atom]: https://www.ietf.org/rfc/rfc4287.html

[HTTP]: https://www.rfc-editor.org/rfc/rfc2616.html

[SWORDv2 specifications document]: https://swordapp.github.io/SWORDv2-Profile/SWORDProfile.html