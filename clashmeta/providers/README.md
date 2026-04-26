# Rule Providers

Individual rule files for Clash Meta rule-providers format.

## Usage

```yaml
rule-providers:
  Apple:
    type: http
    behavior: domain
    url: "https://raw.githubusercontent.com/ipevel/karing-ruleset/main/providers/Apple.yaml"
    path: ./providers/Apple.yaml
    interval: 86400
```

## Files

| File | Description | Rules |
|------|-------------|-------|
| Apple.yaml | Apple services | 29 |
| BanAD.yaml | Block ads | 6458 |
| BanADCompany.yaml | Block ad companies | 131 |
| Bing.yaml | Microsoft Bing | 3 |
| ChinaDomain.yaml | China domains DIRECT | 635 |
| ChinaMedia.yaml | Bilibili, video | 37 |
| Claude.yaml | Claude AI | 2 |
| Game.yaml | Gaming platforms | 7 |
| Gemini.yaml | Google Gemini | 38 |
| GitHub.yaml | GitHub | 6 |
| Google.yaml | Google services | 1113 |
| GoogleFCM.yaml | Google FCM | 12 |
| GooglePlay.yaml | Google Play | 37 |
| Instagram.yaml | Instagram | 4 |
| Microsoft.yaml | Microsoft services | 79 |
| NetEaseMusic.yaml | NetEase Music | 37 |
| Netflix.yaml | Netflix | 33 |
| OneDrive.yaml | Microsoft OneDrive | 15 |
| OpenAI.yaml | OpenAI / ChatGPT | 17 |
| ProxyGFWlist.yaml | GFW proxy list | 6985 |
| ProxyMedia.yaml | YouTube/TikTok/IG | 368 |
| Telegram.yaml | Telegram | 13 |
| TikTok.yaml | TikTok | 10 |
