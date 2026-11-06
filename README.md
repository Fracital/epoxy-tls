# @mercuryworkshop/epoxy-tls (Fracital build)

Prebuilt output of [Fracital/epoxy-tls](https://github.com/Fracital/epoxy-tls) branch
`fracital`: epoxy-tls 2.1.20 with the HTTP/2 client accepting response header blocks up
to 256 KiB (Chrome parity) instead of hyper's 16 KiB default, which reset YouTube and
other header-heavy sites with `PROTOCOL_ERROR`. Built with `RELEASE=1 bash publish.sh`
in a Rust nightly container (`Dockerfile.fracital` on the source branch).

Install: `"@mercuryworkshop/epoxy-tls": "github:Fracital/epoxy-tls#<commit on this branch>"`.
