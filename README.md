# bot-ixn Attribute

## Overview

The `bot-ixn` attribute is introduced to differentiate content generated by Large Language Models (LLMs) in links.

## Problem

LLMs can produce content that, while coherent, might be unfounded or untrue. When such content appears in search results or is shared on platforms, it can be misleading for users who might assume it's human-generated or factual.

## Proposed: `bot-ixn` Attribute

The `bot-ixn` (short for 'bot interaction') attribute serves as a marker for content generated through interactions with LLMs. By marking links or content with this attribute, platforms, developers, and users can easily identify unedited and untrusted LLM-generated content and handle it appropriately. See this post [here](https://danielsgriffin.com/2023/10/03/highlighting-llm-generated-content-in-search-results-do-we-need-a-new-link-attribute.html).

## Usage

To mark a link as LLM-generated, simply add the `bot-ixn` attribute:

```html
<a rel="bot-ixn" href="link-to-llm-content">Link Text</a>
```

## Styling & Labels

You may also add styling and labels to better inform human readers.

## Contribution

Feedback and contributions are welcome.