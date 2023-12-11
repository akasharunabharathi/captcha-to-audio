# captcha-to-audio
An application that is able to decipher text-based CAPTCHA on websites, and make it more accessible for visually impaired users – by converting text-based CAPTCHA into a noise-added, audio-based CAPTCHA that users will still have to decipher to prove that they are human.


### Project Organization:

[/data/samples](/data/samples) contains our dataset.
[captcha2audio.ipynb](captcha2audio.ipynb) contains our entire project, divided into different sections.

### How to run

[captcha2audio.ipynb](captcha2audio.ipynb) contains all the code the user needs to run. We suggest running all cells except the cell which sharpens all images in our dataset.

The neural net only needs to be trained once. After running through the entire file, you only need to run the last cell (Command Line Interface) every time you want to make a prediction.

The CAPTCHA audio output the user should listen to is written to [captchaAudioFinal.wav](captchaAudioFinal.wav) by default.

### Motivation and Impact

We chose this topic to
- Make the Web a more inclusive and accessible space: Since its introduction in 1997, there have been broad concerns that CAPTCHA makes the web inaccessible to differently-abled users. While audio-based CAPTCHA exists on some websites, most websites do not have it. Furthermore, with the introduction of reCAPTCHA, this divide only grows.
- Learn more about artificial neural networks and Optical Character Recognition and thought this project might be a good way to achieve that.

