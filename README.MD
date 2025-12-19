🧪 Jr. AI Engineer Take-Home Assignment (Shopify Data)

Thanks for taking the time to complete this exercise!

This assignment is designed to reflect real-world AI-assisted engineering work while respecting your time.

⏱ Timebox (Important)

⏰ Please spend no more than 1 hour total.

This assignment is intentionally ambitious. You are expected to use AI coding tools (Claude, ChatGPT, Copilot, etc.). Partial solutions are totally acceptable.

🎯 Goal

Build a small UI or script that combines:

Public ecommerce product data (from a Shopify store)

Basic search/filtering

An LLM-powered recommendation step

We care about how you work as much as what you build.

🌐 Data Source (Public Shopify Product Catalog)

Please use a public Shopify store product feed, which is often available at:

https://STORE_DOMAIN/products.json


You may choose any public Shopify store you like. Here are a few examples you can use:

https://allbirds.com/products.json

https://kith.com/products.json

https://gymshark.com/products.json

https://sterlingbyusic.com/products.json

https://ugmonk.com/products.json

Note: Some stores may paginate, rate-limit, or return lots of data. That’s fine — you can simply use the first page / first N products.

🧩 Problem Statement

You are building a simple product search + AI recommendation widget.

Core flow

User enters a search query (e.g., “running shoes”, “hoodie”, “water bottle”)

Your app fetches products from the Shopify feed (or caches them locally)

Your app filters/searches products (basic substring match is fine)

Your app sends the top 3 matching products to an LLM prompt

Your app displays the AI recommendation explaining:

Which product is best for a beginner

Which product is best for an expert

Why

You may implement the LLM call as either:

A real API call (OpenAI/Anthropic/etc.), or

A mock function that returns a hardcoded “LLM-like” response

🛠 Requirements
Must-have (choose a reasonable subset)

A basic UI or CLI/script (frontend preferred, but not required)

Shopify product fetching (live or cached)

Search/filtering logic

LLM prompt that consumes multiple products

Display/output of recommendation

You do not need to

Handle pagination perfectly

Make it production-ready

Over-optimize search

Add authentication

Perfect styling

🤖 AI Tool Usage (Very Important)

You are explicitly encouraged to use AI coding tools.

Please include a short write-up explaining:

Which tools you used

Example prompts you used

What was AI-generated vs. what you wrote/edited manually

What worked well and what didn’t

This can be included as:

A section at the bottom of this README, or

A NOTES.md

✨ Optional Stretch Ideas (Do NOT try to do all)

Beginner vs. Expert toggle in the UI

Loading/error states

“Tone” selector (professional, casual, expert)

A comparison table between two products

Validation of AI output (ensure JSON schema, required fields, etc.)

📤 Submission Instructions

Please submit:

Your code (GitHub repo link or zip)

Your AI-usage notes

Simple run instructions

Partial solutions are completely acceptable.

🧠 What We’re Evaluating

We are not grading on completeness.

We care about:

Problem decomposition

Effective use of AI tools

Reasoning about AI output

Frontend/backend fundamentals

Clear communication

💬 Final Note

If this feels too big to finish manually in one hour — that’s intentional 🙂

We’re excited to see how you approach it!
