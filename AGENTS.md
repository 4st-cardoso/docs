# Documentation project instructions

## About this project

- This is the **4SeletPay** documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter located under `pages/`
- Configuration lives in `docs.json`
- OpenAPI spec for API endpoints lives in `openapi.yaml`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "4SeletPay" (capitalized) when referring to the company/product
- Use "4seletpay.com.br" for domain references
- Use "dashboard" for the web application at app.4seletpay.com.br
- Use "Dev mode" (not "sandbox" or "test mode") for the development environment
- Use "cobrança" for charges/billings
- Use "checkout" for the payment page
- Use "checkout transparente" for the transparent PIX checkout
- Use "chave de API" for API key

## Style preferences

- Write in Brazilian Portuguese (pt-BR)
- Use active voice and second person ("você")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Values in centavos (R$ 10,00 = 1000 centavos)

## Content boundaries

- Do not reference AbacatePay or any competitor
- Do not document internal admin features
- API base URL is always `https://app.4seletpay.com.br/api/v1`
- Dashboard URL is always `https://app.4seletpay.com.br`
- Support email is always `suporte@4selet.com.br`
- API v2 is under development — only reference it in the v2 coming-soon page
