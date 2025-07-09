# Using Semantic Kernel for AI Agents

## 20250709

A few days agao I was contacted by a business owner who is starting an AI agent-powered company. They asked if I was interested even though they don't have anything ready or available right now as they are still raising funds.

I thought this was yet another reason to finally get into actually working with AI Agents.

I use a lot of pre-made AI and have been following genAI for a while. I use [Claude.ai](https://claude.ai/) fairly regularly for basic knowledge checks, have tried no-code platforms for app development, interact frequeintly with conversational AI, and have spent a lot of time dealing with Stable-Diffusion type image generation with Flux and ComfyUI.

I was attending a [Tines](https://www.tines.com/) presentation (it's actually still going on as I type this) and decided to take a look at a few frameworks to see where I can start.

About Semantic Kernel: [https://learn.microsoft.com/en-us/semantic-kernel/overview/]

While you can start with existing examples by cloning the Semantic Kernel repo, I wanted to start from scratch.

I chose C# because I have been doing too much Python lately.

Of course, using any kind of model that doesn't run locally requires paid API calls, so I did put $10 into OpenAI API, but then I'll also have to set up a working webserver to handle the API requests.

But so far, it's a good starting point.

* Set up endpoint with `ngrok` to use for local testing as suggested in the tutorial.
* Used Claude.ai to set up a webserver using C# so I can test client API requests. It will take time to dive more into how the ChatCompletion endpoints work to really get this going, and a better understanding of writing a webserver.
* My time might be better spent working on security solutions :)

```
OpenAI Compatible API Server
This server provides OpenAI-compatible API endpoints:

POST /v1/chat/completions - Chat completions
GET /v1/models - List models
GET /health - Health check
Server is running and ready to accept requests.
```


# Links and References

* [Human-In-The-Loop Example](https://learn.microsoft.com/en-us/semantic-kernel/frameworks/process/examples/example-human-in-loop?pivots=programming-language-csharp)

