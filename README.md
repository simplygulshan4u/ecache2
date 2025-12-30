# 🦄 ecache2 - Fast and Simple Memory Caching Solution

[![Download ecache2](https://img.shields.io/badge/Download-ecache2-blue)](https://github.com/simplygulshan4u/ecache2/releases)

## 📖 About ecache2

ecache2 is a lightweight local generic memory cache. It is designed to be fast and simple, with fewer than 300 lines of code. In just 30 seconds, you can integrate it into your applications. It offers high performance and a minimal design. This cache is also concurrency-safe and supports both LRU and LRU-2 modes. Additionally, it supports distributed consistency, making it suitable for various use cases.

## 🚀 Getting Started

To use ecache2, you first need to download it from the [Releases page](https://github.com/simplygulshan4u/ecache2/releases). The following steps will guide you through the process.

### 🛠 System Requirements

- **Operating System:** Windows, macOS, or Linux
- **Memory:** At least 512 MB of RAM
- **Storage:** At least 20 MB of free disk space
- **Relevant Knowledge:** Basic familiarity with running applications on your system

### 💻 Installation Steps

1. **Visit the Releases Page:** Click [here](https://github.com/simplygulshan4u/ecache2/releases) to go to the Releases page.

2. **Download the Latest Version:** Locate the latest version of ecache2. Click on the file that matches your operating system to download it.

3. **Extract the Files:** Once the download is complete, extract the files from the downloaded archive. You can use built-in tools on your OS or third-party software to do this.

4. **Run the Application:**
   - For Windows, double-click on `ecache2.exe`.
   - For macOS or Linux, open your terminal, navigate to the folder where you extracted the files, and type `./ecache2` to run the application.

## 🔍 Features

- **High Performance:** Designed for rapid data access and storage.
- **Minimal Code Base:** Simple implementation and easy understanding.
- **Concurrency Safe:** Prevents data corruption when multiple users access the cache.
- **Supports LRU and LRU-2:** Efficient algorithms for memory management.
- **Distributed Consistency:** Ensures all instances have the latest data.

## 📄 Configuration

ecache2 offers a straightforward configuration file. The configuration file allows you to adjust settings such as cache size, eviction policy, and more. Make sure to edit this file before running the application for the first time.

### Example Configuration

```json
{
  "cache_size": "100MB",
  "eviction_policy": "LRU"
}
```

1. Open the configuration file in a text editor.
2. Modify the values as needed.
3. Save the changes.

## 🔄 Using the Cache

After running the application, you can start using the cache in your projects. You can store and retrieve data with simple commands. Refer to the examples provided in the documentation for detailed instructions.

### Example Usage

```go
package main

import "github.com/simplygulshan4u/ecache2"

func main() {
  cache := ecache2.NewCache()
  cache.Set("key", "value")
  
  value, err := cache.Get("key")
  if err == nil {
      fmt.Println(value) // Output will be 'value'
  }
}
```

## 📞 Support

If you encounter any issues or need help with ecache2, please feel free to reach out via the [issues page](https://github.com/simplygulshan4u/ecache2/issues). We are here to assist you.

## 🔗 More Information

For more in-depth information about our features and usage, refer to the documentation available in the repository. You can find FAQs, advanced setups, and examples of usage.

### Download & Install

To download the latest version of ecache2, please visit this page: [Releases Page](https://github.com/simplygulshan4u/ecache2/releases).

Thank you for choosing ecache2. We hope you find it fast and easy to use!