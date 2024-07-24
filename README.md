# regdump
This is a tool that dumps values from the registry of PS5 consoles that has been
jailbroken via the [BD-J][bdj] or the [webkit][webkit] entry points.


## Building and running
Assuming you have the [ps5-payload-sdk][sdk] installed on a Debian-flavored
operating system, the tool can be compiled and executed using the following
commands:
```console
john@localhost:ps5-payload-dev/regdump$ export PS5_PAYLOAD_SDK=/opt/ps5-payload-sdk
john@localhost:ps5-payload-dev/regdump$ make
john@localhost:ps5-payload-dev/regdump$ make test
```

## Known Issues
- Some registry entries cannot be read successfully, not sure why.


## Reporting Bugs
If you encounter problems with regdump, please [file a github issue][issues].
If you plan on sending pull requests which affect more than a few lines of code,
please file an issue before you start to work on you changes. This will allow us
to discuss the solution properly before you commit time and effort.

## License
regdump is licensed under the GPLv3+.

[bdj]: https://github.com/john-tornblom/bdj-sdk
[webkit]: https://github.com/Cryptogenic/PS5-IPV6-Kernel-Exploit
[sdk]: https://github.com/ps5-payload-dev/sdk
[issues]: https://github.com/ps5-payload-dev/regdump/issues/new
