# Asset Store Readme for szch.me Web

Assets for the szch.me web are organized and served using jsDelivr as the CDN.\
This document outlines the naming conventions and folder structuring for various assets including releases/mixes, news, and visuals.

## Naming Conventions
To ensure consistency and ease of navigation, assets are named following a standardized pattern: `YYYY-MM-DD_title.format`. This facilitates chronological ordering and content identification. Here are key points on naming:

- **General**: Use lowercase letters, hyphens for spaces, and no special characters except for the underscore (_) when necessary.
- **News**: `yyyy-mm-dd_news_title.jpg`
- **Releases/Mixes**: `yyyy-mm-dd_album_or_single_name_or_mix_name.jpg`
- **Visuals**: `yyyy-mm-dd_visual_title.jpg`

When a title exceeds a practical length, abbreviate sensibly while maintaining recognizability.


## Folder Pathing
Assets are categorized into different folders based on their type and date. The conventions for each category are detailed in the table below:

| News page folder pathing | Music page folder pathing      | Visuals page folder pathing |
| ------------------------ | ------------------------------ | --------------------------- |
| ./images/news/2024/01    | ./images/music/_year_/mixes    | ./images/visuals/2016       |
| ./images/news/2024/02    | or                             | ./images/visuals/2017       |
| so forth                 | ./images/music/_year_/releases | so forth                    |

Replace `_year_` with the appropriate year for music-related assets. Ensure that files are placed in the correct folder to maintain a consistent and searchable asset library.

### Examples
- Music release: `./images/music/2024/releases/2024-03-01_examplename_ep.jpg`
- News item: `./images/news/2024/02/2024-02-12_important_announcement.jpg`