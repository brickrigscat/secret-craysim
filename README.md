# Crayfish Simulator 2 — Secret Beta Portal 🦞

The secret beta-code redemption website for **Crayfish Simulator 2**, by **Whyacat**.

**Website:** https://secret-craysim.vercel.app

## How it is designed to work
1. Players reach the Day 100 reward in Crayfish Simulator 1.
2. The game requests a temporary code through the server API.
3. Players enter that code on this website.
4. The server checks whether the code is valid and still within its **60-second** lifetime.
5. When beta access is available, an eligible player can unlock it.

> **Development status:** The website is a starter page. Code redemption remains disabled until the backend has reliable Day 100 verification, persistent one-use codes, and beta-access storage.

## Important
Codes are verified on the server. This website must not contain private API secrets.

## Related websites
- [Crayfish Simulator](https://craysim.vercel.app)
- [CraySim beta API](https://api-client-secret-craysime.vercel.app)

Created by **Whyacat**.
