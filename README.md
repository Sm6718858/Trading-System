# Deribit Trading System

## 📈 Overview

**Deribit Trading System** is a high-performance, command-line-based order execution and management system designed to interact with the [Deribit Testnet](https://test.deribit.com) via WebSocket. It allows you to trade, manage positions, and control orders efficiently through terminal commands.

---

## 🚀 Features

- 📡 WebSocket-based real-time trading interface  
- 🔐 Secure API authentication  
- 🛒 Support for advanced order types  
- 📊 Portfolio and open orders management  
- ✏️ Modify and cancel orders on the fly  
- 🧠 Command-line interface with built-in help  

---

## 🛠 Tech Stack

- **C++17**
- **CMake**
- **WebSocket++**
- **Boost**
- **OpenSSL**
- **nlohmann/json**
- **Readline**

---

## 📦 Prerequisites

- C++ compiler (g++)
- CMake
- Boost
- OpenSSL
- Git
- Readline

---

## ⚡️ Quick Setup Scripts

git clone https://github.com/Sm6718858/Trading-System.git
cd Trading-System
mkdir build
cd build
cmake .. -Wno-dev
cmake --build .
./deribit_trader

