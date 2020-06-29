# @skyux-sdk/actions

## Usage

```
- uses: blackbaud/skyux-sdk-actions@master
  with:
    browser-stack-access-key: ${{ secrets.BROWSER_STACK_ACCESS_KEY }}
    browser-stack-username: ${{ secrets.BROWSER_STACK_USERNAME }}
    github-token: ${{ secrets.PERSONAL_ACCESS_TOKEN }}
    npm-token: ${{ secrets.NPM_TOKEN }}
    slack-webhook: ${{ secrets.SLACK_WEBHOOK }}
```

## Build

```
npm run build && npm run pack
```
