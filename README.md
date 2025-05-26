# 🌍 DeCleanup Network – Empowering Cleanups. Tokenizing Impact.

## 🧭 Mission
We mobilize people worldwide to take meaningful environmental action by transforming cleanups into measurable, onchain environmental commodities - called Impact Products. Through transparent verification, community participation, and scalable incentive models, we drive real-world impact that bridges local actions with global significance.

---

## 🔗 What is DeCleanup Network?
DeCleanup Network is a global system for coordinating environmental cleanups and turning them into long-lasting digital impact. It connects individuals, grassroots groups, and partner organizations into a shared ecosystem, where every cleanup becomes part of a broader effort to regenerate the planet. By converting actions into onchain dynamic Impact Products, we enable recognition, traceability, and participation across regions and communities.
Additionally, users are being rewarded with $DCU - an in-app currency that will be redeemable for a token post-TGE. 
DeCleanup Impact Products will be later integrated to impact marketplace - [Regen Bazaar](https://regenbazaar.com), allowing participants to earn additional rewards for staking them. 

---

## ⚠️ The Problem & Our Solution

### The Challenges
- Lack of Incentives for Cleanup Action
- Limited Recognition and Quantification of Personal Impact
- Weak Global Coordination

### Our Solution
- Tokenizing Impact into Impact Products: we turn each cleanup into a dynamic onchain Impact Product - a visible, growing asset tied to real-world action. This creates lasting value and recognition beyond the moment of cleanup.
- Scalable Personal Recognition System: participants earn visibility and status through a system designed to reflect their actual environmental contributions - unlocking new levels, metrics, and future benefits based on their actions.
- Global Network of Coordinated Action: through our ambassador program, partner communities, and decentralized tech, we connect local cleanup efforts into one shared ecosystem - aligned, visible, and scalable across borders.
---

## 🛠️ How It Works

### Clean Up, Snap, Earn (3-Step Process)
1. **Clean Up** – Find or organize a cleanup in your local area.  
2. **Snap** – Capture before-and-after photos with geotags and timestamps.  
3. **Earn** – Submit via the dApp, get verified, receive DeCleanup Impact Products, and accumulate $DCU rewards.

---

## ✅ Existing Use Cases (V1 Campaigns)

### 🇯🇵 HEM Japan
HEM Japan was DeCleanup’s first active community partner. Led by Yuichi Hosomo (the first user to complete all Impact Product levels), they’ve demonstrated the power of Web3 for real-world environmental action.  
- **2024 Impact**: 12 active users, 9 cleanup events registered.

### 🇳🇬 Pesathon (Nigeria) – UNNploggas Youth Campaign
Pesathon campaign brought together cleanup and environmental education in Nigerian schools and communities, they partnered with DeCleanup Network, submitting cleanups via [dApp V1](https://decleanup.net). We also provided additional sponsorship for the participants in $USDGLO, which then were sent to the most active participants via [Atlantis Impact Miner](https://www.atlantisp2p.com/).   
- **2024 Impact**: 9 users, 4 verified events

---

## 🧩 Key Features in DeCleanup dApp (v2.1)

- **Proof of Impact Verification** – Timestamps, geotags, and image analysis ensure authenticity.  
- **Impact Product System** – Each verified cleanup earns you a collectible and levelable digital item (currently 10 levels).  
- **$DCU Accumulation** – Users earn $DCU within the system, which can be claimed as real tokens after TGE.  
- **Leaderboard & Rankings** – Compete, track progress, and gain recognition.  
- **Referral Rewards** – Invite friends to clean and earn bonus $DCU after successful verifications.  
- **Anti-Fraud by Design** – Verifications will evolve from team-based to decentralized, staking-enabled community validation.

---

## 🛣️ Roadmap – Building a Scalable, Verifiable Cleanup Ecosystem

### 🔄 Current Development: DeCleanup dApp V2.1
Version 2.1 lays the technical and experiential groundwork for DeCleanup’s long-term ecosystem. It introduces the core mechanics that bring environmental action on-chain while setting up for EVM compatibility and eventual decentralization.

### 🔑 Key Features of V2.1

#### 🧾 Proof of Impact System
A secure and transparent flow that verifies real-world cleanup efforts using visual and geolocation data.

- **Required Submission**:  
  - Before & after photos of the cleaned location.  
  - Geotagged and timestamped image files (JPEG, JPG, HEIC, max 10MB per image).  
  - Optional consent, allowing us to use images provided on our socials.

- **Team-Based Verification Flow**:  
  - Submissions are manually reviewed by the DeCleanup team.  
  - Must show clear before/after difference, consistent framing, and real-world metadata.  
  - AI-generated or manipulated images, or any unverifiable submissions, are rejected.  
  - Review time: 2–12 hours depending on volume.

- **Post-Verification Actions**:  
  - Once approved, users receive access to “Claim Next Level.”  
  - Claiming generates a DeCleanup Impact Product (gas fees apply).

#### 🧩 DeCleanup Impact Products
These are soulbound dynamic NFTs that represent tokenized environmental contributions.  
- Non-transferable, tied to the wallet of the person who cleaned up.  
- Represent Real World Impact (RWI) and evolve based on verified activity.  
- Automatically update onchain metadata: level progression, streaks, and total Impact Value.  
- Serve as future gateways to additional utility (e.g., staking on Regen Bazaar for APY in native token).

#### 💰 $DCU Accumulation System
Users earn $DCU (initially non-tradable system points) for every verified cleanup.  
- Bonus rewards for activity streaks and verified referral actions.  
- $DCU can be redeemed into actual tokens post-TGE.

---

## 🧭 Upcoming Roadmap

### 🔜 V2.2
- $DCU token launch: utility first.
- Community validation for Proof of Impact: users can become verifiers by staking and locking their $DCU.
- Impact Circles: collaborative cleanup campaigns where multiple users contribute to a shared environmental impact initiative.
- Multichain expansion: multiple EVM-compatible chains, plus Stellar.
- Start of Regen Bazaar integration - users will be able to stake their DeCleanup Impact Products at Regen Bazaar to earn $REBAZ tokens, introducing DeFi-powered incentives for impact-based staking. 

## Overview

The **DeCleanup dApp V2.2** focuses on **Impact Circles** – collaborative, time-bound, and location-based cleanup campaigns. Users can **create** or **join** campaigns through the platform. Each Impact Circle can include a reward pool and concludes with a **campaign NFT** minted upon completion.

---

## Functional Structure

### Entry Points (Dashboard Buttons)

- **Create Impact Circle**  
  → For users who want to lead a cleanup campaign.

- **Join Impact Circle**  
  → For users who want to participate in existing campaigns via list or map.

- **My Impact Circles**  
  → View and manage campaigns created by the logged-in user.

---

## 1. Create Impact Circle (User A - Campaign Creator)

### UI Flow

1. **Page Header**
   - Title: `Create Impact Circle`
   - Subheading: _Lead collaborative cleanups and get extra bonuses_

2. **Form Fields**
   - Campaign Name (string)
   - Description (text)
   - Location (string)
   - Start & End Date (date)
   - Participant Limit (integer)
   - Community Reward Pool (integer)
   - Contact Info (email, Telegram, etc.)
   - Upload Image (badge representation)

3. **On Submission**
   - Trigger smart contract deployment:
     - Logs metadata
     - Stores image hash (e.g. IPFS CID)
     - Collects deployment fee
   - Success UI:
     - “Congratulations! You’ve created your Impact Circle campaign.”
     - “You’ll receive additional DCU upon verification and minting.”

4. **Social Sharing Prompt**
   - Button: `Share on X`
   - Pre-filled message:
     > “I’ve just created my cleanup campaign on https://app.decleanup.net/linktocampaign  
     > Join me on [DATE] at [LOCATION].  
     > Let’s tokenize the real-world impact of cleanups by simply submitting our results!”

---

## UIC System (Unique Impact Code)

### What is UIC?

A short, auto-generated **8-character alphanumeric** code (e.g., `DHY157B2`) that uniquely identifies a campaign.

### Key Functions

1. **Participant Check-In**
   - Scannable QR with UIC logs real-time presence.

2. **Data Linking**
   - Associates PoI submissions to correct campaign.

3. **POAP & NFT Gating**
   - Only verified attendees can mint post-campaign rewards.

4. **Sharing & Discoverability**
   - UIC in URLs: `app.decleanup.net/circle/DHY157B2`

### Technical Notes

- Generated at contract deployment
- Stored on-chain in campaign metadata
- Embedded in:
  - QR code
  - Campaign page
  - Dashboard

---

## Campaign Page

- **URL**: `/impact-circle/:id`
- **Editable Fields**: Description, Dates, Image, Reward Pool
- **Features**:
  - QR Code for check-in
  - POAP-like NFT minting:
    - Available 1 day post-campaign
    - Requires participant check-in + PoI
  - Dashboard access via “My Impact Circles”

---

## 2. Join Impact Circle (User B - Participant)

### UI Flow

1. **Page Header**
   - Title: `Join Impact Circle`
   - Subheading: _Find cleanup near you_
   - Display:
     - Active campaigns (list or map)
     - Search by location
     - QR scanner interface

2. **Campaign Preview Card**
   - Name, Organizer, Description, Location, Dates
   - Participants limit
   - Community reward pool

3. **Interaction Options**
   - Show on Map
   - Set Reminder
   - Contact Organizer

4. **Back Button**
   - Returns to campaign search

---

## Event Check-In Flow

### Step 1: UIC & QR Code (Creator Side)

- Generated on campaign creation
- Displayed at cleanup site
- Counts as **referral** → extra DCU for each signer

### Step 2: Scan QR (Participant)

- QR opens campaign check-in flow
- Prompts wallet connection if not logged in
- Logs:
  - `userAddress`
  - `UIC`
  - `timestamp`
  - (optional) `geolocation`

> **Confirmation Message**:  
> _“Thank you for joining Impact Circle Central Moscow. Your additional rewards will be distributed upon your proof submission and claim of the next level of DeCleanup Impact Product.”_

- Button: `TOKENIZE IMPACT` → leads to PoI submission

### Step 3: Proof of Impact (PoI)

- Valid for 24 hours post-check-in
- Links PoI to the correct UIC
- Marks the participant as:
  - Eligible for rewards
  - Counted in campaign stats

## Rewards Logic

| Role                          | Condition                                                             | Reward                                                                                                 |
|-------------------------------|----------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **Impact Circle Participant** | Verified PoI submission marked with UIC                              | 10 DCU + 1 Impact Value + claimed DeCleanup Impact Product each level + 20 bonus DCU                  |
| **Impact Circle Leader**      | Campaign leadership                                                  | 10 DCU + 1 Impact Value + claimed DeCleanup Impact Product each level + 50 bonus DCU                  |
| **Referral (QR Scans)**       | Referee must sign in and submit proof of cleanup                     | 2 DCU to the leader per valid sign-in, verified submission, and claim of DeCleanup Impact Product     |
---

## Smart Contract Interactions

### 1. Campaign Deployment

- Triggered by form submission
- Stores metadata:
  - Name, description, dates, location, limits, reward pool, contact, imageCID
- Auto-generates and stores UIC
- Requires a gas/platform fee

### 2. Reward Pool Creation (Optional)

- User deposits tokens
- Locked until campaign ends
- Distributed post-verification

### 3. Participant Check-In

- Wallet + location verification
- Logs address, time, and UIC
- Prevents duplicates and spoofs

### 4. Proof of Impact Submission

- Submitted with photo/video
- Linked to verified check-in
- Enables:
  - DCU rewards
  - NFT minting
  - Product level upgrades

### 5. Campaign Completion & Minting

- Creator can mint campaign **Impact Product**
- Verified participants unlock **POAP NFT**
- Leader receives additional rewards

---

## Dependencies & Assets

### Frontend

- TypeScript-based UI
- Pages:
  - Create / Join Impact Circle
  - My Campaigns
  - Individual Campaign Page
  - PoI Submission
  - QR Scanner
- Wallet Integration (WalletConnect, MetaMask)

### Backend

- Campaign registry (UIC metadata cache)
- IPFS for image storage
- Check-in logs with geolocation
- PoI submission tracking
- PoI verification flow (centralized or delegated)
- X (Twitter) sharing integration

### Smart Contracts

- `ImpactCircleFactory` – campaign creator
- `ImpactCircleInstance` – per-campaign logic
- `RewardPoolManager` – optional reward pool
- `POAPManager` – NFT/POAP distribution
- DCU allocation logic linked to validated actions
---
### 🔭 V2.3 – Cleanup Campaigns, Teams & Impact Circles
- Multi-chain POAPs (Proof of Attendance Protocol) - non-transferable ERC-721 NFTs, issued to users who participate in verified Impact Circles across different blockchains, they act as verifiable, on-chain proof of environmental contribution and may hold future staking, reputation, or governance utilities, offering enhanced recognition for sustained contributions.  
- Expanded reward system - introduction of additional tiers of Impact Product to recognize long-term commitment and larger contributions.  
- Impact metrics expansion - detailed tracking and differentiation of Impact Value, based on various environmental factors (e.g., type of waste removed, cleanup location significance, CO2 offset calculations). 
- Governance mechanics - users who staked $DCU will be able to vote on key DeCleanup Network decisions, such as adjusting staking APY and verification rewards, deciding on grant funding for large-scale cleanup campaigns, proposing and implementing new reward mechanism or token utilities. 
- Ambassador program & incentives - selected community leaders and contributors can earn extra $DCU rewards for promoting DeCleanup, onboarding new participants, and organizing cleanup events. 


### 🛒 V3.0 – Redemption Layer (2026)
Bridge partnerships with external Web3 ecosystems for cross-campaign incentives.

### Additional Information
- Current version Figma design: [Link](https://www.figma.com/design/gcIv3YALbv8eFTJjXm3aUK/DCU-%E2%80%94-V2--Copy-?node-id=2654-7146&t=pBK1krNmTZHkliO1-0)
- Full dApp prototype: [Link](https://www.canva.com/design/DAGa70P3H9I/g2rqJn8-hsOxOeyy8yqE4g/view?utm_content=DAGa70P3H9I&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h7ae241b0bb)
- Impact Reporting: [Link](https://gap.karmahq.xyz/project/decentralized-cleanup-network-decleanup-network)

