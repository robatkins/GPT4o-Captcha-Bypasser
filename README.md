# GPT4o Captcha Bypass

This project is a CLI tool for testing various types of captchas including puzzle, text, complicated text, and reCAPTCHA using Python and Selenium. The tool also uses OpenAI GPT-4 to help solve the captchas.

## Prerequisites

- Python 3.7+
- Firefox Browser
- Imgur Account for uploading images
- OpenAI Account for GPT-4 API

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/robatkins/GPT4o-Captcha-Bypasser
   cd gpt4-captcha-bypass
   ```

2. Install the required Python packages:

   ```sh
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory of your project and add your Imgur Client ID and OpenAI API Key:

   ```sh
   echo "OPENAI_API_KEY=sk-your-openai-api-key" > .env
   echo "IMGUR_CLIENT_ID=your-imgur-client-id" >> .env
   ```

4. Make sure you have the `geckodriver` for Firefox installed. You can install it using `webdriver-manager`:

   ```sh
   pip install webdriver-manager
   ```

## Usage

Run the CLI tool with the desired captcha type:

```sh
python main.py [captcha_type]
```

where `[captcha_type]` can be one of: `puzzle`, `text`, `complicated_text`, `recaptcha`.

Example:

```sh
python main.py text
```

## Captcha Types

- `text`: Tests simple text captchas.
- `complicated_text`: Tests complicated text captchas.
- `recaptcha`: Tests Google's reCAPTCHA.
- `puzzle`: Tests puzzle captchas.

### Text

<img width="615" alt="image" src="https://github.com/user-attachments/assets/840a58c5-4a5b-47fe-89a3-845063585907">

### Complicated Text

<img width="382" alt="image" src="https://github.com/user-attachments/assets/409e2386-2db5-4af7-9150-f374f7ee4ac6">

## Recaptcha and Slider

Recaptcha and Slider may be bypassed in average 10 attempts.

<img width="407" alt="image" src="https://github.com/user-attachments/assets/1972322b-fd6b-4641-8cdf-a74e53311de7">

<img width="283" alt="image" src="https://github.com/user-attachments/assets/fe7c5c5b-e8d3-4f03-9c94-e778c849640a">



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/usestrix/cli.svg?style=for-the-badge

[contributors-url]: https://github.com/aydinnyunus/gpt4-captcha-bypass/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/usestrix/cli.svg?style=for-the-badge

[forks-url]: https://github.com/aydinnyunus/gpt4-captcha-bypass/network/members

[stars-shield]: https://img.shields.io/github/stars/usestrix/cli?style=for-the-badge

[stars-url]: https://github.com/aydinnyunus/gpt4-captcha-bypass/stargazers

[issues-shield]: https://img.shields.io/github/issues/usestrix/cli.svg?style=for-the-badge

[issues-url]: https://github.com/aydinnyunus/gpt4-captcha-bypass/issues

[license-shield]: https://img.shields.io/github/license/usestrix/cli.svg?style=for-the-badge

[license-url]: https://github.com/aydinnyunus/gpt4-captcha-bypass/blob/master/LICENSE.txt

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

[linkedin-url]: https://linkedin.com/in/aydinnyunus

[product-screenshot]: data/images/base_command.png

[latest-release]: https://github.com/aydinnyunus/gpt4-captcha-bypass/releases
