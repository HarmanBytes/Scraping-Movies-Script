# Movie Script Scraper

This Python script scrapes movie titles, plots, and scripts from the subslikescript.com website. It collects data for movies starting with the give letter across multiple pages and saves the collected data to a CSV file.

## Website Movie Page Preview
![image](https://github.com/HarmanBytes/Scraping-Movies-Script/assets/105145207/25d87a4b-de5c-41fd-bf5e-7c5d45979cc9)
This screenshot displays the list of movie names for the letter 'V', each of which is a clickable link to access more details.

## Single Movie Data
![image](https://github.com/HarmanBytes/Scraping-Movies-Script/assets/105145207/a1f5fe11-f5d0-4f02-b522-203f2d4706bd)
This screenshot illustrates the detailed information available for a single movie, including its title, plot, and script, accessible by clicking on a movie name.

## Sample Data
Here's a sample of the extracted data stored in a CSV file:
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Title</th>
      <th>Plot</th>
      <th>Script</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>V (2020) - full transcript</td>
      <td>An action-thriller centered on the showdown be...</td>
      <td>"Lord Supreme, our Protector"\n"Stealer of our...</td>
    </tr>
    <tr>
      <th>1</th>
      <td>V (1983) - full transcript</td>
      <td>Aliens pretending to be friendly come to Earth...</td>
      <td>Translation and subtitles by\nPEPPER &amp; LALASPA...</td>
    </tr>
    <tr>
      <th>2</th>
      <td>V avguste 44-go (2001) - full transcript</td>
      <td>The movie is set in Belarus, where a team of c...</td>
      <td>Ministry of culture\nof Republic of Belarus\nB...</td>
    </tr>
    <tr>
      <th>3</th>
      <td>V bolshom gorode (1928) - full transcript</td>
      <td>NaN</td>
      <td>IN THE BIG CITY in 7 parts.\nProduction Belgos...</td>
    </tr>
    <tr>
      <th>4</th>
      <td>V for Vendetta (2005) - full transcript</td>
      <td>Tells the story of Evey Hammond and her unlike...</td>
      <td>ingat, ingat\nTanggal 5 November\nPengkhianata...</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>578</th>
      <td>Vuxna människor (1999) - full transcript</td>
      <td>Frank leads a respectable yuppie life working ...</td>
      <td>- How long have you been married?\n- Nearly th...</td>
    </tr>
    <tr>
      <th>579</th>
      <td>Výbuch bude v pet (1984) - full transcript</td>
      <td>Ludvik is a budding scientist who seems that a...</td>
      <td>Central Film Rental Office Presents\nThe Explo...</td>
    </tr>
    <tr>
      <th>580</th>
      <td>Vysota (1957) - full transcript</td>
      <td>NaN</td>
      <td>Mosfilm Studios\nTHE HEIGHT\nBased upon a nove...</td>
    </tr>
    <tr>
      <th>581</th>
      <td>Vyssí princip (1960) - full transcript</td>
      <td>The story of High school in Czechoslovakia dur...</td>
      <td>Order\nAssassination of S Obergruppenführer\nT...</td>
    </tr>
    <tr>
      <th>582</th>
      <td>Vyyti zamuzh za kapitana (1985) - full transcript</td>
      <td>Captain Alexander Blinov goes on vacation and ...</td>
      <td>Comrade\n- Elena Pavlovna, please. - Yes...\n-...</td>
    </tr>
  </tbody>
</table>

##

## Installation

To use this script, you need to have Python installed on your system. You also need to install the required libraries by running:

```
pip install pandas numpy beautifulsoup4 requests tqdm
```

## Usage

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/movie-script-scraper.git
```

2. Navigate to the project directory:

```
cd movie-script-scraper
```

3. Run the script:

```
python script.py
```

The script will start scraping movie data and save it to a file named `movies_scripts.csv` in the project directory.

## Note
- This script is intended for educational purposes and should be used responsibly.
- subslikescript.com may have usage restrictions or terms of service that you should review before scraping data from their website.
