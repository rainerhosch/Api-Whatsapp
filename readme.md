# Whatsapp API Implementation

Hi, this is API Service for Whatsapp basic from <a href="https://github.com/pedroslopez/whatsapp-web.js">whatsapp-web.js</a>

Social Media:

- <a href="#">Instagram</a>
- <a href="#">Tweeter</a>
- <a href="#">Telegram</a>


### How to use?

- Clone or download this repo
- Enter to the project directory
- Edit or Set port server on file app.js
- Run `npm install` for required library
- Run `npm run start`
- Open browser and go to address server `http://localhost:8080`
- Scan QR Code

### Send message to group by <a href="https://github.com/ngekoding">Nur Muhammad</a>

You can send the message to any group by using `chatID` or group `name`, chatID will used if you specify the `id` field in the form, so if you want to send by `name`, only use name.

**Paramaters:**

- `id` (optional if name given): the chat ID
- `name` (optional): group name
- `message`: the message

Here the endpoint: `/send-group-message`

Here the way to get the groups info (including ID & name):

- Send a message to the API number `!groups`
- The API will replying with the groups info
- Use the ID to send a message

### Downloading media by <a href="https://github.com/ngekoding">Nur Muhammad</a>

I add an example to downloading the message media if exists. Please check it in `on message` event!

We use `mime-types` package to get the file extension by it's mimetype, so we can download all of the type of media message.

And we decided (for this example) to use time as the filename, because the media filename is not certain exists.

## Thanks To
- <a href="https://github.com/pedroslopez">pedroslopez</a>
- <a href="https://github.com/ngekoding">Nur Muhammad</a>

## Support Me

You can make a support for this work by <a href="#">RZ OKTAN</a>.
