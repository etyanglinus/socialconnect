# README for SocialConnect

SocialConnect is a social media platform that allows users to create accounts, post text and images, follow other users, and engage with content. The platform will soon integrate M-Pesa payment features for donations, tipping, sponsored posts, transfers, and group fundraisers.
Features:
# Current Features:

    User Accounts:
        Users can create accounts, log in, and manage their profiles.
        Profile information includes email, bio, and profile pictures.

    Post Feeds:
        Users can create posts with text and images.
        Posts appear on the user's feed and in the feeds of their followers.

    Follow System:
        Users can follow other users to see their posts in the feed.
        A personalized feed is generated based on the users they follow.

    Save Posts:
        Users can save posts they like and return to them later.

# Planned Features (Coming Soon):

    M-Pesa Integration:
        Link M-Pesa accounts to profiles for payments, donations, and tipping.
        Securely process M-Pesa payments via the Daraja API.

    Donation Campaigns:
        Users will be able to create donation campaigns and donate to causes.
        Donations can be tracked on campaign pages.

    Tipping:
        Content creators can receive tips from users via M-Pesa.

    Sponsored Posts:
        Businesses will be able to create sponsored posts for paid promotions.
        M-Pesa will be used for payment processing.

    M-Pesa Transfers:
        Users will be able to send and receive M-Pesa transfers directly through the platform.

    Group Fundraisers:
        Groups can organize and collect donations for a cause.

# Technical Details:
# Backend:

    Django for the backend, handling user authentication, database management, and M-Pesa payments.
    MySQL for storing data such as user profiles, posts, donations, and payment transactions.

# Frontend:

    Bootstrap for responsive UI design.
    Forms for interacting with donation campaigns, tipping, and sponsored posts.
    Payment integration via M-Pesa's Daraja API for secure payment processing.

# Security:

    SSL encryption for secure data transmission.
    Tokenization and encryption for M-Pesa payment information