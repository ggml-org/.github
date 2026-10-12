### Overview

The `ggml-org` organization on Github develops and supports the [ggml](https://github.com/ggml-org/ggml) machine learning library and related projects.

- https://huggingface.co/ggml-org - `ggml-org` at Hugging Face
- https://llama.app - `llama.cpp`'s official website

```mermaid
graph TD;
ggml --> whisper.cpp
ggml --> llama.cpp
llama.cpp --> coding
llama.cpp --> providers

subgraph coding[Coding]
    llama.vim
    llama.vscode
    llama.qtcreator
end

subgraph providers[Providers]
    llama
    Llama-macOS
    Llama-Windows
end

ggml[<a href="https://github.com/ggml-org/ggml"                       style="text-decoration:none;">ggml</a>            <br><span style="font-size:10px;">Machine learning library</span>];
whisper.cpp[<a href="https://github.com/ggml-org/whisper.cpp"         style="text-decoration:none;">whisper.cpp</a>     <br><span style="font-size:10px;">speech-to-text</span>];
llama.cpp[<a href="https://github.com/ggml-org/llama.cpp"             style="text-decoration:none;">llama.cpp</a>       <br><span style="font-size:10px;">LLM inference</span>];
llama.vim[<a href="https://github.com/ggml-org/llama.vim"             style="text-decoration:none;">llama.vim</a>       <br><span style="font-size:10px;">Vim/Neovim plugin</span>];
llama.vscode[<a href="https://github.com/ggml-org/llama.vscode"       style="text-decoration:none;">llama.vscode</a>    <br><span style="font-size:10px;">VSCode plugin</span>];
llama.qtcreator[<a href="https://github.com/ggml-org/llama.qtcreator" style="text-decoration:none;">llama.qtcreator</a> <br><span style="font-size:10px;">Qt Creator plugin</span>];
llama[<a href="https://llama.app"                                     style="text-decoration:none;">llama</a>           <br><span style="font-size:10px;">CLI app</span>];
Llama-macOS[<a href="https://github.com/ggml-org/Llama-macOS"         style="text-decoration:none;">Llama-macOS</a>     <br><span style="font-size:10px;">macOS app</span>];
Llama-Windows[<a href="https://github.com/ggml-org/Llama-Windows"     style="text-decoration:none;">Llama-Windows</a>   <br><span style="font-size:10px;">Windows app</span>];
```
