# Altbase XGR module

Source-only XGRChain module for Altbase Wallet 0.1.7.

The module provides the frontend registration, XGR account wallet engine, and
the native node/API boundary for XGRChain mainnet (chain ID 1643). It contains
no compiled libraries or generated build output.

The native `CMakeLists.txt` is a module-registration fragment loaded after the
Altbase native-core SDK helpers; it is not configured as a standalone top-level
CMake build. Platform binaries are produced by the integration build scripts in
the `AltbaseWallet` project.
