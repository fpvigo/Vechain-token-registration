# Vechain-token-registration
# VeChain Token-registry - Submit Form  Token-registry is a platform where you can submit the token. Token-registry will provide a list to application includes the token name, symbol, description, image and contract address in Mainnet or Testnet. If you wish your token on the list, you can create a pull request to submit token.
VeChain Token-registry - Submit Form
Token-registry is a platform where you can submit the token. Token-registry will provide a list to application includes the token name, symbol, description, image and contract address in Mainnet or Testnet. If you wish your token on the list, you can create a pull request to submit token.

Requirements
Make sure the contract address is correct (main/test)
Token image is required
Folder name must be the same as the contract address
Clear and simple description
Comply with directory & contents rules
Getting Ready for Submission
Fork Token-registry
Forking a repository allows you to create your token details and send a pull request for the maintainers to review and merge into Token-registry.

Generate Token Information
Create a directory in main /test/both and named the directory with Contract address.
Contract address start with 0x + 40 characters and must be lower case, E.g., 0x0000000000000000000000000000456e65726779.

├── main 
│   └── 0x0000000000000000000000000000456e65726779 //Contract address
│       ├── token.png
│       ├── info.json
│       └── additional.json
Import your token image into the directory and named it token.(Image must be png format, transparent backgroundand 256 x 256 pixel size)

Generate a info.json file includes token details.

    {
        "name": "VeThor",
        "symbol": "VTHO",
        "decimals":18,
        "desc": "Represents the underlying cost of using VeChainThor"
    }
Generate an additional.json file includes following details.
{
  "website":"https://www.example.com/", 
  "links":{
      "twitter":"https://twitter.com/example",      
      "telegram":"https://t.me/example",
      "facebook":"https://www.facebook.com",
      "medium":"https://medium.com/@example",
      "github":"https://github.com/example",
      "slack":"https://example.slack.com/"
    },
  "whitePaper":"https://www.example.com/whitepaper/"
}

Only Twitter / Telegram / Facebook / Medium / Github / Slack are supported

Making a Pull Request / Submit Your token
After Create a pull request, your pull request will be reviewed by maintainers. Once the review is completed, your token will be merged into the base branch.
