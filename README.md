## Cloudscape Design System Demos

This package contains a fork  that follow [Cloudscape Design System](https://cloudscape.design) guidelines and use [Cloudscape components](https://cloudscape.design/components). customized for brand adherence and alignment. This forked design system provides components and styles tailored for branding visual identity and design standards.

### Modifications Overview

This fork includes the following customizations:

	•	Typography: Removal of Open Sans and updated fo SF font family, and letter-soacing adjustment.

This fork is based on Cloudscape is an open source design system  built for and is used by Amazon Web Services (AWS) products and service.

You can view the ordemos running live from the the [Cloudscape website 'demos' list](https://cloudscape.design/demos/).

### Build the project

To install the project dependencies and build all demos:

```
npm install
npm run build
```

The demo artifacts will be output to the `/build` folder.

### Run Dev Server

To start a dev server with live reload:

```
npm start
```

The demos will be available at http://localhost:9615.

### Run Tests

```
npm test
```

This will build the project by running the `build` script, start a webpack dev server instance and run tests afterwards.

To run only tests without building the full project again:

```
npm run test-no-build
```

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
