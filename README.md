# Tabsaku

Tabsaku is a free, privacy-first Android money book. It reads the transaction emails and app notifications your banks and e-wallets already send, records your income, spending and transfers by itself, and keeps a balance for each account. Everything stays on your phone: no account to sign up for, no server, no cloud AI. The only place Tabsaku connects to is your own mail server.

This repository hosts the signed APK releases and the [privacy policy](https://byciikel.github.io/tabsaku-releases/privacy.html).

## Features

- Records transactions automatically from bank emails and app notifications
- Balance per account, with balance recalibration
- Transfers between your own accounts are recorded as Pindah dana, not as spending
- Buku: spending and income by category, monthly comparison over six months, your own categories
- Belum terbaca: messages Tabsaku can't read yet wait for you to enter them, nothing is lost
- Kebun saku: a pocket garden that grows with your weekly habits, never with amounts
- App lock (fingerprint or PIN), home-screen widget, CSV export, delete all data

## Supported banks and e-wallets

| Bank / e-wallet | Email | App notification |
| --- | --- | --- |
| BCA | ✓ | ✓ (myBCA) |
| Bank Jago | ✓ | ✓ |
| blu by BCA Digital | ✓ | ✓ |
| BSI (BYOND) | ✓ | |
| BRI | ✓ (QRIS) | ✓ (BRImo, money in) |
| Superbank | ✓ | ✓ |
| OVO | | ✓ |

Bank Mandiri and BNI can already be added, but their messages are not read automatically yet; they wait in Belum terbaca for you to enter them. Coming soon: CIMB Niaga, Permata, SeaBank, GoPay.

Missing your bank, or a message that isn't recognised? Open an issue in this repository (please remove account numbers and names first).

## Install

Requires Android 8.0 or newer.

1. Download `tabsaku-<version>.apk` from the [latest release](https://github.com/byciikel/tabsaku-releases/releases/latest).
2. Check its SHA-256 against the `.sha256` file attached to the same release.
3. Open the APK and allow installing from your browser or file manager when Android asks.

## Update

In the app, go to Pengaturan → Periksa pembaruan, or install the newer APK directly over the old one. Your data stays.
