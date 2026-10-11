<div align="center">

<img src="assets/avian-network-brand.webp" alt="Avian Network" width="720">

# Avian Wallet Guides

**Practical, safety-first help for the Avian Wallet desktop client and Avian (AVN).**

[![Website](https://img.shields.io/badge/Website-avianwallet.com-16a6a1?style=for-the-badge)](https://avianwallet.com) [![Release](https://img.shields.io/badge/Release-v5.0.4-27364b?style=for-the-badge)](https://github.com/avian-network/Avian-Wallet/releases/tag/v5.0.4)

</div>

---

## Download Avian Wallet

[![Download Windows](https://img.shields.io/badge/Windows-Download-16a6a1?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-win64-setup.exe) [![Download macOS](https://img.shields.io/badge/macOS-Download-16a6a1?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-apple.dmg) [![Download Linux](https://img.shields.io/badge/Linux-Download-16a6a1?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-linux.zip)

| Platform | File | Requirements |
|---|---|---|
| Windows | [avian-wallet-v5.0.4-win64-setup.exe](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-win64-setup.exe) | Windows 10 or 11, 64-bit |
| macOS | [avian-wallet-v5.0.4-apple.dmg](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-apple.dmg) | Apple silicon or Intel |
| Linux | [avian-wallet-v5.0.4-linux.zip](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-linux.zip) | 64-bit desktop distribution |

> [!TIP]
> Verify installer hashes on the [tagged v5.0.4 Release](https://github.com/avian-network/Avian-Wallet/releases/tag/v5.0.4). Checksums are deliberately maintained there and in the main app README.

## Installation guides

| Guide | Direct answer |
|---|---|
| [Download Avian Wallet for Windows](docs/download-avian-wallet-windows.md) | Install the current Windows desktop wallet from the verified v5.0.4 release. |
| [Download Avian Wallet for macOS](docs/download-avian-wallet-macos.md) | Use the current DMG for Apple silicon or Intel Macs and verify it before opening. |
| [Download Avian Wallet for Linux](docs/download-avian-wallet-linux.md) | Download the current Linux archive, keep it in a dedicated folder, and verify the file. |
| [Avian Wallet System Requirements Explained](docs/avian-wallet-system-requirements.md) | Plan for a 64-bit desktop, a steady connection, and enough storage for full-node synchronization. |
| [How to Update Avian Wallet Safely](docs/update-avian-wallet-safely.md) | Back up first, close the old wallet cleanly, and install the current release from the official source. |
| [Avian Wallet FAQ for New Desktop Users](docs/avian-wallet-faq-new-users.md) | Start with the current installer, protect recovery material, allow synchronization to finish, and verify addresses before sending. |

## Security guides

| Guide | Direct answer |
|---|---|
| [How to Verify an Avian Wallet SHA-256 Checksum](docs/verify-avian-wallet-sha256.md) | Compare the downloaded installer fingerprint with the value published on the tagged release. |
| [Avoid Unofficial Avian Wallet Bootstrap Downloads](docs/safe-avian-wallet-bootstrap-alternatives.md) | Prefer the current wallet’s verified synchronization path over third-party archives shared in chats or forums. |
| [Can Someone Steal AVN with Your Wallet Address?](docs/avian-wallet-address-safety.md) | A public receive address is meant to be shared, but a private key, recovery phrase or wallet.dat must stay secret. |
| [Avian Wallet Anti-Phishing Checklist](docs/avian-wallet-anti-phishing.md) | Use only the tagged release and never give support, strangers or recovery sites your phrase, private key or wallet.dat. |
| [Is Avian Wallet Open Source and Safe to Use?](docs/avian-wallet-open-source-safety.md) | Open source enables inspection, but users still need official downloads, checksum verification, backups and careful transaction review. |

## Sync guides

| Guide | Direct answer |
|---|---|
| [Avian Wallet Not Syncing: A Safe Checklist](docs/avian-wallet-not-syncing.md) | Confirm the version, connection and sync status before trying more invasive recovery steps. |
| [Avian Wallet Stuck Connecting to Peers](docs/avian-wallet-stuck-connecting.md) | Use the current wallet and read its peer and sync indicators before changing network settings. |
| [Why Avian Wallet Shows a Zero Balance](docs/avian-wallet-zero-balance.md) | A restored or imported wallet can show zero until the correct wallet is open and synchronization completes. |
| [When to Rescan Avian Wallet](docs/avian-wallet-rescan-guide.md) | Use a rescan when known wallet data is open but historical transactions have not been rediscovered. |
| [Understanding Avian Wallet Peer Count and Sync Status](docs/avian-wallet-peer-count.md) | Peer count and sync percentage describe network progress; neither alone proves a balance is final. |

## Backup guides

| Guide | Direct answer |
|---|---|
| [How to Back Up Avian Wallet wallet.dat](docs/backup-avian-wallet-dat.md) | Copy wallet.dat while the wallet is closed, keep more than one protected copy, and test your recovery plan. |
| [How to Restore Avian Wallet from wallet.dat](docs/restore-avian-wallet-dat.md) | Install the current wallet, preserve the original file, and use the guided restore flow rather than experimenting on your only copy. |
| [Avian Wallet Recovery Phrase Safety](docs/avian-wallet-recovery-phrase.md) | Keep the phrase offline and private; anyone who obtains it may be able to control the restored wallet. |
| [What Is an Avian Wallet wallet.dat File?](docs/wallet-dat-file-explained.md) | wallet.dat is sensitive wallet data, not a document to upload to a viewer or send to support. |
| [Handling a Damaged Avian wallet.dat Safely](docs/recover-corrupted-wallet-dat-safely.md) | Stop changing the original, work from copies, and avoid tools that ask you to upload private wallet data. |
| [What If an Avian Wallet Backup Is Missing?](docs/lost-avian-wallet-no-backup.md) | First locate every possible wallet.dat or recovery-phrase copy; there is no honest shortcut around missing key material. |
| [Does an Avian Wallet USB Backup Update Automatically?](docs/avian-wallet-backup-usb.md) | A copied backup is a snapshot, not a live mirror, so make a fresh protected copy after important wallet changes. |

## Migration guides

| Guide | Direct answer |
|---|---|
| [How to Import a RavencoinLite Wallet into Avian Wallet](docs/import-ravencoinlite-wallet.md) | Keep the old wallet.dat untouched, install Avian Wallet, import a copy, and let the rescan complete. |
| [RavencoinLite to Avian Wallet Migration Guide](docs/rvl-to-avn-migration.md) | The wallet transition uses existing wallet data; it is not an instruction to send RVN or use a token swap. |
| [RavencoinLite Coins Not Showing in Avian Wallet](docs/ravencoinlite-coins-not-showing.md) | Check that the intended wallet file is open and synchronization or rescanning has finished before judging the balance. |
| [How to Find an Old RavencoinLite wallet.dat](docs/find-old-ravencoinlite-wallet-dat.md) | Search backups and old computers carefully, copy any candidate file, and never move or overwrite the only original. |
| [RavencoinLite and Avian: What Wallet Users Need to Know](docs/ravencoin-lite-vs-avian.md) | Avian Wallet supports the Avian network and legacy RavencoinLite wallet migration; it does not claim support for Ravencoin (RVN). |
| [Ravencoin and RavencoinLite Wallets Are Not the Same](docs/ravencoin-vs-ravencoinlite-wallets.md) | Treat RVN and the Avian/RVL path as separate networks, files and addresses to avoid a costly assumption. |

## Coin guides

| Guide | Direct answer |
|---|---|
| [What Is Avian Coin (AVN)?](docs/what-is-avian-coin.md) | AVN is the native coin of the Avian proof-of-work network and can be held in the self-custody Avian Wallet. |
| [Avian Coin Supply, Units and Block Time](docs/avian-coin-supply-block-time.md) | Avian uses AVN, eight decimal places, a 21 billion maximum supply and a target block time of about 30 seconds. |
| [What a Full-Node Avian Wallet Does](docs/avian-full-node-wallet.md) | The desktop wallet verifies network data locally, which requires initial synchronization and ongoing storage. |

## Transactions guides

| Guide | Direct answer |
|---|---|
| [How to Receive AVN in Avian Wallet](docs/how-to-receive-avn.md) | Create or copy a receive address in the current wallet, verify it on screen, and share only the public address. |
| [How to Send AVN from a Desktop Wallet](docs/send-avn-from-desktop-wallet.md) | Confirm the destination, amount and fee preview before authorizing an irreversible blockchain transaction. |
| [How to Withdraw AVN to Avian Wallet](docs/withdraw-avn-to-desktop-wallet.md) | Copy a fresh receive address, verify the network and use a small test withdrawal when the sending service allows it. |

## Mining guides

| Guide | Direct answer |
|---|---|
| [How to Mine Avian with a GPU on X16RT](docs/mine-avian-with-gpu-x16rt.md) | Prepare an AVN receive address first, then configure compatible mining software and a chosen pool independently. |
| [How to Mine Avian with a CPU on MinotaurX](docs/mine-avian-with-cpu-minotaurx.md) | Use a verified AVN receive address and treat miner and pool configuration as separate from wallet custody. |
| [Set an Avian Mining Payout Address Safely](docs/avian-mining-payout-address.md) | Copy a receive address from Avian Wallet, check it character by character, and avoid exposing wallet secrets to a pool. |
| [Avian GPU vs CPU Mining: X16RT and MinotaurX](docs/avian-gpu-vs-cpu-mining.md) | Avian uses X16RT for GPU mining and MinotaurX for CPU mining, with separate difficulty adjustment. |

---

## About

This repository contains original Avian Wallet help articles informed by published product documentation, saved search research and community questions. Visit the [Avian Wallet website](https://avianwallet.com), review [wallet security guidance](https://avianwallet.com/security), or get the [current desktop download](https://avianwallet.com/download).

## License

Documentation in this repository is provided under the MIT License. Software repositories may carry their own license notices.
