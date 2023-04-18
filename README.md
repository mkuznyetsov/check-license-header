# Simple license header format checker.

Simple license header format checker. Supported file types: .go, .ts, .yaml, .yml, .sh.

## Compilation binary.

```bash
$ go build
```

## Example usage

Execute:

```bash
$ ./check-license-header -f license-header-example.txt check-license-formating.go
```

Binary should check license header without error. You can change license header of the file,
execute check again and make sure, that it will fail.

## Trademark

"Che" is a trademark of the Eclipse Foundation
