# Countries of the World: A Simple Example

This project is a web scraping application that retrieves information about all the countries in the world from a single web page. The application uses Python with the requests, pandas, and BeautifulSoup libraries to scrape the data.

## Installation

To run the project locally, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python libraries by running the following command:

   ```
   pip install requests pandas beautifulsoup4
   ```

## Usage

1. Open the project in your preferred Python editor or IDE.
2. Open the `main.py` file and ensure that the necessary libraries are imported at the beginning of the file.
3. Modify the code if needed, such as adjusting the URL if you want to scrape a different webpage.
4. Run the `main.py` script, and the program will make a request to the specified webpage, parse the HTML, and print out information about each country.
5. After the scraping process completes, a DataFrame containing the country details will be displayed in the console.

## Acknowledgements

The project uses the following libraries:

- [requests](https://docs.python-requests.org/en/latest/): For making HTTP requests to retrieve the webpage's content.
- [pandas](https://pandas.pydata.org/): For creating and manipulating the DataFrame that stores the scraped data.
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/): For parsing the HTML content and extracting relevant information.

The website used for scraping in this project is [ScrapeThisSite](https://www.scrapethissite.com/pages/simple/), which provides a simple example page listing information about all the countries in the world.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to your needs.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

---

You can customize this README file according to your project's specific details and add any additional sections that might be relevant.
