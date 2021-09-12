# Playing Around with Solana

Solana [docs here](https://docs.solana.com/)

YT Video Series [link](https://youtube.com/playlist?list=PL41Cw3fN3CfdbmhgxADwyDyIoDrxc22v2)

## Getting started

Checkout out the [install guide](README-installation-notes.md) for a more detailed set of instructions on how to get up and running for the first time.

## ENV Setup

Ensure that the Solana logs are getting propagated through.

```bash
export RUST_LOG=solana_runtime::system_instruction_processor=trace,solana_runtime::message_processor=debug,solana_bpf_loader-debug,solana_rbpf=debug
```

```bash
solana logs -u localhost
```
