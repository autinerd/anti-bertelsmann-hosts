# Anti Bertelsmann hosts file

This file blocks all connections to sites which are from Bertelsmann or have a connection with them.

## How to install

### Windows:

- Paste the content of the file bertelsmann-hosts into `%WINDIR%\System32\etc\hosts` (admin rights are neccessary)

### Linux:

- Paste the content of the file bertelsmann-hosts into `/etc/hosts` (root rights are neccessary)

### uBlock Origin and other adblock add-ons

- Add `https://raw.githubusercontent.com/autinerd/anti-bertelsmann-hosts/master/bertelsmann-hosts` to the custom filter lists.

## Contributing

When you find a domain which belongs to Bertelsmann and it's not on the list or there is a domain which doesn't belong to Bertelsmann, feel free to open an issue or do a pull request.
