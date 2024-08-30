
# Voice Cloning with Coqui XTTS-V2 in Google Colab

This notebook demonstrates how to use the Coqui XTTS-V2 model for voice cloning within Google Colab. It provides a user-friendly interface and allows for customization of parameters like the input text, speaker audio, and output language.

## Features

* **Voice Cloning:** Clone voices from audio samples using the powerful XTTS-V2 model.
* **Multilingual Support:** Generate speech in various languages including English, Spanish, French, German, and more.
* **Google Colab Integration:** Runs seamlessly in Google Colab with GPU acceleration for optimal performance.
* **Easy-to-Use Interface:** Simple and intuitive parameters for text input, speaker audio selection, and output customization.

## How to Use

1. **Enable GPU Acceleration:** In Google Colab, navigate to "Runtime" -> "Change runtime type" and select "GPU" as the hardware accelerator.
2. **Mount Google Drive:** Run the provided code cell to mount your Google Drive and access your audio samples.
3. **Provide Input:**
   * **Text:** Enter the text you want to be synthesized in the designated field.
   * **Speaker Audio Path:** Specify the path to the audio file containing the voice you want to clone. This file should be in your mounted Google Drive.
   * **Output Folder:** Choose the directory in your Google Drive where the synthesized audio will be saved.
   * **Language:** Select the language of the speaker from the dropdown menu.
4. **Run the Code:** Execute the main code cell to initiate the voice cloning and speech synthesis process.
5. **Access Output:** The generated audio file will be saved in the specified output folder in your Google Drive.

## Requirements

* **Google Colab Account:** You need a Google Colab account to run this notebook.
* **GPU Enabled:** Ensure that GPU acceleration is enabled in your Colab runtime settings.

## Installation

The necessary libraries will be installed automatically when you run the first code cell in the notebook.

## Important Notes

* The quality of the voice cloning depends on the quality and length of the speaker audio provided.
* Experiment with different parameters to achieve the desired voice and speech output.

## Disclaimer

This notebook is intended for educational and experimental purposes. The use of voice cloning technology should be ethical and responsible.


<hr>  
By:
<div align="center">
    <img src="https://i.ibb.co/DVCbGKp/1694197931620-e-1700697600-v-beta-t-V9i-TOhf-Pk-Vf-Bh4-QQxt-QPBVvs-Uyi-c-Emms-Qlh9d-C8p-UA.jpg" alt="hero" style="width: 200px; height: auto; border-radius: 50%;">
    <h3>Andres Castaño</h3>
    <p>Data Scientist | Geological Engineer</p>
    <a href="https://github.com/FeRsOmBrA" target="_blank">
        <img alt="GitHub" src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github" />
    </a>
    <a href="https://www.linkedin.com/in/ferney-castano/" target="_blank">
        <img alt="LinkedIn" src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin" />
    </a>
</div>
