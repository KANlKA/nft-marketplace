# 🚀 Artium-NFTMarketplace

A modern, full-stack NFT marketplace powered by Next.js, Ethers.js, and the best of the Web3 ecosystem.

![image](https://github.com/user-attachments/assets/eaf809d6-e350-4e50-97e3-7106f235b435)

---

## 🚩 Features

### **Home Page (List All NFTs)**
- Browse all NFTs in a responsive layout
- Display NFT metadata: name, image, price, owner, and status

### **Wallet Authentication**
- Register/Login using Web3 Wallets via RainbowKit integration
- Supports MetaMask, Coinbase Wallet, WalletConnect, and more
- Session management with Next-Auth

### **NFT Creation**
- Mint new NFTs with image/file upload using IPFS (Pinata)
- Custom metadata fields: name, description, attributes
- ERC-721 standard compliance with preview before minting

### **NFT Management**
- Change NFT status (For Sale/Not for Sale)
- Update listing price with transaction confirmation
- Owner-only controls with wallet verification

### **NFT Purchases**
- Buy NFTs directly with your crypto wallet
- Integrated with Ethers.js and Wagmi for secure transactions

---

## 💻 Tech Stack

### **Core Framework**
- [Next.js (App Router)](https://nextjs.org/) – Full-stack framework

### **Blockchain Integration**
- [Ethers.js](https://docs.ethers.org/) – Smart contract interactions
- [Wagmi](https://wagmi.sh/) & [Viem](https://viem.sh/) – React hooks for Ethereum
- [RainbowKit](https://rainbowkit.com/) – Wallet connection UI

### **Backend & Database**
- [Prisma](https://www.prisma.io/) – ORM for database management
- [PostgreSQL](https://www.postgresql.org/) – Relational database (recommended)

### **Web3 Storage**
- [Pinata/IPFS](https://www.pinata.cloud/) – NFT metadata and file storage

### **UI & Styling**
- [shadcn/ui](https://ui.shadcn.com/) – Accessible UI components
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first styling

### **State & Data**
- [TanStack React Query](https://tanstack.com/query/latest) – Server state management
- [Zustand](https://zustand-demo.pmnd.rs/) – Client state management

### **Authentication**
- [Next-Auth](https://next-auth.js.org/) – Authentication framework
- Web3 wallet-based sessions

---

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rezakurniawan88/Flexi-NFTMarketplace.git
   cd Flexi-NFTMarketplace
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment configuration:**
   ```bash
   cp .env.example .env
   ```
   - Setup your environment variables in `.env`.

   **You must have:**
   - [Supabase](https://supabase.com/) database
   - [Pinata](https://www.pinata.cloud/) account
   - [Infura](https://infura.io/) account

4. **Database setup:**
   ```bash
   npx prisma migrate dev
   ```

5. **Run the development server:**
   ```bash
   npm run dev
   ```

6. **Open the app:**
   - Visit [http://localhost:3000](http://localhost:3000) in your browser to see the application.

---

## 📄 License

MIT

---

## 🙏 Acknowledgements

- Thanks to the creators and maintainers of all open-source packages used in this project!
