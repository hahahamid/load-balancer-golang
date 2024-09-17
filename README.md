# Go Load Balancer

![Go](https://img.shields.io/badge/Go-1.20-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A simple and efficient load balancer implemented in Go. This project demonstrates how to distribute incoming HTTP requests across multiple backend servers using the Round Robin algorithm. It's designed to be easy to understand and extend, making it a great starting point for building more complex load balancing solutions.

- **Usage:** A minimal program to balance and redirect server requests.
- **Prevents single point of failure:** Ensures that SPoFs are eliminated in case of HTTP requests.
- **Custom domains:** The redirect URL can be fully customized.
- **Low complexity:** The application is relatively simple to understand and work with.
- **No limit on server URLs:** The number of proxy servers can be added single-handedly.
- **Improves overall reliability:** Improves the reliability of the network by efficient distribution of requests.


## Features

- **Round Robin Load Balancing:** Distributes incoming requests evenly across multiple backend servers.
- **Reverse Proxy:** Utilizes Go's `httputil.ReverseProxy` to forward requests to backend servers.
- **Health Checks:** Checks the availability of backend servers before routing requests.
- **Concurrency Safe:** Ensures thread-safe operations when handling multiple requests.
- **Error Handling:** Gracefully handles errors during proxying and server communication.
- **Extensible:** Easily add more load balancing algorithms or features as needed.

## Prerequisites

- **Go:** Ensure you have Go installed on your machine. You can download it from [Go's official website](https://golang.org/dl/).
- **Git:** For cloning the repository. Download from [Git's official website](https://git-scm.com/downloads).