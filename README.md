<p align="center">
  <h3 align="center">
    react-facebook-login
  </h3>

  <p align="center">
    React hook for Facebook login
  </p>

</p>

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About](#about)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About

`react-facebook-login` - React hook for Facebook login

## Installation

```bash
npm install --save @hoangnguyen1247/react-facebook-login
```

or

```bash
yarn add @hoangnguyen1247/react-facebook-login
```

## Getting Started

The simplest way to use `react-facebook-login`

```typescript
import useFacebookLogin from "@hoangnguyen1247/react-facebook-login";

function App {

    const { isSdkLoaded, fbLogin } = useFacebookLogin({
        onSuccess: fbCheckLogin,
        appId: process.env.NEXT_PUBLIC_FB_APP_ID,
    });

    return (
        <>
            <Button
                onClick={() => fbLogin()}
            >
                Login
            </Button>
        </>
    )
}
```

## Example

Update soon...

## Contributing

I would greatly appreciate any contributions to make this project better. Please
make sure to follow the below guidelines before getting your hands dirty.

1. Fork the repository
2. Create your branch (`git checkout -b my-branch`)
3. Commit any changes to your branch
4. Push your changes to your remote branch
5. Open a pull request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- [react](https://reactjs.org/)

Copyright &copy; 2022 Hoàng Nguyễn
