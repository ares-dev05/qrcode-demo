## 🔳 Quirky

Make really cool QR codes with AI. Try it out at [quirky.replicate.dev](https://quirky.replicate.dev).


## How it works

This app is powered by:

🚀 [Replicate](https://replicate.com), a platform for running machine learning models in the cloud.

🖼️ [Multi-ControlNet](https://replicate.com/anotherjesse/multi-control), an open-source machine learning model that layers controlnets to do cool things with your QR code.

🔳 [react-qr-code](https://www.npmjs.com/package/react-qr-code) for generating QR codes.

## Development

Install dependencies:

```console
npm install
```

Add your [Replicate API token](https://replicate.com/account#token) to `.env.local`:

```
REPLICATE_API_TOKEN=<your-token-here>
```

Run the development server:

```console
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser. That's it!
