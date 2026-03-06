---
title: "Delegate SD-JWT"
category: info

docname: draft-gco-delegate-sd-jwt-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
# area: AREA
# workgroup: WG Working Group
keyword:
 - security
 - sd-jwt
 - delegate sd-jwt
venue:
  github: "GarethCOliver/gco-delegate-sd-jwt"
  latest: "https://GarethCOliver.github.io/gco-delegate-sd-jwt/draft-gco-delegate-sd-jwt.html"

author:
 -
    fullname: Gareth Oliver
    organization: Google
    email: gco@google.com

normative:
RFC9901:
RFC2046:
RFC6838:

informative:

...

--- abstract

This document specifies an extension to Selective Disclosure JSON Web Tokens [@!RFC9901] to support further delegation from the Holder to a Delegate Holder. This is done by allowing the Key Binding JWT to also be an SD-JWT, optionally with its own Key Binding. This has particular applicability to Agentic systems.


--- middle

# Introduction

TODO Introduction


# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
