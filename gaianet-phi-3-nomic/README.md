# A Phi-3-mini-4k node with GaiaNet knowledge

**Step 1:** Install GaiaNet node

```
curl -sSfL 'https://raw.githubusercontent.com/GaiaNet-AI/gaianet-node/main/install.sh' | bash
```

See the [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)

**Step 2:** Init with the Yi-1..5-9B-16K model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/gaianet-phi-3-nomic/config.json
```

**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct)
* [GGUF formatted model](https://huggingface.co/gaianet/Phi-3-mini-4k-instruct-GGUF)