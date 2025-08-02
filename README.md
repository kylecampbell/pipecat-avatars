# Pipecat AI Avatar Agents

This is an example of a AI avatars that use the Pipecat SDK to create an AI agent that can be used in a Daily room.

## Installation

```console
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Setup

In this project's directory, run the following command to copy the `.env.example` file to `.env`:

```console
cp .env.example .env
```

Edit the `.env` file with your own values.

### OpenAI - for STT, LLM, and TTS

Visit https://platform.openai.com to get your `OPENAI_API_KEY`.

### Tavus - for avatar

Visit https://tavus.io to get your `TAVUS_API_KEY` and `TAVUS_REPLICA_ID`.

OR

### HeyGen - for avatar

Visit https://heygen.com to get your `HEYGEN_API_KEY`.

## Usage

Run the following command to start the agent:
```console
python avatar_tavus.py
or
python avatar_heygen.py
```

Then, from the logs in above, find and click on or copy the `http://localhost:7860/client` and paste it into your browser, or just go there.


## References

- [Pipecat AI Tavus Documentation](https://docs.pipecat.ai/server/services/video/tavus)
- [Pipecat AI GitHub Tavus Example](https://github.com/pipecat-ai/pipecat/blob/main/examples/foundational/21a-tavus-video-service.py)
- [Pipecat AI GitHub HeyGen Example](https://github.com/pipecat-ai/pipecat/blob/main/examples/foundational/43a-heygen-video-service.py)
