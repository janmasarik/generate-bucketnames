# generate-bucketnames
Simple script to generate small amount of possible bucketnames, without the complexity of `altdns`.

## Usage
```bash
$ docker run s14ve/generate-bucketnames --help
Usage: docker run s14ve/generate-bucketnames [OPTIONS]

Options:
  -d, --domains TEXT   List of domains
  -sd, --domain TEXT   Single domain name
  -w, --wordlist TEXT  List of possible bucket names like admin, dev, logs
  -o, --output TEXT    Output file name
  --help               Show this message and exit.
```
