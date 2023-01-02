# SecureSentral

![SecureSentral](https://avatars.githubusercontent.com/u/121227945?s=200&v=4)

**SecureSentral** is a Centralized Information Security Management Portal, which is a portal that centralizes several management functions in the information security line into one place that can be integrated with various other services.
<p>
  • <a href="https://github.com/SecureSentral/securesentral">Homepage</a>
  • <a href="#deployment">Deployment Steps</a>
   • <a href="#features">Features</a>
  • <a href="https://github.com/SecureSentral/securesentral" target="_new">Demo</a>
  • <a href="#roadmap">Roadmap</a>
    • <a href="#license">License</a>
  • <a href="#support">Support Us</a>
  • 
</p>

## Features
Some of the main features include the following but are not limited to this list because the available features can be added or reduced according to user needs

  **Ticketing system**\
  Secure Sentral supports ticketing centralization for information security needs such as requesting a product security review ticket, and other assignment tickets related to the realm of information security

  **Asset inventory for cloud and on-premises**\
SecureSentral can be integrated with various infrastructure services to monitor inventory of well-known cloud services such as GCP, AWS which are currently supported and in the future other services and on-premise infrastructure will be added.

  **Charts**\
SecureSentral has a dashboard that can be customized as needed to display charts such as SLA on a ticket, how many changes to an inventory and so on

  **Asset monitoring and alerting**\
SecureSentral can monitor inventory changes and send warnings to users when changes occur according to predetermined settings. Currently, warning integration can only be done via slack and will be developed to integrate with other services.

  **Security analysis tools**\
SecureSentral has several integrations with tools to analyze the security of a service, currently available are as follows:

 - Dependency checkers

Dependency-Check is a Software Composition Analysis (SCA) tool that attempts to detect publicly disclosed vulnerabilities contained within a project's dependencies. It does this by determining if there is a Common Platform Enumeration (CPE) identifier for a given dependency.

 - SSL checker

Used to check the details of a secure connection certificate

 - Password/PIN Generator
Used to generate passwords or PINs safely that can be used by users

  **Centralized identity management**\
SecureSentral can manage several cloud service identities simultaneously in one place, such as adding, changing access, and removing someone's access to various services at once, including being able to see someone has access to any service, provided that the service must have been integrated with SecureSentral, currently available are as follows:

 - GCP
 - AWS
 - CLoudflare

  **Risk registers**\
SecureSentral also provides a place to carry out risk management which can be used to register and monitor known risks so that risks can be tracked properly

  **Knowledge base**\
SecureSentral has a knowledge base that can manage content according to user needs as an information center for end users.

## Roadmap

You can find the **SecureSentral** road map here: [SecureSentral Roadmap](https://github.com/orgs/SecureSentral/projects/1)

## Documentations
Under constructions.

## Tech Stacks

- [FastAPI](https://fastapi.tiangolo.com/): High-performance web framework for building APIs
- [Stisla](https://stisla.multinity.com/): HTML5 template for modern web apps
- [Starlette](https://www.starlette.io/): Async web framework for Python
- [Uvicorn](https://www.uvicorn.org/): Blazing fast ASGI server
- [MongoDB](https://www.mongodb.com/): NoSQL database for storing data in flexible, JSON-like documents


## License

**SecureSentral** is licensed under the [MIT License](LICENSE)

As for all other code/plugin/project licenses used in this project, still follow the Author's license.

## Support Us

You can help to develop SecureSentral for the better by contributing directly to the SecureSentral repository or you can also support us by buying us delicious coffee by pressing the button below

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/securesecntral)

## Custom integration / deployment

Please contact us to arrange a discussion schedule if you need special integration with your internal services or other services that have not been provided at this time according to your needs or custom deployment following the infrastructure you have.

Contact Us : mail@secs.my.id
