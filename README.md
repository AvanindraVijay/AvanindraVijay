@GitHub

import os

from openai import OpenAI

client = OpenAI(base_url="https://api.experientiallabs.ai/v1", api_key=os.environ["EXPLABS_API_KEY"])
response = client.chat.completions.create(
model="gpt-6-astra-pro",
stream=True,
messages=[{"role": "user", "content": "Hello from my product"}],
)

This is my github profile readme make it more attractive and good looking with professional and attractive