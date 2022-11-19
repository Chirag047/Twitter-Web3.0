# Twitter-Web3.0

 <img src =''>
Twitter Web3.0 is a Next.Js application that is built on Ethereum Blockchain using IPFS system and deplying on ethcode 

<!-- ## Table of Contents

- [Inspiration](#inspiration)
- [What it does?](#what-it-does)
- [How we built it?](#how-we-built-it)
- [Challenges we ran into?](#challenges-we-ran-into)
- [Accomplishments that we're proud of?](#accomplishments-that-were-proud-of)
- [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Demo Credentials](#demo-credentials)
- [What we learned?](#what-we-learned)
- [Future Scopes](#future-scope)
- [Screenshots Time](#screenshots-time)
- [Contributing](#contributing)
- [License](#license)
- [About Us](#about-us) -->

## What it does?

It’s a Decentralized Twitter where users can create their own NFT and mint it and also set this NFT as their profile picture linked to their profile . it's user -friendly and gives more security to the user and make the database and personal information more secure. Decentralized database makes easy to find the node in the blockchain where it is stored . we have used IPFS to store minted pictures on pinata and even can check it on ipfs browser that it follows the rules and shows the minted picture on georli testnest network. we have deployed it on ethcode and we have made smart contract in ethereum.

<!-- ## How we built it?

This Project is proudly built with [Appwrite](https://appwrite.io/) and Hosted on [Digital Ocean](https://www.digitalocean.com/). -->

<!-- 'Made with Appwrite' badge 
<a href="https://appwrite.io/" target="_blank" style=";right: 18px;bottom: 18px;z-index: 999;">
  <img style="width: 130px;" src="https://appwrite.io/images-ee/press/badge-pink-box.svg" alt="Built with Appwrite">
</a> -->

Our Frontend is designed with [React](https://reactjs.org/) and [Bulma](https://bulma.io/) and [Tailwind](https://tailwindcss.com/) Framework. We also used Sass(https://sass-lang.com/) for styling.

Cloud Functions has been written in various Languages and some of the code taken from our senior's project and tweaked a bit(getting the required permissions).All Rights goes to them. To know more about it go the `cloud-functions`.

## Challenges we ran into?

Even though our team had knowledge of various techstacks, we still had quite a hurdles.

Chirag - For him, it was his second time developing on ethereum blockchain on a next.js application, using IPFS ,sanity database and ethcode and making smart contract on solidity. Also, he had to learn how to use Lens Protocol. For him, deploying on ethcode was new experience .

Lakshya - For him, it was his first time integrating with nextjs and metamask . He collaborated with Chirag to integrate and fix the crucial bugs for the smart contract and minting.

Harsh - For him, it was his first time particpating in a hackathon and he was quite thrilled and did a great job. he played role in building the frontend and ppt . he was the lead in designing and beautifying the website using tailwindcss. he took time designing the UI for the website but achieved the desired look.

<!-- 
## Accomplishments that we're proud of?

We are proud that this project is ready for production and can be used readily for our university at least. Using an Open Source Backend as a Service ([Appwrite](https://appwrite.io/)). This project has been deployed successfully and can be viewed in any device.

Writing a web scraper function to get the neccessary data from the university website and populating the database was a major accomplishment for us.

Writing cloud functions and automating things for us was a huge happniess😄.

## Installation

This project is built with React and Appwrite. To run this project locally, you need to have Node.js and npm installed on your system.

To run appwrite locally, follow the instructions [here](https://appwrite.io/docs/installation). Note you must have Docker installed on your system.

To run the frontend, follow the instructions below:

```bash
git clone https://github.com/The-Powerpuff-Boys/schedu-mate
cd schedu-mate
npm install && npm start
```

Tu run it locally - go over to [https://localhost:3000](https://localhost:3000)

To setup appwrite, there are some cloud functions well written for you by us😉. You can find them in the cloud functions. To run those cloud functions, follow the instructions [here](https://appwrite.io/docs/functions).
It's recommended to install appwrite CLI to deploy those cloud functions easily. More about it [here](https://appwrite.io/docs/command-line)

> Also edit the `.env` file and update the variables. This should be pretty self-explanatory although we would be happy to help you out if you face any issues. If there is feel free to create an issue.

## Directory Structure

```bash
.
├── functions # Cloud Functions
│   ├── deleteUsers
│   │   └── lib
│   ├── notification
│   │   └── src
│   └── schedumate_setup
│       └── lib
├── public # Public Assets
└── src # React App
    ├── assets # Assets
    ├── components # Components
    │   ├── CourseCard
    │   ├── class
    │   ├── name
    │   ├── navbar
    │   └── profile
    ├── context # Contexts
    └── pages # Pages
        ├── add-classes
        ├── add-mates
        ├── classes
        ├── details
        ├── home
        ├── landing
        ├── login
        ├── my-schedule
        ├── newgroup
        ├── notes
        ├── profile
        └── signup
```

## Demo Credentials

If you want to just try out the demo, you can use the following credentials:

- frontend-server: [schedumate.study](https://schedumate.study)

- backend-server: [appwrite.schedumate.study](https://appwrite.schedumate.study)

**NOTE:** For Backend server, DM me if you just want to see the credentials. I will provide you with the credentials if you want to see how it looks😉

## What we learned?

Everyone learned something.

- **Biswa** learned about deploying and setting up a production server, integrating Appwrite with React, using Appwrite's SDK and API for the JS application, using Appwrite's CLI, linking a domain to Appwrite, setting up SSL, and using subdomains for Appwrite and main domain for frontend.

- **Harsh** learned Appwrite, more advanced fundamentals of React, and how to use Appwrite's SDK and API for the JS application.

- **Gunjan** learned more about React and tools like Bulma and Tailwind CSS. She also learned about appwrite.

- **Vidhu** learned how to write cloud functions for Appwrite, how to deploy cloud functions, how to write a web scraper in Python, and how to populate the database. He also learned about appwrite and integrating it with React.

## Future Scopes

Although this project is ready, there is always scope for more improvement

- We will use NLP to find relevant information for any subject on the internet and display it accordingly.

- We will add a feature to add a class to the schedule by just scanning the QR code of the class.

- Encrypting data using AES-CBC 256 bit encryption.

- Improving the UI and UX of the website.

## 📸 Screenshots Time

<p float="left">
<img src = 'https://user-images.githubusercontent.com/62933155/190900684-ae2c758b-b11a-41b5-9115-f4d2f97845b0.png' width = 500>
<img src = 'https://user-images.githubusercontent.com/62933155/190900696-c55ab8a1-e2e5-464d-91e9-3d9fde925da7.png' width = 500>
</p>
<p float="left">
<img src = 'https://user-images.githubusercontent.com/62933155/190900707-98063c0d-298f-4627-b430-d94b8a265293.png' width = 500>
<img src = 'https://user-images.githubusercontent.com/62933155/190900721-74c6e97c-7b9b-49dc-a833-88e2305d0aea.png' width = 500>
</p>
<p float="left">
<img src = 'https://user-images.githubusercontent.com/62933155/190900730-ce32ab32-8c2b-4203-91dd-c23706b7b7a8.png' width = 500>
<img src = 'https://user-images.githubusercontent.com/62933155/190900733-e237bfa6-ef4a-4125-8284-025a715e29d4.png' width = 500>
</p>
<p float="left">
<img src = 'https://user-images.githubusercontent.com/62933155/190900740-61b1e1bc-83c7-4e06-8e1a-8b7d9e9ab224.png' width = 500>
<img src = 'https://user-images.githubusercontent.com/62933155/190900752-46d8d49f-5130-4220-9699-f3e7c73ea8d1.png' width = 500>
</p>
<p float="left">
<img src = 'https://user-images.githubusercontent.com/62933155/190900759-aa1d5c8e-ada3-4b51-b375-6ae6a12d5dcc.png' width = 500>
<img src = 'https://user-images.githubusercontent.com/62933155/190900768-805918dd-7079-40ca-868a-bd2f3187184d.png' width = 500>
</p>

## Contributing

Since this project was built during Hack the Mountains 3.0, we would be seldomly improving this product. However we encourage you to contribute this repo and take it more as a tutorial of how this project was built. If you have any suggesstions or want to make some changes, feel free to create a PR or an issue.

## License

This project is MIT [Licensed](./LICENSE)

## About Us -->

We are The Powerpuff Rangers (formerly The Powerpuff Boys)

<img src = '.github/images/powerpuff.png'>
