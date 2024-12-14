# KickOfframe


## Getting Started

To use the Farcaster Transaction Frame, you'll need to clone this repository, install dependencies, set up environment variables, and deploy the application. Below are the steps to follow:

### Cloning the Repository

To get started, clone the repository to your local machine:
```
git clone https:
```
```
cd farcaster-transaction-frame-youtube
```


### Installing Dependencies

This application requires several dependencies to function, including thirdweb and Coinbase's OnchainKit. Install them using npm or yarn:

```
npm install
```
or
```
yarn install
```



### Deploying with Vercel

To deploy the Farcaster Transaction Frame, we recommend using Vercel. If you haven't already, sign up for a Vercel account and install the Vercel CLI:

```
npm i -g vercel
```

Then, within your project directory, run:
```
vercel
```


Follow the prompts to set up and deploy your project.

### Setting Environment Variables

Vercel requires specific environment variables for the Farcaster Transaction Frame to operate correctly. These include:

- `TW_SECRET_KEY`: thirdweb API secret key.
- `CONTRACT_ADDRESS`: The contract address for the NFT.
- `NEXT_PUBLIC_HOST_URL`: The URL of your deployed application.
- `NEYMAR_API_KEY` (optional): Your Neymar API key, if you choose to use it.

To add these variables in Vercel, navigate to your project settings on the Vercel dashboard, find the Environment Variables section, and add the variables listed above.

### Final Steps

Once your environment variables are set, your application is ready to go! 

You can test you Frame using [Farcaster's Frame Validator](https://warpcast.com/~/developers/frames)

