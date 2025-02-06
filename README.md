This minimal reproduction includes a Clerk middleware that is based on the "custom onboarding flow" [docs](https://clerk.com/docs/references/nextjs/add-onboarding-flow#configure-your-middleware-to-read-session-data).
I have removed most of the middleware content to focus only on whether there's a user ID or not.
The case is reproduced - a CORS error when redirecting to Clerk sign-in screen.
