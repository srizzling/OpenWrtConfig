## OpenWrtConfig

A Ansible Playbook to configure openwrt for my liking. If it works for you then great! If it doesn't then send a PR. I purposely haven't made it easier to config, because OpenWrt is different for everybody.

## Installation

** Requiured tools **
- Ansible
- A router with OpenWRT installed

Then you need to configure OpenWRT to allow ssh access.

## My Usecase

The first role is setting up OpenWRT. Sets up Hostname and installs basic packages
The second role is configuring a dumb AP to use in the flat.
The third role will vary by use-case depending on performance tests to ensure that you acheive the best performance for your needs.

I mostly found the tutorial below handy for configuring and tuning my OpenWRT.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

TODO: Write license
