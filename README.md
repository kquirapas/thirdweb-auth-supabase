## Getting Started

This example demonstrates how to use thirdweb Auth with Supabase.

Before running the project, you'll need to seutp and configure Supabase [as specified here](https://portal.thirdweb.com/auth/integrations/supabase).

To run the project, first clone this repository, and then run one of the following commands to install the dependencies:

```bash
npm install
# or
yarn install
```

Next, you need to create a `.env.local` file and add the following environment variables:

```
NEXT_PUBLIC_THIRDWEB_AUTH_DOMAIN=
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE=
```

The `NEXT_PUBLIC_THIRDWEB_AUTH_DOMAIN` is used to prevent phishing attacks on the thirdweb Auth (sign-in with ethereum) request. You can learn more about it in the [Auth documentation](https://portal.thirdweb.com/auth/how-auth-works/sign-in-with-wallet#domain).

The remaining environment variables are used to connect to your Supabase instance, and can be found in the settings section of your Supabase dashboard.

Once you've configured the necessary environment variables, you can run this project with the following command:

```bash
npm run dev
# or
yarn dev
```

Now, you can navigate to [http://localhost:3000](http://localhost:3000) to visit the client side page where you can connect a wallet, sign-in with ethereum and view the payload, and use the payload to authenticate with the backend.

## Learn More

To learn more about thirdweb, take a look at the following resources:

- [thirdweb Auth Documentation](https://docs.thirdweb.com/auth) - learn about thirdweb Auth.
- [thirdweb React Documentation](https://docs.thirdweb.com/react) - learn about our React SDK.
- [thirdweb Portal](https://docs.thirdweb.com) - check our guides and development resources.

You can check out [the thirdweb GitHub organization](https://github.com/thirdweb-dev) - your feedback and contributions are welcome!

## Join our Discord!

For any questions, suggestions, join our discord at [https://discord.gg/thirdweb](https://discord.gg/thirdweb).
