# SealNotes

SealNotes is an end-to-end encrypted web-based notepad that stores and manages your notes. 

## Features

- **End-to-End Encryption:** Your text is encrypted using AES-256 before being stored on our servers, and even the name of your notepad is securely hashed before being saved in our database.
  
- **Rich Text Support:** Create and manage notes with formatting options like bold, italics, and code.

- **No Account Required:** Access your notes using a unique URL and password combination.

- **Cross-Platform Access:** Access your secure notes from any device with an internet connection.

- **Lightweight and Minimalist UI:** Enjoy a clean, responsive interface for distraction-free note-taking.


## Usage

- Visit [https://sealnotes.com/](https://sealnotes.com/)
  
- Create a new note by entering a unique name for the note’s URL.

- Set a strong password for encryption.

- Write or paste your text into the note editor.

- Click "Save" to encrypt and store your note.

- To access a saved note, enter the URL and password.

## Security

- **Encryption:** All data is encrypted client-side using AES-256. Only the encrypted data is stored on the server.

- **Privacy:** We do not store or have access to your passwords. Without the correct password, notes cannot be decrypted.

- **No Tracking:** Sealnotes does not track user activity or store unnecessary metadata.

## Local Setup

- Clone the repo.

```
git clone https://github.com/harshsbhat/sealnotes.git
cd sealnotes
```

- Install dependencies:

```
pnpm install
```

- Create a `.env` file:

```
cp .env.example .env
```

- Create a Redis database with Upstash ( Upstash offers a serverless Redis database with a generous free tier of up to 10,000 requests per day. That's more than enough.)  Add the following environment variables:

```
UPSTASH_REDIS_REST_URL=""
UPSTASH_REDIS_REST_TOKEN=""
```

- Run the project: 

```
pnpm dev
```

## License

This project is licensed under the [MIT License](https://github.com/harshsbhat/sealnotes?tab=MIT-1-ov-file).

## Support

For support or inquiries, please contact us at <a href="mailto:harsh121102@gmail.com">harsh121102@gmail.com</a>


