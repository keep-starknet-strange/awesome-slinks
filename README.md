# Awesome Slinks 🌟

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Welcome to the Awesome Slinks repository! This is a community-curated list of cool Slinks (Starknet Links) on Starknet.

## What are Slinks?

Slinks are the Starknet version of Solana Blinks (Blockchain Links). The concept is simple: use a Starknet application directly from Twitter as an embed card in a tweet.

Under the hood, Slinks are just [Twitter Cards](https://developer.x.com/en/docs/twitter-for-websites/cards/overview/abouts-cards).

## Purpose of this Repository

This repository serves two main purposes:

1. To showcase a collection of cool Slinks on Starknet
2. To demonstrate how to easily implement a Slink for any Starknet Application

## Security Disclaimer ⚠️

**Important:** Interacting with any web3 application carries inherent risks. The inclusion of an application in this list does not guarantee its security or imply that it is free from vulnerabilities. Always exercise caution, do your own research, and understand the risks before interacting with any decentralized application.

## Awesome Slinks List

Here's a list of some cool Slinks on Starknet:

- **Avnu**

  - Live Slink Tweet: [https://x.com/avnu_fi/status/1816442462069502441](https://x.com/avnu_fi/status/1816442462069502441)
  - Official Application Website: [app.avnu.fi](https://app.avnu.fi)

- **Ekubo**

  - Live Slink Tweet: [https://x.com/EkuboProtocol/status/1816154347547312261](https://x.com/EkuboProtocol/status/1816154347547312261)
  - Official Application Website: [https://app.ekubo.org/](https://app.ekubo.org/)

- **Fibrous**

  - Live Slink Tweet: [https://x.com/FibrousFinance/status/1816451301942657529](https://x.com/FibrousFinance/status/1816451301942657529)
  - Official Application Website: [fibrous.finance](https://app.fibrous.finance/)

- **Flex**

  - Live Slink Tweet: [https://x.com/Flex_strk/status/1816460243616035061](https://x.com/Flex_strk/status/1816460243616035061)
  - Official Application Website: [hyperflex.market](https://hyperflex.market/)

- **STRKFarm.xyz**

  - Live Slink Tweet: [https://x.com/strkfarm/status/1816536692813365417](https://x.com/strkfarm/status/1816536692813365417)
  - Official Application Website: [strkfarm.xyz](https://strkfarm.xyz/)

- **Raize Club**

  - Live Slink Tweet: [https://x.com/RaizeClub/status/1816493967099437119](https://x.com/RaizeClub/status/1816493967099437119)
  - Official Application Website: [raize.club](https://raize.club/)

- **Jediswap**
  - Live Slink Tweet: [https://x.com/JediSwap/status/1816693579055825327](https://x.com/JediSwap/status/1816693579055825327)
  - Official Application Website: [app.jediswap.xyz](https://app.jediswap.xyz/)

## Contributing

We welcome contributions from the community! If you know of a cool Slink that's not on the list, feel free to submit a pull request.

## How to Implement a Slink

### Implement Twitter Card Metadata

Add the following meta tags to your main app's HTML `<head>`:

```html
<meta name="twitter:card" content="player" />
<meta name="twitter:site" content="@YourTwitterHandle" />
<meta name="twitter:title" content="Your App Title" />
<meta name="twitter:description" content="Brief description of your app" />
<meta
  name="twitter:player"
  content="https://your-domain.com/twitter-card.html"
/>
<meta name="twitter:player:width" content="360" />
<meta name="twitter:player:height" content="560" />
<meta
  name="twitter:image"
  content="https://your-domain.com/preview-image.png"
/>
```

### Additional Considerations

### Implement Open Graph Meta Tags

To improve sharing across various social media platforms, add Open Graph meta tags to your HTML:

```html
<meta property="og:url" content="YOUR_PAGE_URL" />
<meta property="og:title" content="Your Title Here" />
<meta property="og:description" content="Your description here" />
<meta property="og:image" content="URL_TO_YOUR_IMAGE" />
```

## FAQ / Troubleshooting

### Q: Why don't Slinks work for me? I only see a link that redirects me to the website.

A: If Slinks aren't displaying properly and you're only seeing a link that redirects to the website, it's likely due to cookie settings on X. To resolve this:

1. Ensure you're accepting all cookies from X.
2. If you're using Chrome or Arc browser, check your cookie settings for X.
3. Try clearing your browser cache and cookies, then reload the page.

Remember, Slinks rely on X's ability to load and display Twitter Cards. Without the proper cookie permissions, X may not be able to render the embedded content correctly.

### Q: How do I accept all cookies from X?

A: To accept all cookies from X:

1. Go to X.com
2. Look for a cookie consent banner or popup
3. Choose "Accept All Cookies" or a similar option
4. If you don't see a banner, check your browser settings or X account settings for cookie preferences

After accepting cookies, try viewing the Slink again. It should now display properly as an embedded card in the tweet.

If you're still experiencing issues after following these steps, please ensure your browser is up to date and try disabling any ad-blockers or privacy extensions that might interfere with X's functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
