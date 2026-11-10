# NASA EPIC Photo Explorer

NASA EPIC Photo Explorer retrieves Earth photos from NASA's EPIC API for a selected date. It counts the photos available and displays information about the first photo, including its date, image identifier, and centroid coordinates.

## How it works

- **retrieve_epic_photos(api_key, date):** Retrieves NASA EPIC photo data for a specific date and returns a list of dictionaries containing photo information.
- **count_photos(photos):** Counts the number of photos retrieved and returns zero if no photos are available.
- **display_photo_info(photos):** Displays the date, image identifier, and centroid coordinates of the first photo. Handles empty lists without crashing.

## How to run

1. Install requests: `pip install requests`
2. Run: `python epic_photo_explorer.py`
3. Uses `DEMO_KEY` by default. Replace it with your own NASA API key from https://api.nasa.gov for higher rate limits.

## Example

For March 8, 2016, the program retrieved 12 photos and displayed information about the first photo.

## Technologies used

- Python
- Requests library
- NASA EPIC API
