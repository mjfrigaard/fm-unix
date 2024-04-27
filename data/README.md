---
editor: 
  markdown: 
    wrap: 72
---

# Data Files

## Alan J. Perlis' Epigrams

The `ajperlis_epigrams.txt` file contains a collection of witty
programming and systems design epigrams by Alan J. Perlis.[^ajperlis-epigrams] These
statements cover various topics related to computer programming,
software architecture, and philosophy. The epigrams offer nuggets of
reflective and forward-thinking wisdom that provoke thought on the
complexities of technology, the art of programming, and the interplay
between human cognition and computational logic. This collection is
invaluable for programmers and computer scientists interested in the
cultural and intellectual history of computing.

[^ajperlis-epigrams]: Read the [Wikipedia](https://en.wikipedia.org/wiki/Epigrams_on_Programming) or download the [original PDF](https://iiif.library.cmu.edu/file/Simon_box00075_fld05959_bdl0003_doc0002/Simon_box00075_fld05959_bdl0003_doc0002.pdf).

## Music Videos

The file `music_vids.tsv` is a tab-separated values (TSV) data file that
details some of the most expensive music videos ever produced.[^music-vids] Key
information captured in the file includes:

| Variable       | Description                                                                                   |
|----------------|-----------------------------------------------------------------------------------------------|
| `rank`         | The music video's position based on the production cost.                                      |
| `title`        | The name of the music video.                                                                  |
| `artists`      | The artist(s) who performed the song.                                                         |
| `director`     | The director of the music video.                                                              |
| `year`         | The year the music video was released.                                                        |
| `cost_nominal` | The production cost at the release time, presented in U.S. dollars.                           |
| `cost_adj`     | The production cost adjusted to current values for inflation, also presented in U.S. dollars. |

[^music-vids]: From the [List of most expensive music videos on Wikipedia](https://en.wikipedia.org/wiki/List_of_most_expensive_music_videos)

## Passwords

The files `pwrds.csv` and `pwrds.tsv`are CSV (comma-separated values)
files containing a comprehensive list of commonly used passwords and
attributes.[^pwrds] The dataset contains information about passwords' strength,
popularity rank, and resilience against online attacks. The dataset includes the following variables:

| Variable           | Description                                                                                                                         |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| **`password`**     | The actual password text.                                                                                                           |
| **`rank`**         | Numerical ranking based on the frequency or commonness of the password.                                                             |
| **`strength`**     | A numerical value representing the estimated password strength, where higher numbers indicate stronger passwords.                   |
| **`online_crack`** | An estimate of how long it would take to crack this password using online attack methods, expressed in units from seconds to years. |

[^pwrds]: The original
data comes from [Information is
Beautiful](https://docs.google.com/spreadsheets/d/1cz7TDhm0ebVpySqbTvrHrD3WpxeyE4hLZtifWSnoNTQ/edit#gid=16)

## Roxanne

The file `roxanne.txt` contains the lyrics to the song "Roxanne" by The
Police.[^roxanne] The structure of the lyrics emphasizes the repeated refrain,
"You don't have to put on the red light," which is a metaphor for not
having to engage in prostitution.

[^roxanne]: Read more about Roxanne (The Police song)
on the [Wikipedia page.](https://en.wikipedia.org/wiki/Roxanne_(The_Police_song))

## Trees

The file `trees.txt` is a tab-separated value (TSV) document that
catalogs some of the tallest trees in the world, providing detailed
information on each tree listed.[^trees] This file is structured to provide a
quick reference to some of the most significant trees around the world,
highlighting their impressive heights and the diverse locations they
inhabit. Each entry in the dataset includes the following fields:

| Variable        | Description                                                 |
|-----------------|-------------------------------------------------------------|
| **`tree`**      | Identifier or common name used for the tree.                |
| **`species`**   | Scientific name of the tree species.                        |
| **`class`**     | Biological classification (e.g., Conifer, Flowering plant). |
| **`ht_meters`** | Height of the tree in meters.                               |
| **`ht_feet`**   | Height of the tree in feet.                                 |
| **`location`**  | Specific location where the tree is found.                  |
| **`continent`** | Continent on which the tree is located.                     |
| **`name`**      | The colloquial name given to the tree, if applicable.       |

[^trees]: From the [List of tallest trees on Wikipedia.](https://en.wikipedia.org/wiki/List_of_tallest_trees)

## Video Game Hall of Fame

The file `vg_hof.tsv` is a tab-separated values (TSV) document that
contains a list of video games inducted into a hall of fame over several
years, from 2015 to 2024.[^vg_hof] Each record in the dataset includes the year
of induction, the game's name, the developer, and the year the game was
initially released.

The fields detailed in the dataset are:

| Variable            | Description                                           |
|---------------------|-------------------------------------------------------|
| **`year`**          | The year the game was inducted into the hall of fame. |
| **`game`**          | The name of the video game.                           |
| **`developer`**     | The company or individual who developed the game.     |
| **`year_released`** | The original year of the game's release.              |

[^vg_hof]: From the [World Video Game Hall of Fame Wikipedia page.](https://en.wikipedia.org/wiki/World_Video_Game_Hall_of_Fame)

## World Health Organization Tuberculosis 

The files `who_tb_data.tsv` and `who_tb_data.txt` are tab-separated
values (TSV) documents that provides tuberculosis (TB) case data
alongside population figures for selected countries over specific years,
as reported by the World Health Organization (WHO).[^who_tb_data]

The dataset includes the following fields:

| Variable      | Description                                                                                                                                                                                     |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **`country`** | The name of the country where the data was recorded.                                                                                                                                            |
| **`year`**    | The year in which the data was collected.                                                                                                                                                       |
| **`type`**    | A descriptor of the data type, which can be either 'cases' indicating the number of tuberculosis cases reported, or 'population' representing the total population of the country in that year. |
| **`count`**   | The numerical value corresponding to the type, either the number of TB cases or the population size.                                                                                            |

[^who_tb_data]: From the [WHO global tuberculosis programme](https://www.who.int/teams/global-tuberculosis-programme/data#csv_files)
## Wu-Tang Clan 

`wu_tang.dat`, `wu_tang.txt`, and `wu_tang.csv` are data files that
provides the stage names and real names of the members of the Wu-Tang
Clan, a highly influential hip-hop group.[^wu-tang] Each entry in the dataset
correlates a member's popularly known stage name with their legal name,
offering insight into the identities behind the personas. The data
structure includes two main fields:

| Variable     | Description                                |
|--------------|--------------------------------------------|
| **`Member`** | The stage name of the Wu-Tang Clan member. |
| **`Name`**   | The real name of the member.               |

[^wu-tang]: From the [Wu-Tang Clan Wikipedia page](https://en.wikipedia.org/wiki/Wu-Tang_Clan).