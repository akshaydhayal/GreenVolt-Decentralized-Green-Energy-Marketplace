# GreenVolt: Decentralized Green Energy Marketplace

Live Project Link: [https://greenvolt-energy.vercel.app/](https://greenvolt-energy.vercel.app/)

## Description
**GreenVolt** is a decentralized energy marketplace built on the Solana blockchain, designed to simplify how energy is created, distributed, and consumed — with a strong focus on sustainability. It enables energy producers to list and sell green or non-green energy, while charging station owners purchase this energy and offer electric vehicle (EV) charging services to consumers.

Users can choose to charge their EVs with green energy (like solar or wind) and track transactions in real-time thanks to smart contracts deployed using Solana and Anchor. The platform promotes renewable energy adoption by differentiating between **green and non-green source**s and enables Renewable Energy Credit (REC) tracking for green energy producers.

## Features

- **Energy Producer Creation:**:Producers can register as energy providers by defining the total energy available and setting rates for green or non-green energy.
- **Charging Point Setup:**: Charging station owners can create charging points, specifying different rates for green and non-green energy.
- **Chargin Points buys From Producers**: The Charging Points buy from Producers(they buy from Green Producers if they want green energy or vice versa)
- **EV Charging thorugh Charging Points:**:  Users can charge their EVs at charging stations using the purchased energy.They can opt for if they want to use Green or Non Green Energy. The system checks for sufficient energy availability (green or non-green) before proceeding with the charging process.

## Website Demo

![Mission Dashboard](https://github.com/akshaydhayal/UEI-Green-Energy-Check/blob/main/GreenVolt1.png)

*Figure 1: Create Energy Producers and Charginf Points to interact with later*

![Mission Details](https://github.com/akshaydhayal/UEI-Green-Energy-Check/blob/main/Green-Energy-Management%20(1).png)

*Figure 2: Energy Transactions Section(b/w Producer-Charging Point and b/w Charging Point-Consumer)*
![Mission Details](https://github.com/akshaydhayal/UEI-Green-Energy-Check/blob/main/Green-Energy-Management%20(3).png)

*Figure 3: All Available Producers and Charging Points created*



## Video Demo:

[https://www.loom.com/share/598e67c7c9374cda816deeb82681077e?sid=d5d2aaa3-9e3f-44e6-a62c-c51f673daffb](https://www.loom.com/share/598e67c7c9374cda816deeb82681077e?sid=d5d2aaa3-9e3f-44e6-a62c-c51f673daffb)


## Technologies Used

- **Frontend**: Next.js, React, Recoil, Tailwind CSS, Lucide Icons
- **Contract/Ledger**: Solana Smart Contract with Anchor

  ## Assumption made
- **Green Producer**: A Producer can either be Green or Non Green Energy Producer.(So that It is easy to implement REC.A green Energy producer can transfer REC to Charging Points but Non Green Producers can't.) 
