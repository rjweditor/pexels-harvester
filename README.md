## Pexels Harvester 

This script allows you to download high-definition (HD) resolution videos from Pexels using their API.

### Prerequisites

Before using the script, ensure you have:

- Python installed on your machine.
- An API key from Pexels. If you don't have one, sign up on [Pexels](https://www.pexels.com/api/), create an account, and generate an API key.

### Instructions

Follow these steps to use the script:

1. **Clone the Repository or Download the Script**
    - Download the script or clone the repository to your local machine.

2. **Install Required Libraries**
    - Ensure you have the `requests` library installed. If not, you can install it via pip:
    ```bash
    pip install requests
    ```

3. **Add Your API Key**
    - Replace `'YOUR_API_KEY'` in the script with your actual Pexels API key.

4. **Adjust Number of Downloads**
    - You can modify the `per_page` parameter in the `download_hd_resolution_video` function to adjust the number of videos downloaded per query. The default is 5.

5. **Set Search Keyword**
    - Replace `'ADD_KEYWORD_HERE'` with the desired keyword you want to search for on Pexels.

6. **Run the Script**
    - Execute the script using Python:
    ```bash
    python pexels.py
    ```

### Adjusting Number of Downloads

To change the number of downloads per query, adjust the `per_page` parameter in the `download_hd_resolution_video` function. Increase or decrease this value to download more or fewer videos in each search query.

### Adding an API Key

To obtain your API key from Pexels:

1. Sign up or log in to your Pexels account.
2. Navigate to the [Pexels API](https://www.pexels.com/api/) page.
3. Generate an API key.
4. Replace `'YOUR_API_KEY'` in the script with your newly generated API key.

### Adding a Keyword

To search for videos related to a specific keyword:

1. Replace `'ADD_KEYWORD_HERE'` in the script with your desired search keyword.
2. Run the script to fetch and download videos related to that keyword.


