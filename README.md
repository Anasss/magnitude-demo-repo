# Magnitude Demo Repo

Basic repository to demonstrate how to set up Magnitude test cases.

Why Magnitude for QA Automation
Magnitude eliminates locator maintenance by testing what users see, not DOM structure. Perfect for:

Replacing manual UAT: Automate repetitive user flows (search → cart → checkout) without brittle selectors
Coexisting with Selenium: Use Magnitude for visual validation, keep Selenium for API/DOM testing
Zero-maintenance tests: Site redesigns don't break tests—if the button still says "Add to Cart", the test still works

Not a replacement for everything. Use Magnitude for stable user journeys. Use Selenium for cross-browser, API validation, and technical assertions.

## Running locally
1. Clone repo:
```
git clone https://github.com/magnitudedev/magnitude-demo-repo.git
```

2. Add LLM keys to .env file

Please follow the [Configure LLMs section](https://github.com/magnitudedev/magnitude?tab=readme-ov-file#configure-llms) in the main Magnitude repo.

3. Install deps
```
npm i
```

4. Start local server (in a separate terminal)
```
npm run dev
```

5. Run Magnitude against the local server
```
npx magnitude
```


## GitHub Actions
See [magnitude.yaml](.github/workflows/magnitude.yaml) for an example of how to run your Magnitude test suite with GitHub Actions.

