bash_completion
===============
 
Install this like you would any other Bash completion script. Copy it into
your `bash_completion.d` directory. This will probably be one of:

* `/etc/bash_completion.d/`
* `/usr/local/etc/bash_completion.d/`

Make sure that it is `chmod +x` and assuming that you've got completion enabled,
this will take effect on the next login.

This script will adapt as you install new modules with new resource types
and Puppet subcommands. As you might guess, listing all those can take some
time. For responsiveness, they're pre-generated and cached when you log in.
This means that any new commands or types won't be learned until the next
time you log in, but then they'll be blindingly fast.

## Contributing

Pull requests are happily accepted.

## Disclaimer

I take no liability for the use of this script.

Contact
-------

binford2k@gmail.com

