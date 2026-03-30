NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_ZGFyaW5nLWNvZC0zMy5jbGVyay5hY2NvdW50cy5kZXYk
CLERK_SECRET_KEY=sk_test_8PhyKjuV5qljPKGHpVulmWPAEZBSwz7HRwDasmWIWo

proxy
import { clerkMiddleware } from '@clerk/nextjs/server';

export default clerkMiddleware();

export const config = {
  matcher: [
    // Skip Next.js internals and all static files, unless found in search params
    '/((?!_next|[^?]*\\.(?:html?|css|js(?!on)|jpe?g|webp|png|gif|svg|ttf|woff2?|ico|csv|docx?|xlsx?|zip|webmanifest)).*)',
    // Always run for API routes
    '/(api|trpc)(.*)',
  ],
};

pnpm create sanity@latest --project v03kh79u --dataset production --template clean --typescript --output-path studio-onlinestore
cd studio-onlinestore

apo token 
sk2mifcHuNpwrNQGZVzDhwKZeNfY54LHu9I1TdUB9hOMZcp4ZAEpnPZIfyt2DBXSuxxuBuJbKp5nf9AGKuPhtPo3dyGV70CcPbuMkxb96IoUFUfYEMvMYLkXjZLESDhnoT2U16gUGvgpJi72B8r57fxtghhmKbP9helspzvSG5mEFroSg7d3