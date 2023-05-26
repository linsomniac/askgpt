# askgpt

A tool to interact with the OpenAI API.

I created it to allow me to create and modify interactions with GPT, including being
able to fill in responses which I *WISH* that chatgpt had asked me and add answers.

For example, I was asking it for a FastAPI server and wanted to provide the database
schema, so with "askgpt" I can add an "- assistant: What is the database schema?" and
then paste in the schema, to get that in the answer context, without creating an
initial, unwieldy prompt that ran up against the token limits.

## Installation

- `pip install openai dotenv`
- Copy "askgpt.env" to "~/.askgpt" and modify by putting in your OpenAI key.

## Quickstart

- Copy "example" and edit it to add a question you want to ask OpenAI.
- Run: `./askgpt <FILENAME>"
- The OpenAI response will be printed.
- Edit "<FILENAME>" again and type in your reply.
- Remember: You can also edit the "assistant" response or create your own assistant
  responses as part of this.
- Repeat.

## OpenAI API Keys

Having a ChatGPT account, even a paid "Plus" account, does not give you access
to an API key.  To get one of those you need to go to https://platform.openai.com/
and put in credit card billing information.  You are billed on a per request basis
(even if you have a ChatGPT Plus account).

Access to GPT-4 is severely limited, even if you have access to it in ChatGPT Plus.
You need to get on a waitlist at https://openai.com/waitlist/gpt-4-api

## License

CC0 1.0 Universal, see LICENSE file for more information.

<!-- vim: ts=4 sw=4 ai et tw=85
-->
