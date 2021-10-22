# Vue Storefront 2 Theme Integeration with Kibo Commerce

### Requirements:
- NodeJS v14 or later
- KiboCommerce Account
### Steps
1. Fork the repo
2. Clone your fork of the repo
    ```
    example:
    git clone https://github.com/vuestorefront/template-kibocommerce.git
    cd kibocommerce
    ```
3. Checkout develop branch `git checkout develop`
4. Run `yarn` to install dependencies
5. Define a store running environment by adding a STORE_ENV to your running project or execute the code
    ```$ echo "STORE_ENV=dev" >> .env```
6. Copy config/example.json to an environment named config and update GraphQL Endpoint
    ```
    $ cp ./config/example.json ./config/dev.json
    ```
7. Update clientId and sharedSecret with your respective Application Client ID and Shared secret found in your Kibo Commerce Developer Console.  Visit [Kibo documentation](https://apidocs.kibong-perf.com/?spec=graphql#auth) for more details on API authentication
8. Update apiHost to point at your Kibo Commerce site.
9. Run `yarn dev` to run theme with hot reload at localhost:3000. You can find other commands in `package.json`
10. For production build:

```bash

# build for production and launch server
$ yarn build
$ yarn start

```
For detailed explanation on how things work, check out the [documentation](https://docs.vuestorefront.io/v2/).

## Resources

- [Vue Storefront Documentation](https://docs.vuestorefront.io/v2/)
- [kibocommerce integration Documentation](https://docs.vuestorefront.io/kibocommerce)
- [Community Chat](https://discord.vuestorefront.io)

## Support

If you have any questions about this integration we will be happy to answer them on `kibocommerce` channel on [our Discord](discord.vuestorefront.io).

## Contributors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
