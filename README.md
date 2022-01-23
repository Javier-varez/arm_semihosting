
# arm-semihosting

Semihosting implementation targetting aarch64 and arm32 architectures. So far it has only been tested on aarch64, but the differences across architectures should be pretty minimal.

At the moment using this crate requires you to declare an allocator for `alloc` if you're running in a `no_std` environment.
