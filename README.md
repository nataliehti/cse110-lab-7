## Intro
1. You should fit your automated tests in a Github Action that runs whenever code is pushed. It's easier to do so in a Github action because there would be no risk of you forgetting to run them and it would tell you what tests failed before you try merging your code. And it's better to test as you go, waiting until the end might result in a larger number of errors and code that was built on those errors. 

## Explore

2. No, E2E is for user workflow, not outputs.

## Expose 
3. Navigation reports on overall performance on its initial load, but nothing after that. Snapshot reports on its current state and runs metrics after its been interacted with.
4. I used PageSpeed Insights, but it says:
    - A responsive viewport meta tag should be added to ensure the site scales on mobile devices.
    - Serve static assets with an efficient cache policy to speed up repeat visits to the page.
    - Avoid chaining critical requests to improve speed of page load. 





