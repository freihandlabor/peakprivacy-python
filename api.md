# Api token

Types:

```python
from peakprivacy import ApiTokenValid, ApiTokenNotFoundError
```

Methods:

- <code title="post/ ai/ping">client.chat.<a href="./peakprivacy/resources/chat.py">
  check_api_token</a>() -> <a href="./peakprivacy/types/api_token_valid.py">ApiTokenValid</a></code>

# Models

Types:

```python
from peakprivacy import ModelList, Model
```

Methods:

- <code title="post /completions">client.models.<a href="./peakprivacy/resources/models.py">
  list</a>() -> <a href="./peakprivacy/types/model_list.py">ModelList</a></code>

# Completions

Types:

```python
from peakprivacy import ChatCompletion, Choice, ChatCompletionMessage, CompletionUsage
```

Methods:

- <code title="post /completions">client.chat.completions.<a href="./peakprivacy/resources/completions.py">
  create</a>(\*\*<a href="./peakprivacy/resources/completions.py">
  params</a>) -> <a href="./peakprivacy/types/chat_completion.py">ChatCompletion</a></code>

# Completions Stream

Types:

```python
from peakprivacy import Stream, ChatCompletionChunk, StreamChoice, ChoiceDelta
```

Methods:

- <code title="post /completions">client.chat.completions.<a href="./peakprivacy/resources/completions.py">
  create</a>(\*\*<a href="./peakprivacy/resources/completions.py">
  params</a>) -> <a href="./peakprivacy/types/stream.py">Stream</a></code>
