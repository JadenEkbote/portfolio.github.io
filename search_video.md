## Search Operation in twitch
Searching in twitch may involve searching for a paticular stream/video or a channel. The algorithm that twitch uses for 
### Concepts Used:
- **Radix Tree**: Provides efficient indexing and fast lookup for video titles, descriptions, and tags. This data structure supports quick searches and autocomplete functionality by storing each character of the search terms in nodes.
- **A * with priority queue**: Ranks search results based on relevance. This algorithm considers multiple factors such as title matches, view count, likes, and user engagement to deliver the most pertinent results to the user.
