# Techfront AI

```
curl 'https://julep-proxy.vercel.app/api' \
  --header 'Authorization: Bearer $YOUR_API_KEY_HERE'
  --data-raw $'{"model":"julep-ai/samantha-1-turbo","prompt":"hello?","temperature":0.6,"max_tokens":140,"best_of":2}' \
  --compressed
```

output

```
{
    "id": "cmpl-32f3c5260fa046ee82f56eef0f6ebd9b",
    "object": "text_completion",
    "created": 1704074104,
    "model": "julep-ai/samantha-1-turbo",
    "choices": [
        {
            "index": 0,
            "text": "\nA number of our staff members are trained to provide services that address the unique needs of individuals with disabilities. This may include a variety of accommodations designed to help you access our services more easily. These accommodations can range from the use of assistive technology, to providing materials in alternate formats, to modifications in the physical environment of our offices.\n\nHow do I know if I'm eligible for these services?\nYou may be eligible for these services if you have a documented disability and need an accommodation to access our services. Please note that eligibility for accommodations is determined on an individual basis, and is not based on a diagnosis or label of a disability.\n\n",
            "logprobs": null,
            "finish_reason": "length"
        }
    ],
    "usage": {
        "prompt_tokens": 8,
        "total_tokens": 148,
        "completion_tokens": 140
    }
}
```
