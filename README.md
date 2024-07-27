# Food-Ordering-backend
This is the backend repository of the food ordering application.
Access the frontend repository [here](https://github.com/coderphilosophy/Food-Ordering-frontend). Demo is available there.

## Installation
1. Clone the repo
   ```
   git clone https://github.com/coderphilosophy/Food-Ordering-backend.git
   cd Food-Ordering-backend
   ```
2. Install dependencies
   ```
   npm install
   ```
3. Set up environment variables:<br/>
   Create a .env file in the root directory and add the necessary environment variables:
   ```
   MONGODB_CONNECTION_STRING=

   #Auth0
   AUTH0_AUDIENCE=
   AUTH0_ISSUER_BASE_URL=

   #Cloudinary
   CLOUDINARY_CLOUD_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=

   #Stripe
   FRONTEND_URL=
   STRIPE_API_KEY=
   STRIPE_WEBHOOK_SECRET=
   ```
4. Start the development server
   ```
   npm run dev
   ```
