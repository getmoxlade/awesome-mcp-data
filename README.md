# Awesome MCP Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> MCP servers that bring your agent data it does not already have — 216 of them, each checked.

Most MCP lists index everything: action tools, connectors to your own database, and data
sources, all in one pile. This list keeps only the third kind, and verifies it.

**A data source gives your agent facts it cannot otherwise reach** — market prices, court
rulings, published papers, satellite passes, who is behind a listing. **A connector is
plumbing to data you already own** — your PostgreSQL, your Snowflake, your Weaviate. Both are
useful; only one answers "where do I get data about X". Connectors are deliberately excluded
here.

**Why a smaller list.** The largest MCP directory carries 3,937 entries. Checking every entry
in its data categories on 2026-09-15 found **46 dead links**, **47 repositories with zero
stars** (61% under five), at least one server listed twice, and 133 database *connectors*
filed as data sources — while the four most-used commercial data servers were absent from
those categories entirely: Apify (7,131★), Exa (5,002★), Bright Data (2,641★) and Tavily
(2,380★). That list is a comprehensive index. This one is a filtered one. Use whichever you need.

**The bar for inclusion:** the server supplies data you do not already own, its repository is
alive (not archived, pushed within 180 days), and it is either maintained with real traction
or published by the data provider itself. Every link resolved when added.

## Contents

- [Web & Search](#web--search)
- [Finance & Markets](#finance--markets)
- [Science & Research](#science--research)
- [Life Sciences & Health](#life-sciences--health)
- [Government & Open Data](#government--open-data)
- [Legal & Regulatory](#legal--regulatory)
- [Geospatial & Location](#geospatial--location)
- [Travel & Transport](#travel--transport)
- [Social & Community](#social--community)
- [Sports](#sports)
- [Culture & Media](#culture--media)
- [Real Estate](#real-estate)
- [Environment & Climate](#environment--climate)
- [Space & Aerospace](#space--aerospace)
- [People & Work](#people--work)
- [Legend](#legend)

## Web & Search

- [firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl server to search the web and scrape, crawl, map, and extract structured data from any site for LLMs. Handles JS-rendered pages,… 🏅
- [apify-mcp-server](https://github.com/apify/apify-mcp-server) - Run 6,000+ Apify Actors as agent tools to extract data from any site; metered per result. 🏅
- [exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) - Neural web search and crawling built for LLMs; paid API key, metered per search. 🏅
- [arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) - Search ArXiv research papers.
- [brightdata-mcp](https://github.com/brightdata/brightdata-mcp) - Web access at scale with unblocking, plus court-tested public datasets; metered. 🏅
- [tavily-mcp](https://github.com/tavily-ai/tavily-mcp) - Real-time search, extract, map and crawl built for agents; free tier then metered. 🏅
- [open-webSearch](https://github.com/Aas-ee/open-webSearch) - Web search using free multi-engine search (NO API KEYS REQUIRED) — Supports Bing, Baidu, DuckDuckGo, Brave, Exa, and CSDN.
- [duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) - Web search using DuckDuckGo.
- [brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) - Web search capabilities using Brave's Search API.
- [crw](https://github.com/us/crw) - FastCRW — open-source (AGPL-3.0), self-hostable Rust web crawler & search API for AI agents. Tools: `scrape`, `crawl`, `map`, and SearXNG-backed… 🏅
- [perplexity-mcp](https://github.com/jsonallen/perplexity-mcp) - Web search via Perplexity with recency filtering; needs a Perplexity API key.
- [mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) - Local MCP server for searching 300,000+ foods, nutrition facts, and barcodes from the OpenNutrition database.
- [search1api-mcp](https://github.com/fatwang2/search1api-mcp) - Search via search1api (requires paid API key).
- [mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) - 🐍 ☁️ MCP to search and read medical / life sciences papers from PubMed.
- [serpapi-mcp](https://github.com/serpapi/serpapi-mcp) - SerpApi MCP Server for Google and other search engine results. Provides multi-engine search across Google, Bing, Yahoo, DuckDuckGo, YouTube, eBay,…
- [scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) - The Scrapeless Model Context Protocol service acts as an MCP server connector to the Google SERP API, enabling web search within the MCP ecosystem…
- [arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) - Get the LaTeX source of arXiv papers to handle mathematical content and equations.
- [servo-fetch](https://github.com/konippi/servo-fetch) - Chromium-free web content extraction in a single binary. Fetch, render, crawl, and screenshot powered by the Servo browser engine with a built-in…
- [mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) - "primitive" RAG-like web search model context protocol (MCP) server that runs locally. No APIs needed.
- [google-news-mcp-server](https://github.com/ChanMeng666/server-google-news) - Google News integration with automatic topic categorization, multi-language support, and comprehensive search capabilities including headlines,…
- [brave-search-mcp](https://github.com/mikechao/brave-search-mcp) - Web, Image, News, Video, and Local Point of Interest search capabilities using Brave's Search API.
- [agent-search-mcp](https://github.com/lennney/agent-search-mcp) - Free multi-engine MCP search server — 8 free engines (DDG, Sogou, Bing, Baidu, Wikipedia, Startpage, Yandex, Mojeek), waterfall progressive…
- [naver-search-mcp](https://github.com/isnow890/naver-search-mcp) - MCP server for Naver Search API integration, supporting blog, news, shopping search and DataLab analytics features.
- [reflex](https://github.com/reflex-search/reflex) - Local full-text code search for AI coding agents. Trigram-indexed, sub-100ms queries across large codebases, offline, 18 languages.
- [web-researcher-mcp](https://github.com/zoharbabin/web-researcher-mcp) - Production-grade MCP server for web search (Google, Brave, Serper, SearXNG, SearchAPI.io), content extraction (4-tier pipeline), academic/patent…
- [sifter](https://github.com/sifter-ai/sifter) - Structure any document, query it like a database. Open-source extraction engine that turns any document into typed, schema-defined records,…
- [mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) - Advanced search and retrieval for web crawler data. Supports WARC, wget, Katana, SiteOne, and InterroBot crawlers.
- [cn-scraper-mcp](https://github.com/goesByhc/cn-scraper-mcp) - MCP server that lets AI agents search and extract data from major Chinese internet platforms including Taobao, JD, Xiaohongshu, Zhihu, Weibo,…
- [baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) - MCP server that searches Baseline status using Web Platform API.
- [stocky](https://github.com/joelio/stocky) - An MCP server for searching and downloading royalty-free stock photography from Pexels and Unsplash. Features multi-provider search, rich…
- [searchpin](https://github.com/telly6/searchpin) - Free web search for AI agents with smart re-ranking. Multi-engine parallel search, zero API keys. Works natively within China's network, no…
- [nexus](https://github.com/adawalli/nexus) - AI-powered web search server using Perplexity Sonar models with source citations. Zero-install setup via NPX.
- [nyt](https://github.com/angheljf/nyt) - Search articles using the NYTimes API.
- [himalayas-mcp](https://github.com/Himalayas-App/himalayas-mcp) - Access tens of thousands of remote job listings and company information. This public MCP server provides real-time access to Himalayas' remote…
- [StitchAPI](https://github.com/rejifald/StitchAPI) - Semantic search over the StitchAPI documentation (the hosted docs MCP): `search_docs` returns the most relevant doc sections with deep links,…
- [search-mcp](https://github.com/parallel-web/search-mcp) - Highest Accuracy Web Search for AI.
- [free-web-search-ultimate](https://github.com/wd041216-bit/free-web-search-ultimate) - Zero-cost, privacy-first universal web search MCP server. Enforces a **Search-First** paradigm — instructs LLMs to retrieve real-time information…
- [mcp-claude-hackernews](https://github.com/imprvhub/mcp-claude-hackernews) - An integration that allows Claude Desktop to interact with Hacker News using the Model Context Protocol (MCP).
- [whw23/searxng-http-mcp](https://github.com/whw23/searxng_http_mcp) - Self-contained SearXNG MCP server in Docker. 200+ search engines, 30+ categories, multi-page fanout, autocomplete, and engine discovery. Dual…
- [heventure-search-mcp](https://github.com/HughesCuit/heventure-search-mcp) - Free MCP web search server with 5 engines (DuckDuckGo, Bing, Google SerpAPI, Tavily). No API key required. Auto rate limiting, 300s cache,…
- [mcp_pearch](https://github.com/Pearch-ai/mcp_pearch) - Best people search engine that reduces the time spent on talent discovery. 🏅
- [shopsavvy-mcp-server](https://github.com/shopsavvy/shopsavvy-mcp-server) - Complete product and pricing data solution for AI assistants. Search for products by barcode/ASIN/URL, access detailed product metadata, access… 🏅
- [scavio-mcp](https://github.com/scavio-ai/scavio-mcp) - Unified real-time search API for AI agents. Google, YouTube, Amazon, Walmart, Reddit, and TikTok through one endpoint. 21 tools for web search,…
- [gsc-mcp](https://github.com/mikusnuz/gsc-mcp) - MCP server for Google Search Console & Indexing API — 13 tools for search analytics, sitemaps, URL inspection, and batch indexing.
- [agent-web-search](https://github.com/JerryLiu369/agent-web-search) - Agent-native web search for AI agents: one provider-neutral `web_search` tool aggregating model-native grounding (ARK, Gemini, Grok, DeepSeek,…
- [argus](https://github.com/Khamel83/argus) - Multi-provider search broker with automatic fallback, RRF ranking, content extraction, and budget enforcement.
- [keenable-mcp](https://github.com/keenableai/keenable-mcp) - Live web search and clean-markdown page fetch over the Keenable web index. Two tools: `search_web_pages`, `fetch_page_content`. Keyless by default… 🏅
- [ocds-mcp](https://github.com/qune-tech/ocds-mcp) - German public procurement data (OCDS) — semantic search, tender matching with company profiles, and structured filtering.
- [talonic-mcp](https://github.com/talonicdev/talonic-mcp) - Schema-validated document extraction with searchable workspace memory. Extract structured fields from PDFs, scans, images, and forms; AI agents…
- [rephonic-mcp](https://github.com/getrephonic/rephonic-mcp) - Search 3M+ podcasts and 170M+ episodes, with listener estimates, audience demographics, contacts, transcripts, chart rankings, sponsors, reviews,… 🏅
- [muumuu-domain-mcp](https://github.com/pepabo/muumuu-domain-mcp) - Official remote MCP server for Muumuu Domain (GMO Pepabo). Search and register domains, manage owned domains and contracts, and configure DNS… 🏅
- [forge-mcp](https://github.com/VoxellInc/forge-mcp) - Official MCP server for Forge, Voxell's hosted text-embedding API. Generate vector embeddings (turbo 1024d, pro 2560d, ultra 4096d; Matryoshka… 🏅
- [pod-mcp](https://github.com/Marvy101/pod-mcp) - Search firsthand observations that agents recorded while doing real work — what actually happened with a product, API, service, or place, rather… 🏅
- [quanticdata-mcp-server](https://github.com/quantumproxies/quanticdata-mcp-server) - Web data for AI agents: scrape any page to clean Markdown, structured SERP search across three engines, site crawl and map, 74 ready-made… 🏅
- [mcp-server](https://github.com/ToolTrace-io/mcp-server) - Web page data for agents: scrape to Markdown, extract metadata, links and JSON-LD schema, audit on-page SEO, detect tech stacks, and validate XML… 🏅
- [quantumproxies-mcp](https://github.com/quantumproxies/quantumproxies-mcp) - Live web access through residential proxies: scrape any page to clean Markdown, structured SERP search on three engines, site map and crawl, and… 🏅
- [crawdar-mcp](https://github.com/eliottreich/crawdar-mcp) - Official hosted MCP server with an open-source stdio bridge for evidence-backed business discovery and lead-list research. Search by… 🏅
- [serpdive-mcp](https://github.com/serpdive/serpdive-mcp) - Web search that returns extracted, answer-ready page content (url, title, date, text) instead of links. A Tavily alternative: same speed, 20.2%… 🏅

## Finance & Markets

- [mcp_polygon)](https://github.com/polygon-io/mcp_polygon) - An MCP server that provides access to Polygon.io financial market data APIs for stocks, indices, forex, options, and more.
- [investor-agent](https://github.com/ferdousbhai/investor-agent) - Yahoo Finance integration to fetch stock market data including options recommendations.
- [flox-mcp](https://github.com/FLOX-Foundation/flox/tree/main/mcp) - MCP server for the FLOX trading systems framework. ~30 tools to run backtests, scaffold strategies, validate for lookahead bias, place orders,…
- [korea-stock-mcp](https://github.com/jjlabsio/korea-stock-mcp) - An MCP Server for Korean stock analysis using OPEN DART API and KRX API.
- [octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) - Octagon AI Agents to integrate private and public market data.
- [mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) - MCP server based on baostock, providing access and analysis capabilities for Chinese stock market data.
- [onchain-mcp](https://github.com/Bankless/onchain-mcp/) - Bankless Onchain API to interact with smart contracts, query transaction and token information.
- [mcp](https://github.com/twelvedata/mcp) - Interact with Twelve Data APIs to access real-time and historical financial market data for your AI agents.
- [heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) - Access specialized Web3 AI agents for Blockchain analysis, smart contract security auditing, token metrics evaluation, and on-chain interactions… 🏅
- [dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) - Coinpaprika's DexPaprika MCP server exposes high-performance DexPaprika API covering 20+ chains and 5M+ tokens with real time pricing, liquidity… 🏅
- [trayd-mcp](https://github.com/trayders/trayd-mcp) - Trade Robinhood through natural language. Portfolio analysis, real-time quotes, and order execution via Claude Code.
- [perp-cli](https://github.com/hypurrquant/perp-cli) - Multi-DEX perpetual futures trading MCP server for Pacifica (Solana), Hyperliquid (HyperEVM), and Lighter (Ethereum). 18 tools for market data,…
- [mcp-klever-vm](https://github.com/klever-io/mcp-klever-vm) - Klever Blockchain MCP server for smart contract development, on-chain data exploration, account and asset queries, transaction analysis, and… 🏅
- [mcp](https://github.com/tonnode/mcp) - Direct liteserver access to The Open Network (TON) over native ADNL: GRAM balances, account state, transaction history and contract get-methods.…
- [chart-library-mcp](https://github.com/grahammccain/chart-library-mcp) - Historical stock chart pattern intelligence for AI agents. 24M pre-computed embeddings across 15K stocks and 10 years of data. Search by…
- [hive-crypto-mcp](https://github.com/hive-intel/hive-crypto-mcp) - Hive Intelligence: Ultimate cryptocurrency MCP for AI assistants with unified access to crypto, DeFi, and Web3 analytics.
- [openregistry](https://github.com/sophymarine/openregistry) - Live official data from 27 national company registries (UK Companies House, France RNE, Germany Handelsregister, Korea OpenDART, Canada CBCA, 10… 🏅
- [polymarket-agent-mcp](https://github.com/demwick/polymarket-agent-mcp) - 49-tool Polymarket prediction market suite for AI agents. Direct trading, smart money flow detection, copy trading with auto-monitor, backtesting,…
- [mcp-fns-check](https://github.com/atomno-mcp/mcp-fns-check) - Russian counterparty due diligence — INN/OGRN lookup against EGRUL/EGRIP, bankruptcy registry (EFRSB), tax debts (Transparent Business), FSSP…
- [blockchain-mcp](https://github.com/tatumio/blockchain-mcp) - MCP server for Blockchain Data. It provides access to Tatum's Blockchain API across 130+ networks with tools including RPC Gateway and Blockchain…
- [mcp-server](https://github.com/finmap-org/mcp-server) - Finmap.org MCP server provides comprehensive historical data from the US, UK, Russian and Turkish stock exchanges. Access sectors, tickers,…
- [longbridge-mcp](https://github.com/longbridge/longbridge-mcp) - Official Longbridge brokerage MCP — 110 tools for US/HK real-time quotes, options, trading, fundamentals, analyst ratings, calendars, price… 🏅
- [xrpl-mcp-server](https://github.com/RomThpt/mcp-xrpl) - MCP server for the XRP Ledger that provides access to account information, transaction history, and network data. Allows querying ledger objects,…
- [Reddit-Options-Trader-ROT-](https://github.com/Mattbusel/Reddit-Options-Trader-ROT-) - The first financial intelligence MCP server. Live AI-scored trading signals from Reddit, SEC filings, FDA approvals, Congressional trades, and 15+…
- [Agent-skills](https://github.com/EmblemCompany/Agent-skills) - 200+ crypto tools for AI agents across 7 blockchains (Solana, Ethereum, Base, BSC, Polygon, Hedera, Bitcoin). Swaps, DeFi yield, conditional… 🏅
- [mcp-eastmoney](https://github.com/27dream/mcp-eastmoney) - China A-share stock market MCP server — real-time quotes, main capital flow ranking, sector fund flow, and historical K-lines via Eastmoney's free…
- [mcp-server](https://github.com/Frihet-io/frihet-mcp) - AI-native business management — invoices, expenses, clients, products, and quotes. 31 tools for Claude, Cursor, Windsurf, and Cline.
- [shareseer-mcp-server](https://github.com/shareseer/shareseer-mcp-server) - MCP to Access SEC filings, financials & insider trading data in real time using ShareSeer.
- [builders-sodax-mcp-server](https://github.com/gosodax/builders-sodax-mcp-server) - SODAX MCP server: live cross-chain DeFi API data and auto-updating SDK docs for 17+ networks. Query swaps, lending, solver volume, and intent…
- [trading212-mcp-server](https://github.com/KyuRish/trading212-mcp-server) - Trading 212 API integration with 28 tools for portfolio management, trading (market/limit/stop orders), pies, dividends, market data, and…
- [openapi](https://github.com/longportapp/openapi/tree/main/mcp) - 🐍 ☁️ - LongPort OpenAPI provides real-time stock market data, provides AI access analysis and trading capabilities through MCP.
- [bcb-br-mcp](https://github.com/SidneyBissoli/bcb-br-mcp) - Brazilian Central Bank (BCB) economic data — 18,000+ time series including Selic, IPCA, exchange rates, GDP, and 150+ curated indicators via the…
- [financekit-mcp](https://github.com/vdalhambra/financekit-mcp) - Financial market intelligence with 17 tools — stock quotes, technical analysis (RSI, MACD, Bollinger Bands, ADX, Stochastic), crypto prices via…
- [kite-mcp](https://github.com/aranjan/kite-mcp) - Trade Indian stocks on Zerodha Kite via natural conversation. 14 tools for holdings, orders, quotes, GTT triggers, and more with automated TOTP login.
- [liquidiction-mcp](https://github.com/Liquidiction/liquidiction-mcp) - Live Hyperliquid HIP-4 prediction market data. 10 tools for odds, orderbooks, candles, trades, and portfolio positions. First MCP server for…
- [mcp-binance-futures](https://github.com/muvon/mcp-binance-futures) - MCP server for Binance USDT-M Futures trading — exposes tools for market data, account state, order management, and position/margin control.
- [cnb](https://github.com/martinhavel/cz-agents-mcp) - Czech National Bank (ČNB) daily FX rates: fetch official CZK exchange rates, convert between currencies, fetch historical rates. Cached 10 min to…
- [dodo-agent-plugin](https://github.com/dodopayments/dodo-agent-plugin) - Official Dodo Payments MCP servers — `dodopayments-api` for live payments, subscriptions, customers, products, refunds, license keys, and… 🏅
- [indigo-mcp](https://github.com/IndigoProtocol/indigo-mcp) - MCP server for Indigo Protocol on Cardano — iAsset prices, CDP/loan analytics, stability pools, INDY staking, governance, and DEX data for LLM agents.
- [optionsahoy-mcp](https://github.com/AlvisoOculus/optionsahoy-mcp) - Multi-year equity-compensation optimization engine: returns the globally-optimal ISO/AMT exercise schedule, NSO sell-vs-hold decision, RSU vest…
- [clawpay-mcp](https://github.com/up2itnow0822/clawpay-mcp) - Non-custodial x402 payment layer for AI agents. Agents sign transactions from their own wallet with on-chain spend limits — no custodial…
- [argentum-core](https://github.com/giskard09/argentum-core) - Karma economy for AI agents and humans. Submit good actions, get community attestations, earn on-chain reputation on Arbitrum. 5 MCP tools:…
- [tickerdb-mcp](https://github.com/tickerdb/tickerdb-mcp) - Pre-computed market data for AI agents — 10,000+ US stocks, ETFs, and crypto with 182 categorical indicators (trend, momentum, volatility,…
- [mcp](https://github.com/agentIgris/agentfund) - Fundraising infrastructure for AI agents on Solana — campaigns, x402 donations, and on-chain reputation. MCP tools for registering agents,…
- [agent-discovery-mcp](https://github.com/Claynsn/agent-discovery-mcp) - Minimal MCP server (~250 lines TS) for ERC-8004 agent discovery + x402 payment. Three tools: `find_agents_by_skill` (via 8004scan public API),…
- [mcp-server](https://github.com/OilpriceAPI/mcp-server) - Real-time oil, gas & commodity prices — spot, history, futures curves, price alerts and market briefs for Brent, WTI, natural gas, diesel, jet… 🏅
- [barker-stablecoin-skills](https://github.com/YBSbarker/barker-stablecoin-skills) - Real-time stablecoin yield index across DeFi protocols and CEX earn programs, with an AI yield advisor, risk signals and non-custodial… 🏅
- [alphai-mcp](https://github.com/makeev/alphai-mcp) - Real-time, AI-enriched financial news for trading agents: full-text & ticker search, trending and "actionable-now" feeds, SEC Form 4 insider… 🏅
- [secfinapi-mcp](https://github.com/michalperni11-gif/secfinapi-mcp) - Standardized SEC EDGAR financial data — income statements, balance sheets, cash flow and 40+ ratios for every US public company, normalized from… 🏅
- [quantdata-plugin](https://github.com/celineycn/quantdata-plugin) - Measured market statistics for US stocks/ETFs, futures, HK and A-shares: five-class day-type probabilities for the session in progress, Weis… 🏅
- [equivault-mcp](https://github.com/equivault/equivault-mcp) - Official EquiVault MCP — AI-powered equity research for Claude. 38 tools covering company fundamentals, financial statements, ratios & metrics,… 🏅
- [gloria-mcp](https://github.com/cryptobriefing/gloria-mcp) - AI-curated crypto news intelligence for agents. Real-time headlines with sentiment analysis, AI-generated recaps, keyword search, and ticker… 🏅
- [mcp-server](https://github.com/bitcompare/mcp-server) - Crypto rates (lending, staking, borrowing), coin metadata, aggregated prices, market stats, stablecoin peg-stability, and symbol resolution. 18… 🏅
- [mcp](https://github.com/everstake/mcp) - An MCP server for Everstake's non-custodial staking data across 130+ networks: live APY, uptime metrics, rewards calculator, integrations,… 🏅
- [portal-mcp-server](https://github.com/subsquid-labs/portal-mcp-server) - Query onchain data across EVM, Solana, Bitcoin, Substrate, and Hyperliquid via the SQD Portal API; hosted Streamable HTTP endpoint or local stdio. 🏅
- [entia-mcp-server](https://github.com/ENTIA-IA/entia-mcp-server) - Verified business-identity intelligence for AI agents & MCP clients — company verification, VAT, BORME, GLEIF, ownership and risk signals across… 🏅
- [pattern-vista-cli](https://github.com/xsf0221/pattern-vista-cli) - End-of-day US equity technical data: how far each S&P 500 / Nasdaq 100 name has strayed from its own 200-day average, what share of the universe… 🏅
- [coinpaprika-mcp](https://github.com/coinpaprika/coinpaprika-mcp) - Coinpaprika's MCP server exposes the CoinPaprika API covering 12,000+ cryptocurrencies and 350+ exchanges with real-time prices, tickers, OHLCV,… 🏅
- [finlight-mcp](https://github.com/callbk/finlight-mcp) - Real-time financial news: search by ticker, source, and language, with sentiment scores and tagged company entities. 🏅
- [agent-mcp](https://github.com/IMBAwallet/agent-mcp) - Official prepaid IMBA Agent MCP: docs (policy/HowTo, no money) plus spend (USDT TRC-20 deposit, Visa prepaid, travel eSIM, gift cards) with the… 🏅
- [mcp-server](https://github.com/true402/mcp-server) - Pay-per-call AI + web + on-chain tools for agents over x402 (USDC on Base) — no accounts, no API keys; the wallet is the identity. 11 tools incl.… 🏅
- [wealthville-integrations](https://github.com/amitesh-m/wealthville-integrations) - Solana + EVM liquidity-pool scores for AI agents: **Enter/Hold/Exit verdicts** and a composite **0–100 Wealthville Score**, plus a live,… 🏅
- [cryptotaxedge-mcp](https://github.com/sturs49/cryptotaxedge-mcp) - US tax classification for on-chain transactions: submit a transaction hash, get the canonical category, US tax treatment, a confidence score, and… 🏅
- [peil-mcp](https://github.com/Luminc/peil-mcp) - Peil — financial orientation for Dutch freelancers (ZZP'ers): log hours, draft invoices from unbilled time, and ask where you stand — outstanding,… 🏅
- [cukaimax-agent](https://github.com/jakzaizzat/cukaimax-agent) - Source-linked Malaysian individual and sole-proprietor tax authority for AI agents. Five read-only tools cover YA2025 Form BE drafts, Form B… 🏅
- [mcp](https://github.com/predictionmarketspicks/mcp) - Quant tools + an NFL fantasy draft assistant for AI agents — Kalshi & Polymarket EV, edge, ADP. 22 tools: expected value, Kelly sizing, Bayesian… 🏅

## Science & Research

- [idea-reality-mcp](https://github.com/mnemox-ai/idea-reality-mcp) - Pre-build reality check for AI coding agents. Scans GitHub, Hacker News, npm, PyPI, and Product Hunt to detect existing competition before…
- [deep-research-mcp](https://github.com/pminervini/deep-research-mcp) - Deep research MCP server for OpenAI Responses API or Open Deep Research (smolagents), with web search and code interpreter support.
- [notebooklm-mcp-secure](https://github.com/Pantheon-Security/notebooklm-mcp-secure) - Query Google NotebookLM from Claude/AI agents with 14 security hardening layers. Session-based conversations, notebook library management, and…
- [patent-literature-search-mcp](https://github.com/patsnap/patent-literature-search-mcp) - Natural-language patent and scientific literature search across 200M+ patents and 216M+ papers from 170+ jurisdictions, with semantic/BM25 search,…
- [research-hub](https://github.com/WenyuChiou/research-hub) - Research workspace MCP integrating Zotero, Obsidian, and NotebookLM. Search papers (arXiv/Semantic Scholar/PubMed/CrossRef), ingest into Zotero,…
- [semantic-scholar-mcp](https://github.com/smaniches/semantic-scholar-mcp) - Semantic Scholar MCP server: 14 typed tools over 200M+ academic papers — search, paper/author retrieval, citation-graph traversal, and…
- [BrowserAI-Dev](https://github.com/BrowseAI-HQ/BrowserAI-Dev) - Evidence-backed web research for AI agents. Real-time search with cited claims, confidence scores, and compare mode (raw LLM vs evidence-backed).…
- [sourcelibrary-v2](https://github.com/Embassy-of-the-Free-Mind/sourcelibrary-v2/tree/main/mcp-server) - Search and cite rare historical texts (alchemy, Hermeticism, Renaissance philosophy) with DOI-backed academic citations from Source Library.
- [legiscan-mcp](https://github.com/sh-patterson/legiscan-mcp) - Access legislative data from all 50 US states and Congress — search bills, get full text, track votes, and look up legislators via the LegiScan API.
- [scholar-feed-mcp](https://github.com/YGao2005/scholar-feed-mcp) - Semantic search over 600k+ CS/AI papers with citation-graph traversal, full-text extraction, embeddings, and BibTeX export. Works anonymously or…
- [scholar-sidekick-mcp](https://github.com/mlava/scholar-sidekick-mcp) - Resolve any scholarly identifier (DOI, PMID, PMCID, ISBN, arXiv, ISSN, ADS bibcode, WHO IRIS URL) into structured CSL JSON, format in 10,000+…
- [tripitaka-mcp](https://github.com/dhamma-seeker/tripitaka-mcp) - Search, cite, and compare the Pāli Canon (Tipiṭaka) — full coverage at parity with SuttaCentral (~444K segments across Sutta, Vinaya, Abhidhamma).…
- [paperboy](https://github.com/michaelellis003/paperboy) - Send research papers from Claude to a Kindle or Kobo, with Zotero as the source of truth. Searches arXiv and OpenAlex, recommends related work via…
- [agenda-intelligence-md](https://github.com/vassiliylakhonin/agenda-intelligence-md) - Auditable strategic-risk memos for AI agents — sanctions, regulatory, geopolitics, trade. Geography-routed regional specialists (Central…
- [ph-civic-data-mcp](https://github.com/xmpuspus/ph-civic-data-mcp) - Philippine government data as agent-callable tools: PHIVOLCS earthquakes + volcano alerts, PAGASA weather + typhoons, PhilGEPS procurement, PSA…

## Life Sciences & Health

- [biomcp](https://github.com/genomoncology/biomcp) - Biomedical research MCP server providing access to PubMed, ClinicalTrials.gov, and MyVariant.info.
- [HealthChain](https://github.com/healthchainai/HealthChain) - Typed, validated FHIR tools for healthcare AI agents — build, read, validate, and code FHIR resources from a patient bundle, with terminology…
- [medical-mcp](https://github.com/JamesANZ/medical-mcp) - An MCP server that provides access to medical information, drug databases, and healthcare resources. Enables AI assistants to query medical data,…
- [ChatSpatial](https://github.com/cafferychen777/ChatSpatial) - MCP server for spatial transcriptomics analysis with 60+ integrated methods covering cell annotation, deconvolution, spatial statistics, and…
- [encode-toolkit](https://github.com/ammawla/encode-toolkit) - MCP server and Claude Plugin for a full ENCODE Project genomic data and analysis toolkit — search, download, track, and analyze functional…
- [heor-agent-mcp](https://github.com/neptun2000/heor-agent-mcp) - HEOR (Health Economics and Outcomes Research) MCP server with 7 tools for literature search across 41 medical data sources (PubMed, NICE, CADTH,…
- [wellness-nourish](https://github.com/davidmosiah/wellness-nourish) - Zero-credential nutrition and hydration MCP server with food search, barcode lookup, meal estimation, intake logs and daily summaries.
- [fulcra-context-mcp](https://github.com/fulcradynamics/fulcra-context-mcp) - MCP server for accessing personal health and biometric data including sleep stages, heart rate, HRV, glucose, workouts, calendar, and location via…
- [mcp-techTrend](https://github.com/salwks/mcp-techTrend) - Multi-source academic + code + medical-regulatory trend monitoring (arXiv, PubMed, GitHub, Hugging Face, openFDA 510(k)/Recalls). Newspaper-style…
- [plant-genomics-mcp](https://github.com/musharna/plant-genomics-mcp) - 32 tools for plant-genomics locus lookup across 11 public backends (Ensembl Plants, Phytozome, UniProtKB, KEGG, STRING-DB, Gramene, Europe PMC,…

## Government & Open Data

- [mcp-server-jdbc](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc) - Connect to any JDBC-compatible database and query, insert, update, delete, and more.
- [mcp-swiss](https://github.com/vikramgorla/mcp-swiss) - 68 tools for Swiss open data: transport, weather, geodata, companies, parliament, and more. Zero API keys required.
- [ibge-br-mcp](https://github.com/SidneyBissoli/ibge-br-mcp) - Brazilian Census Bureau (IBGE) data server with 23 tools for demographics, geography, economics, and statistics. Covers localities, SIDRA tables,…
- [brasil-data-mcp](https://github.com/alanpcf/brasil-data-mcp) - Brazilian public data for AI agents — companies (CNPJ), addresses (CEP), banks (BACEN), national holidays — via BrasilAPI. No auth, no API key.…
- [sugra-api-mcp](https://github.com/Sugra-Systems/sugra-api-mcp) - Connector between LLM agents and world data - 1,500+ endpoints aggregating 160+ primary sources across 36 data domains: markets, macroeconomics,… 🏅
- [civicdataforge-mcp](https://github.com/equinoxaifinance-rgb/civicdataforge-mcp) - Ten source-bound government-record evidence tools covering US STR permits, lodging licenses, property violations, healthcare exclusions,… 🏅

## Legal & Regulatory

- [us-legal-mcp](https://github.com/JamesANZ/us-legal-mcp) - An MCP server that provides comprehensive US legislation.
- [ris-mcp-ts](https://github.com/philrox/ris-mcp-ts) - Access Austrian federal laws, state laws, court decisions, and legal documents via the RIS (Rechtsinformationssystem) API with 12 specialized tools.
- [korean-rnd-regs-mcp](https://github.com/smilemin07/korean-rnd-regs-mcp) - Natural-language search and review of South Korea's national R&D (research & development) regulations (acts, decrees, and administrative rules),…
- [lex](https://github.com/SFHAJJI/lex) - Point-in-time Luxembourg and EU law: what did this article say on this date. Ten read-only tools for search, as-of retrieval, article history,…
- [canlii-mcp](https://github.com/Vaquill-AI/canlii-mcp) - Canadian case law and legislation metadata via CanLII. Bring-your-own free CanLII API key. Hosted endpoint at canlii-mcp.vaquill.ai. MIT.

## Geospatial & Location

- [geolens](https://github.com/geolens-io/geolens/tree/main/mcp) - Read-only access to a self-hosted GeoLens geospatial catalog: dataset search, schemas, GeoJSON features, saved maps, and sandboxed read-only SQL… 🏅
- [mcp_weather_server](https://github.com/isdaniel/mcp_weather_server) - Get weather information from https://api.open-meteo.com API.
- [emem](https://github.com/Vortx-AI/emem) - Earth memory MCP server that gives AI agents signed geospatial facts and cite-able receipts for place-based questions. Covers elevation, land…
- [vessel-traffic-mcp](https://github.com/tools-mcp/vessel-traffic-mcp) - Read-only vessel identity lookup, AIS-style positions, tracks, port calls, carrier schedules, vessel schedules, and delay heuristics with source…
- [offnadir-delta-mcp](https://github.com/Off-Nadir-Lab/offnadir-delta-mcp) - Live, geolocated world-event intelligence and a Daily World Brief for AI agents — query event signals (coordinates, severity, sources), hotspots,… 🏅
- [swath-mcp](https://github.com/vibecodebeast/swath-mcp) - Radar-verified hail/wind storm detection and affected-property intelligence for the continental US — NOAA MRMS swath detection, per-address storm… 🏅

## Travel & Transport

- [mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) - Provides tools to search Airbnb and get listing details.
- [aviationstack-mcp](https://github.com/Pradumnasaraf/aviationstack-mcp) - An MCP server using the AviationStack API to fetch real-time flight data including airline flights, airport schedules, future flights and aircraft…
- [chelaile-mcp](https://github.com/PeanutSplash/chelaile-mcp) - A Chelaile-powered MCP server that lets LLMs query realtime bus and metro data in China — arrival times, vehicle positions, timetables, nearby…
- [mcp-server](https://github.com/campertunity/mcp-server) - Search campgrounds around the world on campertunity, check availability, and provide booking links. 🏅
- [infranode](https://github.com/street1983nk/infranode) - Keyless remote MCP server for German public infrastructure open data: weather, air quality, traffic, public transit, parking and roadworks across…
- [luxembourg-mcp](https://github.com/amirdaraee/luxembourg-mcp) - Keyless access to official Luxembourg public data: laws, statistics, live parking and traffic, weather alerts, environment, parliament, geodata,… 🏅
- [gondola-mcp](https://github.com/gondola-ai/gondola-mcp) - The travel MCP that shows cash and award (points) rates side by side — hotels, flights, and rental cars across every major loyalty program, with… 🏅
- [mcp-national-rail](https://github.com/lucygoodchild/mcp-national-rail) - An MCP server for UK National Rail trains service, providing train schedules and live travel information, intergrating the Realtime Trains API.
- [wander-agent](https://github.com/VirajMishra1/wander-agent) - Personal travel agent with 66 tools — flights, hotels, visa checks, itinerary planning, travel advisories, currency conversion, passport power…
- [rental-cars](https://github.com/OctoTrip/rental-cars) - Free rental car search with real-time pricing from multiple providers worldwide. No API key required. Hosted at mcp.octotrip.app.
- [tripgo-mcp-server](https://github.com/skedgo/tripgo-mcp-server) - Provides tools from the TripGo API for multi-modal trip planning, transport locations, and public transport departures, including real-time…
- [hemmabo-mcp-server](https://github.com/HemmaBo-se/hemmabo-mcp-server) - Host-owned, agent-native direct booking for vacation rentals: agents discover a host's own domain, verify a host-domain signed (VRP ·… 🏅
- [pickadive-mcp](https://github.com/afiliptsov/pickadive-mcp) - Live scuba-dive planning for AI agents — ranked dive-forecast windows near any place for any day, month-by-month best-time climatology per… 🏅
- [kids-stay-mcp](https://github.com/sitebox/kids-stay-mcp) - Verified kid-friendly hotel data for Japan — search 1,900+ hotels by 48 conditions checked against official sources (diaper-friendly baths, baby… 🏅
- [tablejourney-mcp](https://github.com/lewismvaughan/tablejourney-mcp) - Free, keyless remote MCP server for food travel data in 200+ cities: hand-checked restaurants, cafes, markets and street food (each with a source and check date), food festivals with resolved dates, signature dishes and itineraries. 🏅

## Social & Community

- [reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) - Browse Reddit posts, search content, and analyze user activity without API keys. Works out-of-the-box with Claude Desktop.
- [reddit-research-mcp](https://github.com/king-of-the-grackles/reddit-research-mcp) - AI-powered Reddit intelligence for market research and competitive analysis. Discover subreddits via semantic search across 20k+ indexed…
- [macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) - 🎖️ 🐍 ☁️ Access real-time X/Reddit/YouTube data directly in your LLM applications with search phrases, users, and date filtering. 🏅
- [tiktok-mcp](https://github.com/HasData/tiktok-mcp) - Remote MCP server for public TikTok data: profile lookup, an account's videos, video comments and reply threads, and keyword search over videos or…
- [linkedin-mcp](https://github.com/devag7/linkedin-mcp) - LinkedIn for AI assistants over an authenticated browser session — profiles, people/job/company search, feed, messaging, and gated writes…
- [weixin-articles-mcp](https://github.com/jj-cheng25/weixin-articles-mcp) - Read WeChat (微信) Official Account articles with native multimodal output — body, images, and video keyframes as MCP content blocks. Handles all…
- [sofya-mcp](https://github.com/sofya-co/sofya-mcp) - Web tools for AI agents through the Sofya API. Search the web for full page content instead of snippets, fetch URLs as clean markdown (including… 🏅
- [postmcp-mcp-server](https://github.com/postmcp/postmcp-mcp-server) - Publish and schedule posts to LinkedIn, X, Facebook, Instagram, Threads, Bluesky and YouTube Shorts from one API key. 16 tools for preflight… 🏅
- [tokportal-mcp](https://github.com/tokportal/tokportal-mcp) - Official TokPortal MCP server: managed social infrastructure — real TikTok, Instagram and YouTube accounts created, warmed and operated by human… 🏅
- [veezee-mcp](https://github.com/veezeehq/veezee-mcp) - Real-time LinkedIn, X (Twitter) and Reddit data: profiles, companies, posts, search, sentiment. Hosted at mcp.veezee.io with OAuth or self-serve keys. 🏅

## Sports

- [trainingpeaks-mcp](https://github.com/JamsusMaximus/trainingpeaks-mcp) - Query TrainingPeaks workouts, analyze CTL/ATL/TSB fitness metrics, and compare power/pace PRs through Claude Desktop.
- [livetennisapi-mcp](https://github.com/livetennisapi/livetennisapi-mcp) - Real-time tennis for ATP, WTA, Challenger and ITF — live scores, players, fixtures, model win-probability, and match-winner market prices. 12…
- [claudinho](https://github.com/arturogarrido/claudinho) - Live scores, fixtures, standings, and read-only prediction-market signals for the 2026 World Cup. No API keys.
- [balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) - MCP server that integrates balldontlie api to provide information about players, teams and games for the NBA, NFL and MLB.
- [mcp-sports-hub](https://github.com/lacausecrypto/mcp-sports-hub) - Unified server aggregating 41 sports-data providers (~396 tools): live scores, standings, player stats, betting odds, F1/MotoGP/NASCAR, esports,…
- [sportsdata-mcp](https://github.com/DanielTomaro13/sportsdata-mcp) - Live sports data and cross-book betting odds as ~500 tools across 28 providers — 10+ bookmakers (Sportsbet, TAB, Betfair, Pinnacle, FanDuel…),…
- [sportscore-mcp](https://github.com/Backspace-me/sportscore-mcp) - Live scores, standings, top scorers, player stats, and knockout Brackets for football, basketball, cricket, and tennis. Free public API, no key…
- [x402-fpl-api](https://github.com/dohyung1/x402-fpl-api) - Personalized Fantasy Premier League intelligence — scored captain picks, transfer suggestions, differentials, fixture outlook, price predictions,…
- [nba_mcp_server](https://github.com/labeveryday/nba_mcp_server) - Access live and historical NBA statistics including player stats, game scores, team data, and advanced analytics via Model Context Protocol.
- [lumify](https://github.com/lumifyai/lumify) - Agent-ready sports intelligence: schedules, live scores, odds, betting splits, and explainable bet confidence via hosted MCP…

## Culture & Media

- [mcp-open-library](https://github.com/8enSmith/mcp-open-library) - A MCP server for the Open Library API that enables AI assistants to search for book information.
- [anilist-mcp](https://github.com/yuna0x0/anilist-mcp) - A MCP server integrating AniList API for anime and manga information.
- [tdmcp](https://github.com/Pantani/tdmcp) - Stop wiring nodes by hand — describe a visual and the AI builds a real, playable TouchDesigner network: audio-reactive, generative, particle, 3D…
- [metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) - Metropolitan Museum of Art Collection API integration to search and display artworks in the collection.
- [open-museum-mcp](https://github.com/cfpramod/open-museum-mcp) - Federated, license-verified search across The Met, Cleveland, AIC, Wikimedia Commons, and Europeana. Strict-default-deny rights gate accepts only…
- [smithsonian-mcp](https://github.com/molanojustin/smithsonian-mcp) - MCP server that provides AI assistants with access to the Smithsonian Institution's Open Access collections.
- [mcp-alphabanana](https://github.com/tasopen/mcp-alphabanana) - Local MCP server for generating image assets with Google Gemini (Nano Banana 2 / Pro). Supports transparent PNG/WebP output, exact…
- [ableton-mind](https://github.com/Pantani/ableton-mind) - Control Ableton Live from Claude, Cursor or Codex through a local Remote Script bridge: inspect sets, create tracks, scenes and clips, load…
- [memeboat-mcp](https://github.com/memebo-at/memeboat-mcp) - Create real, shareable memes from 25,000+ templates on memebo.at. Search the catalog, caption a template, get a live meme URL back. Free,… 🏅

## Real Estate

- [zillow-mcp](https://github.com/HasData/zillow-mcp) - Remote MCP server for Zillow: for-sale, for-rent and sold listings with rich filters, and full property details (price and tax history, schools,…
- [pedra-mcp](https://github.com/pedra-ai/pedra-mcp) - AI photo and video editing for real-estate listings via the Pedra API: virtual staging, renovation, room emptying, photo enhancement, sky… 🏅
- [addressintel-mcp](https://github.com/RantumBits/addressintel-mcp) - SF Peninsula (California) building permits and parcel buildability: search issued permits by city, keyword, contractor or valuation; SB 9… 🏅

## Environment & Climate

- [agentic-swmm-workflow](https://github.com/Zhonghao1995/agentic-swmm-workflow) - Eleven MCP servers exposing a reproducible EPA SWMM stormwater-modelling workflow: model building, simulation runs with manifests and continuity…
- [ambee-mcp](https://github.com/ambeelabs/ambee-mcp) - 🎖️ 📇 ☁️ 🍎 🪟 🐧 The official Model Context Protocol server for Ambee. It gives any MCP-compatible AI assistant — Claude, ChatGPT, Cursor, VS Code,… 🏅

## Space & Aerospace

- [orbit-sentinel-mcp](https://github.com/viventine-space/orbit-sentinel-mcp) - Search 419,000+ space regulatory filings from FCC, ITU, UNOOSA, and FAA — semantic search, entity dossiers, spectrum holdings, launch licenses,… 🏅

## People & Work

- [Moxlade — Upwork Buyer Intelligence](https://buyer.moxlade.com) - Who the anonymous Upwork client behind a posting is, what they have paid, and market rates. Answers only; the corpus never leaves. Metered per… 🏅

## Legend

🏅 Published by the provider of the data itself, rather than a third party.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) first.

Removal requests from server owners are honoured without argument — open an issue.
