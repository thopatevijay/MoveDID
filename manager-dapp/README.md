# MoveDIDBooster UI

This is the **DID Activation Portal** for the MoveDIDBooster project, a customized interface that lets users create their MoveDID tied to their Twitter username. Forked from the official MoveDID UI ([did.rootmud.xyz](https://did.rootmud.xyz/)), this repo enhances the experience with pre-filled Twitter usernames, branded elements, and clear guidelines for the Movement Network community.

## Project Overview
The MoveDIDBooster UI is the on-chain counterpart to the MoveDIDBooster Twitter agent. When users arrive via a link from the agent (e.g., `https://movedidbooster.vercel.app/?description=@UserX`), they’re greeted with a personalized interface to create their decentralized identity (DID) on the Movement testnet. It’s simple, user-friendly, and powered by MoveDIDBooster’s community spirit.

## Workflow
1. **User Redirect**: Users land on the portal via a link from MoveDIDBooster, e.g., `https://movedidbooster.vercel.app/?description=@UserX`.
2. **Personalized Welcome**: Displays a message like "Welcome, @UserX! Let’s create your MoveDID."
3. **Pre-Filled Description**: The description field is automatically filled with the user’s Twitter username (e.g., `@UserX`).
4. **Guidelines**: Clear instructions guide the user:
   - "Step 1: Choose your DID type (Human, Organization, AI Agent, Smart Contract)."
   - "Step 2: Review your description (pre-filled with your Twitter username—edit if you’d like!)."
   - "Step 3: Connect your Movement wallet and sign the transaction."
5. **DID Creation**: Users select a DID type, confirm their description, connect their wallet, and sign to create their MoveDID.

## UI Features
- **Personalized Welcome**: Greets users with their Twitter username (e.g., “Welcome, @UserX!”).
- **Pre-Filled Description**: Automatically populates the description field with the username from the URL.
- **Guidelines**: Step-by-step instructions ensure a smooth DID creation process.

## Setup
1. **Clone the Repo**: `git clone https://github.com/thopatevijay/MoveDID.git`
2. **Install Dependencies**: `npm install`
4. **Run Locally**: `npm run dev`
5. **Deploy**: Deployed on Vercel at [https://movedidbooster.vercel.app/](https://movedidbooster.vercel.app/).

## Customization Details
- **Forked Base**: Built from the MoveDID UI codebase, customized for MoveDIDBooster.
- **URL Parsing**: Extracts `description` from the query string to pre-fill the description field.
- **Branding**: Added “Powered by MoveDIDBooster” text and styling to reflect the agent’s identity.
- **User Experience**: Simplified layout with Movement-themed visuals and clear guidance.

## Integration with MoveDIDBooster
- **Main Repo**: [MoveDIDBooster](https://github.com/thopatevijay/MoveDIDBooster)
- **Workflow Connection**: The UI receives users from the Twitter agent and completes the on-chain DID creation process, tying their Twitter username to their Movement identity.

## Future Enhancements
- **Twitter Sharing**: Add a post-creation prompt with a pre-written tweet (e.g., “Just created my DID with @MoveDIDBooster—#mAInia”).
- **Dynamic Hype**: Display a personalized message based on DID type (e.g., “You’re a Human Movement star, @UserX!”).
- **Streamlined Signing**: Integrate wallet deep links for faster transaction signing.

Built with ❤️ for the Movement mAInia Hackathon, Feb 2025.