# IPNetDB test files

This repository contains MIT-licenced test files in the same format as the
`mmdb` databases available from [IPNetDB](https://ipnetdb.com/). You are
free to use, distribute and embed the test `mmdb` files in this repository
without restrictions as described in the [LICENSE](LICENSE) file.

The test databases contain a tiny subset of the internets structure limited
to just one or two networks and as such are very small.

These files are suitable for embedding into test suites and are designed to
ensure product compatability with the full IPNetDB databases.

All fields and values are identical to the full IPNetDB databases only
the number of entries per database is reduced. For example, you can look
up 8.8.8.8 in the Google prefixes `mmdb` file, however 4.4.4.4 will return
an empty result.

The following test files are currently available:

[Cloudflare preifxes](https://github.com/meeb/ipnetdb-test-files/raw/main/ipnetdb-test-cloudflare-prefix.mmdb)
- Contains information on prefixes advertised by Cloudflare

[Cloudflare ASNs](https://github.com/meeb/ipnetdb-test-files/raw/main/ipnetdb-test-cloudflare-asn.mmdb)
- Contains information on ASNs used by Cloudflare

[Google prefixes](https://github.com/meeb/ipnetdb-test-files/raw/main/ipnetdb-test-google-prefix.mmdb)
- Contains information on prefixes advertised by Google

[Google ASNs](https://github.com/meeb/ipnetdb-test-files/raw/main/ipnetdb-test-google-asn.mmdb)
 - Contains information on ASNs used by Google

Additional test files are available on request. Please open an isssue
if you would like more test databases to be created.

*Note*: these are single snapshot databases, they are accurate at the
time of release but they are only designed to test the data structures.
The data itself is not suitable to be used in projects and is likely to
be innacurate as they are not updated.
