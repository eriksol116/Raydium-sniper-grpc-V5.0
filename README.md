# 🚀Raydium Sniper Bot -Version 5.0 (using Geyser(Yellowstone)) 

This is Raydium sniper bot that snipe token in solana within 1-2 block after pool creation by using grpc

Welcome to the Raydium Sniper Bot v5.0! This bot watches for new Raydium Pool Creation on the Solana blockchain in real-time by using Geyser(Yellowstone), making it the perfect tool to monitor token launches. 🌟

### 🎯 **Key Features**

- 🛰️ **Real-time WebSocket Streaming**: 
  Connects to Solana's blockchain through Helius RPC WebSocket or  VibeStation RPC WebSocket and listens for new transactions, specifically targeting `Raydium New Pool Creation`  instructions.
  
- 🔍 **Filter Raydium Pool Creation**: 
  Filters transactions by program IDs and instruction discriminators related to `Raydium Pool`.

- 📊 **Formatted Data**: 
  Logs essential transaction details like the transaction signature, creator's wallet, and the minted token address when a new `Raydium` Pool is detected.

- ⚡ **Efficient Stream Handling**: 
  Handles WebSocket stream events efficiently, ensuring no loss of data and continuous monitoring.

---

## 📞 **Stay Connected**

Gmail: tom.kinddev@gmail.com

Telegram: [@erikerik116](https://t.me/erikerik116)

Discord: @erikerik116

## 🧑‍💻 **Recording Video**

## 🚀 **Getting Started**

Follow these steps to get your **PumpFun Sniper Bot v5.2** up and running!

### Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/eriksol116/Raydium-sniper-grpc-V5.0.git
    ```

2. **Install Dependencies**:

    Navigate to the project directory and run the following command:

    ```bash
    cd Raydium-sniper-grpc-V5.0
    npm install
    ```

3. **Configure API Token**:

    Add Solana Vibe Station API key to both the `RPC_ENDPOINT` and `RPC_WEBSOCKET_ENDPOINT` fields in the .env file

    ```ts
    const ENDPOINT = "http://ultra.swqos.solanavibestation.com/?api_key=";

    const RPC_WEBSOCKET_ENDPOINT = "wss://ultra.swqos.solanavibestation.com/?api_key=";
    ```
    And set other variables in env file.

4. **Run the Bot**:

    Start the bot by running:

    ```bash
    npm run test
    ```

---



