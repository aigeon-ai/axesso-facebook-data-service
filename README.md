markdown
# Axesso - Facebook Data Service MCP Server

## Overview

The `axesso-facebook-data-service` MCP server is designed to provide seamless access to Facebook (Meta) data such as posts, comments, and replies. This service enables real-time data retrieval, ensuring that users receive the most current information available on the social media platform without any intermediate databases.

## What It Does

This server offers a comprehensive suite of tools for extracting various types of data from Facebook pages. Whether you need to query posts, gather comments, or fetch detailed post information, this service facilitates efficient data access with a straightforward interface.

## Key Features

- **Real-time Data Access:** Retrieve up-to-date information directly from Facebook.
- **No Intermediate Database:** Ensures data freshness by eliminating the need for database caching.
- **Customizable Plans:** Tailored solutions are available to meet specific user requirements.

## Toolset

The server provides a variety of tools, each designed for specific data retrieval tasks:

### Posts

- **Posts:** Query posts by providing a page URL. Supports pagination via the "nextUrl" field.
- **Posts V2:** Retrieve posts from a specified Facebook page using the "pageId" parameter. Pagination is supported through the "cursor" field, and the "startTime" parameter allows filtering posts by date.

### Post Details

- **Post Details:** Fetch detailed information about a single post, including videos and reels.

### Comments

- **Comments:** Retrieve comments for a specific post using the "feedbackId". Pagination is available with the "after" parameter.

### Page Information

- **Page Info:** Access detailed information about a Facebook page, such as follower count and more.

### Reels

- **Reels:** Fetch reels for a given profile, with pagination supported via the "cursor" field.

### Replies

- **Replies:** Retrieve replies to comments using the "feedbackId". Supports pagination through the "after" parameter.

### Hashtag Search (Deprecated)

- **Hashtag Search:** Search for public posts containing a specific hashtag. Note that due to restrictions, only the first found post is returned.

### Healthcheck

- **Healthcheck:** Monitor the health status of the Axesso Facebook service.

## Getting Started

To begin using the `axesso-facebook-data-service`, you need to subscribe to a plan that suits your needs. After subscribing, you can make your first API call and explore the documentation and resources provided to integrate the service into your application or workflow.

## Conclusion

The `axesso-facebook-data-service` MCP server is an efficient tool for developers and businesses looking to harness the power of Facebook data. With its real-time capabilities and diverse toolset, it offers significant advantages in accessing and utilizing social media data effectively.