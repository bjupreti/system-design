# TinyURL

## Rquirements and Goal of the system

## Functional Requirements

1. Given a URL, our service should generate a shorter and unique alias of it or users should be able to pick a custom short link for their URL. This link should be short enough to be easily copied and pasted into applications.
2. When user access a short link, our service should redirect them to the original link.
3. Links will expire after a standard default timespan. Users should be able to specify the expiration time.

## Non-functional Requirements

1. The system should be highly available. This is required because, if our service is down, all the URL and redirections will start failing.
2. URL redirections should happen in real-time with minimal latency.
3. Shortened links should not be guessable (not predictable).

## Extended Requiremens

1. Analytics, e.g., how many times a redirection happened?
2. Our service should also be accessible through REST APIs by other services.
