Refer to

https://github.com/jotelha/dtool-sync

```console
$ dtool compare all -jq smb://lhs s3://rhs
{
    "equal": [
        "065d9fe0-9e41-4add-8a55-577dbcfe2149",
        "9ee101a4-7d1a-45c0-8955-da779398a5ed",
        "c2249963-6459-4901-8263-85610a7a2ac9"
    ],
    "changed": [
        "af16c00d-f60d-41ce-83c6-2a7d9c5e1b0d"
    ],
    "missing": [
        "534792bd-d102-4efc-bc11-6af743959704"
    ]
}
```
