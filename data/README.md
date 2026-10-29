# Data

`netflix_titles.csv`: one row per title in the Netflix catalogue, collected in September 2021 (8,807 rows).
Source: *Netflix Movies and TV Shows*, a public dataset published on Kaggle.

| Column | Description |
|---|---|
| `show_id` | Unique title identifier |
| `type` | `Movie` or `TV Show` |
| `title` | Title name |
| `director` | Director(s), comma-separated; missing for about 30% of titles |
| `cast` | Main cast, comma-separated |
| `country` | Producing country or countries, comma-separated |
| `date_added` | Date the title was added to Netflix |
| `release_year` | Original release year |
| `rating` | Audience rating (TV and MPAA scales) |
| `duration` | Minutes for films, seasons for series |
| `listed_in` | Genres, comma-separated |
| `description` | Short synopsis |

The file is unchanged from the source. All cleaning steps are performed and documented in the notebook.
