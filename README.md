# 🎬 CineCache

A distributed caching system implemented in C++ for high-performance data retrieval with movie database integration.

---

## 📖 Overview

CineCache is a sophisticated caching layer designed to efficiently manage and retrieve movie data using advanced cache management techniques, consistent hashing for distributed systems, and eviction policies for optimal memory utilization.

---

## ✨ Features

* 🔄 **LRU (Least Recently Used) Cache** – Automatic eviction of least-used items
* 🌐 **Consistent Hashing** – Enables distributed caching across multiple nodes
* ⚡ **Hash Table Implementation** – Fast O(1) lookups for cache operations
* 🔗 **Doubly Linked List** – Core data structure for LRU ordering
* 🎥 **Movie Database Integration** – IMDB dataset for testing
* 🧹 **Flexible Eviction Policies** – Efficient memory management
* 🖥️ **Interactive UI** – Terminal-based interface for cache operations

---

## 📦 Download & Installation

### Prerequisites

* 🔧 Git
* ⚙️ C++ Compiler (GCC, Clang, or MSVC)
* 📐 CMake 3.10+
* 🐍 Python 3.7+ (for data extraction)

### Clone the Repository

```bash
git clone https://github.com/yourusername/CineCache.git
cd CineCache
```

---

## 🚀 Quick Start

### 1. Install Dependencies (macOS)

```bash
brew install cmake
```

### 2. Build the Project

```bash
./build.sh
```

Or manually:

```bash
mkdir -p build && cd build
cmake ..
make
```

### 3. Run CineCache

```bash
./build/bin/cinecache
```

---

## 🗂️ Project Structure

```
CineCache/
├── src/
│   ├── main.cpp
│   ├── cache/
│   ├── common/
│   ├── data_structures/
│   ├── database/
│   └── hashing/
├── engine/
├── data/
├── CMakeLists.txt
├── build.sh
├── extract_movies.py
└── README.md
```

---

### Platform-Specific Builds

#### Linux (Ubuntu/Debian)

```bash
sudo apt-get install build-essential cmake python3
./build.sh
```

#### macOS

```bash
./build.sh
```

#### Windows (Visual Studio)

```cmd
./build.bat
```

---

## Running

```bash
./build/bin/cinecache
```

---

## Component Documentation

### Cache Layer (`src/cache/`)

* LRU Cache with automatic eviction
* TTL support for expiration

### Data Structures (`src/data_structures/`)

* Hash Table – O(1) operations
* Doubly Linked List – Maintains LRU order

### Hashing (`src/hashing/`)

* Consistent Hashing for distributed nodes
* Optimized hash functions

### Database (`src/database/`)

* Simulated IMDB movie database
* Realistic testing scenarios

### Engine (`engine/`)

* Cache Nodes for distributed system
* Terminal UI
* Configurable eviction policies
* System coordination layer

---


## Future Enhancements

* Multi-threaded cache operations
* Distributed node communication
* Advanced monitoring & analytics
* Serialization support
* Persistence layer
* REST API
* Web dashboard

---


## Support

For issues or suggestions, open an issue in the repository.

---

