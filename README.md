# paramgaming-bot

paramgaming-bot is a Node.js script designed to interact with the Param Gaming API to fetch tasks, clear them, and claim rewards automatically.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/dante4rt/paramgaming-bot.git
   ```

2. Install dependencies:

   ```bash
   cd paramgaming-bot
   npm install
   ```

3. Create a `.env` file in the root directory and provide the following environment variables:
   - type ```
     vi .env ```
    - The above command will create and open a ```.env``` file, then to edit the file using the ```vi editor```, press ```i``` and add your environment variables.
    
   ```plaintext
   USER_EMAIL=your-email@example.com
   USER_PASSWORD=your-password
   ```
- After adding your environment variables, to save the file, press ```esc```, then type ```:wq``` and press ```enter```.

## Usage

To run the bot, execute the following command:

```bash
npm start
```

The bot will log in to your Param Gaming account, fetch incomplete tasks, clear them, and claim rewards.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
