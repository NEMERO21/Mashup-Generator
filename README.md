# Mashup

Mashup is a unique web application designed to provide users with a personalized music mashup experience. By simply searching for an artist, users can create a continuous mix of their songs sourced from YouTube. The platform offers customization options, allowing users to specify parameters such as the number of songs, duration of each song, and provide their email for delivery of the mashup.

## Functionality

Mashup operates on the following principles:

1. **Artist Search**: Users input the name of an artist they wish to create a mashup for.

2. **Customization**: Users can specify parameters such as the number of songs and duration of each song to be included in the mashup.

3. **Processing**: The website downloads videos of the specified songs from YouTube, converts them to audio format, trims the audio to the desired duration, and then mixes them together seamlessly to create a cohesive mashup.

4. **Delivery**: Upon completion, the resulting mashup is packaged into a Zip file and sent to the user's provided email address.

## Usage
1. Open Mashup in your web browser.

2. Enter the name of the artist you want to create a mashup for.

3. Specify the desired parameters such as the number of songs and duration per song.

4. Provide your email address for delivery of the mashup.

5. Click on the "Create Mashup" button.

6. Wait for the mashup to be processed and delivered to your email.

## Dependencies

The website utilizes the following packages and technologies:

- **pytube**: A Python library for downloading YouTube videos.
- **moviepy**: A Python library for video editing tasks such as trimming and merging.
- **ffmpeg**: A multimedia framework for handling various audio and video processing tasks.
- **youtube-search**: A package for searching YouTube videos programmatically.

## Installation and Setup

To set up Mashup locally, follow these steps:

1. Clone the repository from [GitHub](https://github.com/yourusername/mashup).

2. Install the required dependencies using pip:

   ```bash
   pip install pytube moviepy youtube-search

## Contributing

Contributions to Mashup are welcome! If you'd like to contribute, please fork the repository and submit a pull request outlining your proposed changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
