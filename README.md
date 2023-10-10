# PW Generator - Powerful Password Generator

PW Generator is a powerful and user-friendly password generator designed to generate strong and secure passwords effortlessly. This project aims to provide a reliable solution for creating robust passwords to enhance your online security.

## Why choose this password generator?

This password generator is a simple frontend that is easy to audit and use. Unlike other password generators, you can see all the code in the hosted website, and there are no tracking or backend calls. Your passwords are generated in your browser, ensuring maximum security and privacy.

By using this password generator, you can create strong and secure passwords effortlessly, customized to your requirements. With features such as the option to include special characters and automatic password selection, you can enhance your online security and protect your sensitive data.

Remember to use generated passwords responsibly and follow best practices for password management.

## Features

- Customize password length according to your requirements.
- Option to include special characters for added complexity.
- Simple and intuitive interface for ease of use.
- Passwords are generated using a combination of lowercase letters, uppercase letters, numbers, and special characters.
- Automatic password selection for convenience.
- Hosted on `api.wpp.sh` for reliable access.

## Usage Example

To generate a password programmatically using SecureKey, you can make an API call to the following endpoint:

GET https://api.wpp.sh/password?length=12&specialChars=true

This example request generates a password with a length of 12 characters, including special characters. The response will contain the generated password as a JSON object:

```json
{
  "password": "Ex@mpl3P@ssw0rd"
}
```

You can then use the generated password in your application or service for secure authentication and data protection.

Remember to use generated passwords responsibly and follow best practices for password management.
