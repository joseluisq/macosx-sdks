# Mac OS X SDKs

> Some Mac OS X SDKs for development purposes with [osxcross](https://github.com/tpoechtrager/osxcross) (a macOS Cross toolchain for Linux and BSDs).

__NOTE:__

Please ensure you have read and understood first the [Xcode license terms](https://www.apple.com/legal/sla/docs/xcode.pdf).

## SDKs

- [Mac OS X 15.5 (macOS Sequoia)](https://github.com/joseluisq/macosx-sdks/releases/tag/15.5)
- [Mac OS X 15.4 (macOS Sequoia)](https://github.com/joseluisq/macosx-sdks/releases/tag/15.4)
- [Mac OS X 15.2 (macOS Sequoia)](https://github.com/joseluisq/macosx-sdks/releases/tag/15.2)
- [Mac OS X 15.1 (macOS Sequoia)](https://github.com/joseluisq/macosx-sdks/releases/tag/15.1)
- [Mac OS X 15.0 (macOS Sequoia)](https://github.com/joseluisq/macosx-sdks/releases/tag/15.0)
- [Mac OS X 14.5 (macOS Sonoma)](https://github.com/joseluisq/macosx-sdks/releases/tag/14.5)
- [Mac OS X 14.4 (macOS Sonoma)](https://github.com/joseluisq/macosx-sdks/releases/tag/14.4)
- [Mac OS X 14.2 (macOS Sonoma)](https://github.com/joseluisq/macosx-sdks/releases/tag/14.2)
- [Mac OS X 14.0 (macOS Sonoma)](https://github.com/joseluisq/macosx-sdks/releases/tag/14.0)
- [Mac OS X 13.3 (macOS Ventura)](https://github.com/joseluisq/macosx-sdks/releases/tag/13.3)
- [Mac OS X 13.1 (macOS Ventura)](https://github.com/joseluisq/macosx-sdks/releases/tag/13.1)
- [Mac OS X 13.0 (macOS Ventura)](https://github.com/joseluisq/macosx-sdks/releases/tag/13.0)
- [Mac OS X 12.3 (macOS Monterey)](https://github.com/joseluisq/macosx-sdks/releases/tag/12.3)
- [Mac OS X 12.1 (macOS Monterey)](https://github.com/joseluisq/macosx-sdks/releases/tag/12.1)
- [Mac OS X 12.0 (macOS Monterey)](https://github.com/joseluisq/macosx-sdks/releases/tag/12.0)
- [Mac OS X 11.3 (macOS Big Sur)](https://github.com/joseluisq/macosx-sdks/releases/tag/11.3)
- [Mac OS X 11.1 (macOS Big Sur)](https://github.com/joseluisq/macosx-sdks/releases/tag/11.1)
- [Mac OS X 10.15 (macOS Catalina)](https://github.com/joseluisq/macosx-sdks/releases/tag/10.15)
- [Mac OS X 10.14 (macOS Mojave)](https://github.com/joseluisq/macosx-sdks/releases/tag/10.14)
- [Mac OS X 10.13 (macOS High Sierra)](https://github.com/joseluisq/macosx-sdks/releases/tag/10.13)
- [Mac OS X 10.12 (macOS Sierra)](https://github.com/joseluisq/macosx-sdks/releases/tag/10.12)
- [Mac OS X 10.11 (OS X El Capitan)](https://github.com/joseluisq/macosx-sdks/releases/tag/10.11)
- [Mac OS X 10.10 (OS X Yosemite)](https://github.com/joseluisq/macosx-sdks/releases/tag/10.10)
- [Mac OS X 10.9 (OS X Mavericks)](https://github.com/joseluisq/macosx-sdks/releases/tag/10.9)

All SDKs were packaged using **osxcross**. Check out [Packaging the SDK on macOS](https://github.com/tpoechtrager/osxcross#packaging-the-sdk) for more details.

## JSON SDKs

A list of all provided SDKs can be also found on [macosx_sdks.json](./macosx_sdks.json).

## Contributions

If you would like to contribute a new SDK, please make sure of the following:

- Your SDK is packaged using osxcross. See [Packaging the SDK on macOS](https://github.com/tpoechtrager/osxcross#packaging-the-sdk) for more details.
- Please only one pull request per SDK (for better tracking and consistency reasons).
- Add an entry in the [SDKs](#sdks) section as well as in [macosx_sdks.json](./macosx_sdks.json) file (follow the *newer/up - older/down* order).
- Provide a link for the preliminary download of your SDK and its [SHA256SUM](https://linux.die.net/man/1/sha256sum) for testing.
- Open a [pull request](https://github.com/joseluisq/macosx-sdks/pulls) and wait for approval. Usually after merging, a new release should be coming right after.

Feel free to file an [issue](https://github.com/joseluisq/macosx-sdks/issues).

## Resources

- [Official macOS Release Notes Website](https://developer.apple.com/documentation/macos-release-notes)
- [Rust Linux / Darwin Builder](https://github.com/joseluisq/rust-linux-darwin-builder) - One Docker image to cross-compile Rust programs for Linux (musl libc) or macOS.
