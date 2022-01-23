
# arm-semihosting

Semihosting implementation targetting aarch64 and arm32 architectures. So far it has only been tested on aarch64, but the differences across architectures should be pretty minimal.

At the moment using this crate requires you to declare an allocator for `alloc` if you're running in a `no_std` environment.

## License

Licensed under either of:
  * Apache License, Version 2.0 (LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
  * MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)
at your option.
