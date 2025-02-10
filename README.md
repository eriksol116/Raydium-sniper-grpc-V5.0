# 🚀Raydium Sniper Bot -Version 5.0 (using Geyser(Yellowstone)) 

This is Raydium sniper bot that snipe token in solana within next block of pool creation by using grpc

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

## 🧑‍💻 **Transactions and Dexscreenshot**
Result:


![raydium-sniper-grpc-2block](https://github.com/user-attachments/assets/d057a1e4-424b-4dd1-8f00-f32739c6744f)

Raydium pool creation: [https://solscan.io/tx/2EDyXtVm2iXBYyirFaRagSC259B1SYCiA3iJkJgzmE1KFDTgXXgwdfPoa7RLxX9e2Qo4gFtuinRZQdDrMwEedeKp](https://solscan.io/tx/2EDyXtVm2iXBYyirFaRagSC259B1SYCiA3iJkJgzmE1KFDTgXXgwdfPoa7RLxX9e2Qo4gFtuinRZQdDrMwEedeKp)

![raydium-sniper-grpc-1block-poolcreation](https://github.com/user-attachments/assets/eade4a3c-8978-43ca-ad3c-892a463d5ef2)



Token snipe and buy : [https://solscan.io/tx/BFwmxJeWrLxbzkzFUruzSQiHApTstfGqPm7ZLusTJesJp1eYy1NC3dMVw2oJCEkqQN8TWMeYk9sqCBv6UExAtRr](https://solscan.io/tx/BFwmxJeWrLxbzkzFUruzSQiHApTstfGqPm7ZLusTJesJp1eYy1NC3dMVw2oJCEkqQN8TWMeYk9sqCBv6UExAtRr)


![raydium-sniper-grpc-1block-buy](https://github.com/user-attachments/assets/6905600a-b52b-48a9-ae5a-db6846d92d1d)


Token sell : [https://solscan.io/tx/26cpMsZhMLfYjVk1zY5kEWP47CpUJsNHoGCAYUph3Uq8PMzv5BRrh5q4ZFFmxKorDVDMGo5kGfooQpxDLW9VEe2N](https://solscan.io/tx/26cpMsZhMLfYjVk1zY5kEWP47CpUJsNHoGCAYUph3Uq8PMzv5BRrh5q4ZFFmxKorDVDMGo5kGfooQpxDLW9VEe2N)


![raydium-sniper-grpc-1block-sell](https://github.com/user-attachments/assets/7228f748-3076-4a34-b2f3-c0a753a1f7fa)

GMGN : 

![raydium-sniper-grpc-1block-gmgn1](https://github.com/user-attachments/assets/b0725d2c-1e0b-4134-b5ae-98bad3d278da)



## 🧑‍💻 **Recording Video**


https://github.com/user-attachments/assets/107ed481-33bd-4e11-ab39-0ec4937e7668


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



