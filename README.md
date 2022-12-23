# Kleister: Secrets

This repository contains secrets mostly used by the automated provisoning. If
you think you should need access to the defined secrets get in contact with
Thomas, don't forget to add your public GPG key.

## Usage

First of all you got to install [gopass][gopass], you can find instructions
within the [documentation][documentation]. If you are using gopass for the first
time you should execute `gopass init` first, after that you can add this store:

```console
gopass clone https://github.com/kleister/kleister-secrets.git kleister
```

## Security

If you find a security issue please contact
[kleister@webhippie.de](mailto:kleister@webhippie.de) first.

[gopass]: https://www.gopass.pw
[documentation]: https://www.gopass.pw/docs/#installation
