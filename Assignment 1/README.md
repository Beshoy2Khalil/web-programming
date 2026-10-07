# Web Programming Assignment

**Student:** Beshoy Khalil Hanna  
**Student ID:** 250101496  
**Course:** Web Programming  
**Date:** 27/9/2026

## 1. Internet and the World Wide Web

People often use “the Internet” and “the Web” as if they mean the same thing, but they are not exactly the same. The Internet is the worldwide system that connects computers and other devices. It includes the cables, routers, wireless links, and rules that let information move between networks. It also supports services besides websites, such as email, online games, and file sharing.

The World Wide Web, usually called the Web, is one service that uses the Internet. It is made up of websites and pages connected by links. When I type a website address, my browser sends a request using HTTP or HTTPS, and the website sends information back, often as HTML, images, or other files. So, the Internet is the connection system, while the Web is a way to publish and open linked information through that system.

A simple comparison is a road network and the cars that use it: the roads are like the Internet, and the Web is one kind of traffic on those roads. Email and file transfer are other kinds. This difference matters because losing access to one website does not mean the whole Internet is down. It also helps explain why some apps can work online without being websites. In short, the Web depends on the Internet, but the Internet is bigger than the Web.

**Word count: 222**

## 2. Web 3.0

Web 3.0 is a developing idea for the next web. Some people use the term for the Semantic Web, where data is easier for software to understand. Others use Web3 for blockchain services that let users own digital assets and interact without relying on one platform.

Web 2.0 is the web most of us use now. People post content and use interactive apps, but companies usually store the accounts and data on their own servers. In blockchain-based Web3, a blockchain keeps a shared record on many computers. Smart contracts are programs on that network that carry out rules when conditions are met. Decentralized apps, or dApps, use smart contracts and often let a person connect with a digital wallet.

These apps can make rules easier to inspect and reduce dependence on one company. But they have trade-offs: fees, slow transactions, wallet security, and difficult interfaces. A coding mistake in a smart contract can also be costly.

I think these tools may be useful for some services, such as shared records or digital ownership. I do not think every website needs a blockchain. Web3’s future will depend on making useful services simple, safe, and affordable for ordinary users.

**Word count: 202**

## 3. Network tab: three request examples

I used the simple JSONPlaceholder API and opened these three URLs directly in Edge. Each page displayed a JSON response. In DevTools, the **Network** tab records each page load as a `GET` request; select a row to check its status under **General** and its `Content-Type` under **Response Headers**.

| URL | Method | Status code | Content-Type |
|---|---|---:|---|
| `https://jsonplaceholder.typicode.com/posts/1` | GET | 200 | `application/json` |
| `https://jsonplaceholder.typicode.com/users/1` | GET | 200 | `application/json` |
| `https://jsonplaceholder.typicode.com/comments/1` | GET | 200 | `application/json` |

To repeat: press **F12**, choose **Network**, reload one of these URLs, and click its request. The response body is JSON, so the browser shows it as plain text rather than a formatted web page.

## Sources

- Internet Society, [About the Internet and How it Works](https://www.internetsociety.org/internet/)
- ethereum.org, [What is Web3?](https://ethereum.org/web3)
- ethereum.org, [Web2 vs Web3](https://ethereum.org/developers/docs/web2-vs-web3/)
- ethereum.org, [What are dapps?](https://ethereum.org/what-are-apps/)
- JSONPlaceholder, [Fake Online REST API](https://jsonplaceholder.typicode.com/)
