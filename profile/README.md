This organization is born in order to keep the awesome `pkg` tool and it's companion tool `pkg-fetch` alive after they have been archived.

## `pkg`

`@yao/pkg` is the most active and updated fork of the original [vercel/pkg](https://github.com/vercel/pkg) project. It packages your Node.js project into standalone executables, making it easy to distribute without requiring Node.js to be installed on the target system.

#### Features:
- Cross-platform packaging (Linux, macOS, Windows)
- Produces standalone executables
- Simple and efficient distribution of Node.js projects
- Actively maintained and improved

Visit the [@yao-pkg/pkg](https://github.com/yao-pkg/pkg) to learn more or contribute to its development!

## `pkg-fetch`

`@yao/pkg-fetch` is the companion tool to `@yao/pkg`. It is responsible for building and downloading the patched Node.js executables used by `@yao/pkg` to create the standalone binaries. This process ensures that applications packaged with `@yao/pkg` are fully self-contained and optimized for various platforms.

#### Features:
- Builds patched Node.js executables
- Downloads prebuilt binaries for quick packaging
- Supports multiple Node.js versions and platforms

Explore the [@yao-pkg/pkg-fetch](https://github.com/yao-pkg/pkg-fetch) for more details or to contribute.
