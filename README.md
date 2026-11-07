# sentinela-licencas

The signed license revocation list that Sentinela installations read (SPEC 15.13): `revoked.json` holds license ids only, no customer name; `revoked.json.sig` is its Ed25519 signature by the vendor key. Made with `node tools/license/cli.ts revoke`; a list that does not verify is ignored.
