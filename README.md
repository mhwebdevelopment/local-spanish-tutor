# vocabdia
A Spanish learning tool, vocab tracker, &amp; chatbot interface supporting ollama! Including phrase/word list editing, support for CSV import/export, &amp; quiz functionality (multiple choice or flashcards)

-Note must be run locally with ollama running for the chat functionality!

[Live Demo](https://vocabdia.vercel.app)

Tested with Phi-4-mini-instruct-GGUF [Hugging Face Link](https://huggingface.co/unsloth/Phi-4-mini-instruct-GGUF?show_file_info=Phi-4-mini-instruct-Q4_K_M.gguf)

See [phi4-mini-vocabdia](/phi4-mini-vocabdia)

# Functional but next plans:

- Address quirks like the few times pig = i love you in early testing...
- Add base grammar & frequency list of most common translations into LoRa run
- Move from system prompt only to LoRa training run on Phi-4 with a good size example set for each mode (T, C, & E)
- After the above tests, try structured pruning to remove other languages / targeted layers from Phi-4 to optimize
