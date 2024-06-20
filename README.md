# Qurious: A Full Stack SaaS Platform for Creative Content Creation

Welcome to Qurious, a groundbreaking Full Stack Software as a Service (SaaS) platform designed to redefine the landscape of creative content creation. This project leverages state-of-the-art technologies and AI tools to provide an integrated and seamless experience for users across various domains such as content creation, education, multimedia production, and digital marketing.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Subscription and Billing](#subscription-and-billing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Qurious is a visionary platform that integrates cutting-edge Artificial Intelligence (AI) tools for generating text, code, video, music, and images. It addresses the challenges of accessing diverse creative tools across fragmented workflows, offering users a seamless and efficient solution for content creation.

## Features

- **AI-Driven Content Generation**: Utilize advanced AI models for natural language understanding and few-shot learning, inspired by pivotal works like "BERT" and "Language Models are Few-Shot Learners."
- **Integrated Toolset**: Access a comprehensive suite of tools for generating text, code, video, music, and images in one place.
- **Next.js 13 App Router**: Efficient client-side routing for optimized user navigation.
- **Stripe Subscription System**: Streamlined billing processes for a frictionless subscriber experience.
- **User-Friendly Interface**: Built with React and Tailwind for a modern and responsive user interface.
- **Secure and Scalable Backend**: Leveraging Prisma, MySQL, and Clerk for robust data management and authentication.

## Technologies Used

- **Frontend**: Next.js 13, React, Tailwind CSS
- **Backend**: Prisma, MySQL
- **Authentication**: Clerk
- **Payment Processing**: Stripe
- **Font Optimization**: next/font for automatic optimization and loading of Inter, a custom Google Font

## Getting Started

This is a Next.js project bootstrapped with `create-next-app`.

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Installation

Follow these steps to set up the Qurious platform on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Neerpatel25/qurious.git
    cd qurious
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the root directory and add the necessary environment variables:
    ```env
    DATABASE_URL=your-database-url
    STRIPE_SECRET_KEY=your-stripe-secret-key
    CLERK_API_KEY=your-clerk-api-key
    ```

4. **Run database migrations**:
    ```bash
    npx prisma migrate dev
    ```

5. **Start the development server**:
    ```bash
    npm run dev
    ```

## Usage

Once the development server is running, you can access the platform at [http://localhost:3000](http://localhost:3000). From here, you can explore the various AI tools for content creation, manage your subscription, and enjoy a seamless creative experience.

## Subscription and Billing

Qurious uses Stripe to manage subscriptions and billing. To subscribe, follow these steps:

1. Navigate to the subscription page.
2. Choose a subscription plan that fits your needs.
3. Enter your payment details via the secure Stripe checkout.

Your subscription will be activated immediately, granting you access to the full suite of Qurious tools and features.

## Contributing

We welcome contributions to the Qurious project! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add your commit message"
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact us at [support@qurious.com](mailto:support@qurious.com).

Thank you for using Qurious! We hope it transforms your creative process and unlocks new dimensions of imagination.

---

*This README was generated to provide a comprehensive overview of the Qurious project. For more details, please refer to the documentation or contact our support team.*
