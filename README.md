# MeteorShowerProject
 
## Meteor shower predictions for a certain city using machine learning

This project uses Jupiter Notebooks, Python libraries such as pandas and numpy, and machine learning to predict meteor showers. This is my attempt to play with Python to analyze data and make predictions. Data has been acquired from NASA, Wikipedia, and other open sources. 

### Intro

Comets, Moon phases, and place on Earth influence the observation of the meteor showers.

Meteoroids can come from comets, asteroids, moons, and planets - here, the focus is on meteoroids that come from 4 popular comets.

### Four Comets

1. Comet Thatcher

Comet Thatcher was first discovered in 1861. It takes 415.5 years for comet Thatcher to orbit the sun.
The debris from this comet creates the Lyrids meteor shower each April. The first recorded sighting of the Lyrids meteor shower goes back to 687 BC.
The Lyrids meteor shower appears to come from the direction of the constellation Lyra. But the comet and meteor shower don't actually originate from this constellation.

2. Comet Halley

Comet Halley was first discovered in 1531. However, only in 1705 was it discovered that the comet sighted in 1531, 1607, and 1682 was the same comet.
Comet Halley takes 76 years to orbit the sun. The debris from this comet creates the Eta Aquarids meteor shower each May and the Orionids meteor shower each October.
The Eta Aquarids meteor shower appears to come from the direction of the constellation Aquarius. The Orionids meteor shower appears to come from the direction of the constellation Orion.

3. Comet Swift-Tuttle

Comet Swift-Tuttle was first discovered in 1862. This comet takes 133 years to orbit the sun. Debris from this comet creates the Perseids meteor shower each August.
It wasn't until 1865 that it was understood that this meteor shower originated from Comet Swift-Tuttle. The Perseids meteor shower appears to come from the direction of the constellation Perseus.

4. Comet Tempel-Tuttle

Comet Tempel-Tuttle was independently discovered twice, in 1865 and 1866. This comet takes 33 years to orbit the sun. Debris from this comet creates the Leonids meteor shower each November.
Every 33 years, the Leonids meteor shower becomes a meteor storm. A meteor storm is when there are at least 1,000 meteors per hour. The Leonids meteor shower appears to come from the direction of the constellation Leo.

### Moon Phases

As the Moon orbits Earth, and Earth orbits the sun, different amounts of sunlight are reflected off the Moon to Earth. Each month, the Moon cycles through different phases. The phases are basically the names we apply to how much sunlight we see reflecting off certain parts of the Moon.

These are the phases of the Moon:

    New Moon: Around the 15th of the month
    Waxing crescent
    First quarter: Around the 23rd of the month
    Waxing gibbous
    Full Moon: Around the 1st of the month
    Waning gibbous
    Third quarter: Around the 10th of the month
    Waning crescent

New Moon, first quarter, full Moon, and third quarter are the most frequently tracked phases. The phases cycle every 29 days, so the exact dates depend on the number of days in the month.

### Data

Data has been gathered from:
- moonphases.csv - This file contains the Moon phases for every day of 2021. Data acquired from timeanddate.com.
- meteorshowers.csv - This file contains data for each of the five meteor showers described earlier. Data includes their preferred viewing month, the months when they're visible, and the preferred hemisphere for viewing. Data acquired from NASA.
- constellations.csv - This file contains data for the four constellations that are radiants for the five meteor showers. Data includes the latitudes for which they're visible and the month for the best viewing. Data acquired from Wikipedia.
- cities.csv - This file contains a list of country capitals and their associated latitudes. Data acquired from Wikipedia.

