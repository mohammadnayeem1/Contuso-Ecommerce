**About**

Contuso ecommerce is a fullstack web application that lets users view specific products, view all of its details, add product to cart, and checkout. The technologies used for this application are Next.js, Sanity, and Stripe.

Deployed version can be found here: https://contuso-ecommerce.vercel.app/


**How to Run**


After forking and cloning the repo, use npm to install dependencies and to run the server.

npm install

npm run react-dev

Create a .env file in the root directory and add public sanity token, stripe publishable key, and stripe secret key.

NEXT_PUBLIC_SANITY_TOKEN= ""

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY= ""

NEXT_PUBLIC_STRIPE_SECRET_KEY= ""

**Features**

Home page that is responsive and dynamic. Everything from the hero image/description, to products, footer image/title can be modified in seconds using sanity.

![image](https://user-images.githubusercontent.com/16688207/192125733-c228686a-4923-42be-904b-d632a901a8e7.png)

Product page that displays each product details and images using next.js dynamic routing. From here you can add to cart or buy now as well as navigate to other products. Products can easily be added or modified using Sanity.

![c247ce40aca0e8bac9616b2c90edb0a4](https://user-images.githubusercontent.com/16688207/192126267-fea889ef-3a3d-4807-abf7-7714ac4551ee.gif)

Cart where you can modify items you want and checkout 

![771592a9a35647be699e67bc9d25c472](https://user-images.githubusercontent.com/16688207/192126046-6c3cd048-3422-4dbb-bda4-f2c422bfe0d7.gif)

Stripe Payment system allowing for secure and easy payment

![image](https://user-images.githubusercontent.com/16688207/192125988-20cb8646-dda6-4a4f-8992-13aef44ea890.png)
