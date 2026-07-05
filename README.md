# PubSubHub

A backend service that integrates with the **YouTube Data API** and **PubSubHubbub (WebSub)** to receive real-time notifications whenever subscribed YouTube channels publish new videos. The service processes webhook events, retrieves video metadata, and synchronizes the content with another application.

## Features

* Subscribe to YouTube channels using the PubSubHubbub (WebSub) protocol.
* Receive real-time webhook notifications for newly uploaded videos.
* Fetch video details using the YouTube Data API.
* Automatically synchronize videos with an external application.
* Eliminate the need for periodic polling.
* Scalable and event-driven architecture.

## How It Works

1. Subscribe to one or more YouTube channels.
2. Receive webhook notifications when a subscribed channel uploads a new video.
3. Validate and process the webhook request.
4. Retrieve the video's metadata from the YouTube Data API.
5. Push the processed data to the target application.

## Tech Stack

* Node.js
* NestJS
* YouTube Data API v3
* PubSubHubbub (WebSub)
* REST API

## Use Cases

* Content aggregation platforms
* Video management systems
* News and media applications
* Creator dashboards
* Automated content synchronization


