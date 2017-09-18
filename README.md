# HumIt
You hum a song, and nobody knows what you're trying to sing.
Have you ever remembered a song which you don't know the name of, but know the tune to? Well look no further, Hummit is here for you! Inspired by Shazam, we thought of a new way to intelligently search for songs by the way they sound; by converting frequencies into actual, musical notes.

## Installation
Download the entire project and run the hum_pdp.exe. The application will open and will run you through the entire process.

## What does it do?
While Shazam and other big companies rely on huge databases of audio data files, we rely on simple arrays that contain these musical notes that can be compared with easily and more efficiently. Essentially, we're comparing a dataset of values which are frequencies with the frequencies of an actual song that exist in our database. We can use Microsoft Azure Bot Service for Cortana so that discovering a new song is more user-friendly.

## How did we build it?
We built a Windows-based app that uses Java and Javascript as the main programming languages. In our algorithm, we apply a Fast Fourier Transform at a specific rate to find out the frequency of human pitch per frame. Using that, we generate musical notes. These musical notes that have been detected are compared with the actual musical notes in our database. Once the application guesses the song, the user has the option of buying the song using Bitcoin from websites such as HMV or iTunes. This is done using the CoinBase API to exchange money to pay for the songs.
