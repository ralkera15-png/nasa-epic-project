# nasa-epic-project
# NASA EPIC Photo Explorer

This program uses NASA's EPIC API to retrieve Earth photos for a selected date. It explores mission telemetry by displaying photo counts and information about Earth's images.

## How it works

- **retrieve_epic_photos:** Retrieves NASA EPIC photo data for a selected date and returns a list of dictionaries.
- **count_photos:** Counts the number of photos returned by the API.
- **display_photo_info:** Displays information about the first photo, including its date, image identifier, and centroid coordinates.

## How to run

1. Install requests: `pip install requests`
2. Run: `python epic_photo_explorer.py`
3. Uses `DEMO_KEY` by default. Replace it with your own NASA API key from https://api.nasa.gov for higher rate limits.
