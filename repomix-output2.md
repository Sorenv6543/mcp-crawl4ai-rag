This file is a merged representation of the entire codebase, combined into a single document by Repomix.
The content has been processed where comments have been removed, empty lines have been removed, content has been formatted for parsing in markdown style.

# File Summary

## Purpose
This file contains a packed representation of the entire repository's contents.
It is designed to be easily consumable by AI systems for analysis, code review,
or other automated processes.

## File Format
The content is organized as follows:
1. This summary section
2. Repository information
3. Directory structure
4. Repository files (if enabled)
5. Multiple file entries, each consisting of:
  a. A header with the file path (## File: path/to/file)
  b. The full contents of the file in a code block

## Usage Guidelines
- This file should be treated as read-only. Any changes should be made to the
  original repository files, not this packed version.
- When processing this file, use the file path to distinguish
  between different files in the repository.
- Be aware that this file may contain sensitive information. Handle it with
  the same level of security as you would the original repository.

## Notes
- Some files may have been excluded based on .gitignore rules and Repomix's configuration
- Binary files are not included in this packed representation. Please refer to the Repository Structure section for a complete list of file paths, including binary files
- Files matching patterns in .gitignore are excluded
- Files matching default ignore patterns are excluded
- Code comments have been removed from supported file types
- Empty lines have been removed from all files
- Content has been formatted for parsing in markdown style
- Files are sorted by Git change count (files with more changes are at the bottom)

# Directory Structure
```
.dockerignore
.gitattributes
.gitignore
.repomix/bundles.json
AICHATS/cursor_generate_a_name_for_the_chat.md
crawled_pages.sql
Dockerfile
LICENSE
pyproject.toml
README.md
src/crawl4ai_mcp.py
src/utils.py
```

# Files

## File: .repomix/bundles.json
````json
{
  "bundles": {}
}
````

## File: AICHATS/cursor_generate_a_name_for_the_chat.md
````markdown
# Generate a name for the chat
_Exported on 5/29/2025 at 06:35:26 PDT from Cursor (0.50.7)_

---

**User**

perform_rag_query crawl4ai docs to learn how to smart_crawl :@https://vuejs.org/guide/introduction.html while ignoring any *.vuejs.org max depth 3

---

**Cursor**

I'll help you search through the crawl4ai documentation to understand how to use the smart crawl functionality while excluding vuejs.org domains.

Let me first check what's available in the RAG system.

I see we don't have any existing documentation about excluding domains. Let me try another query to understand the basic smart_crawl functionality.

I see that we don't have any existing documentation in the RAG system about the smart_crawl functionality. However, I can help you with what we know from the tool's description:

The `smart_crawl_url` function takes the following parameters:
- `url`: The URL to crawl (required)
- `max_depth`: Maximum recursion depth for regular URLs (default: 3)
- `max_concurrent`: Maximum number of concurrent browser sessions (default: 10)
- `chunk_size`: Maximum size of each content chunk in characters (default: 5000)

For your specific request, we can use:

I notice that while we can set the max_depth, the tool doesn't directly support excluding domains. For your use case, there are a few options:

1. You could use the single page crawler instead to just get the specific page:

---

**User**

stop fetching

---

**Cursor**

Understood—no further crawling or fetching will be performed. If you need help with anything else, such as working with the smart_crawl function, filtering results, or handling Vue documentation, just let me know!

---

**User**

sequential-thinking: can you make aliases for mcp tool name to make them easier to call?

---

**Cursor**

While I understand your request to make the `mcp_` tool names easier to call by creating aliases, I'm unable to directly create aliases for the tool names themselves. The names are fixed and defined by the system I operate within.

However, please don't worry about using the full tool names in your requests. You can simply tell me what you want to achieve (like "search the web" or "read a file"), and I will automatically use the correct tool with its full name based on your instructions. I'll handle the details of calling `mcp_brave_search_brave_web_search` or `default_api.read_file` for you.

---

**User**

bravewebsearch look on curor documentation, cursor forums , reddit, for ways to improve mcp tools in cursor

---

**Cursor**

I've searched on Cursor forums, Reddit, and general web results for ways to improve MCP tools in Cursor. Here are some relevant findings:

*   **Community Discussions:** There are several discussions on Reddit and the Cursor community forum about using and setting up MCP servers and tools. Users share their experiences, challenges, and tips.
    *   r/cursor on Reddit: Documentation to MCP: [https://www.reddit.com/r/cursor/comments/1iur8rz/documentation_to_mcp/](https://www.reddit.com/r/cursor/comments/1iur8rz/documentation_to_mcp/)
    *   How to use MCP Server? - How To - Cursor - Community Forum: [https://forum.cursor.com/t/how-to-use-mcp-server/50064](https://forum.cursor.com/t/how-to-use-mcp-server/50064)
    *   r/cursor on Reddit: What’s are the best MCP servers you guys are using?: [https://www.reddit.com/r/cursor/comments/1j1ovbr/whats_are_the_best_mcp_servers_you_guys_are_using/](https://www.reddit.com/r/cursor/comments/1j1ovbr/whats_are_the_best_mcp_servers_you_guys_are_using/)
    *   Any favorite MCP tools? : Cursor Discussion Forums | Product Hunt: [https://www.producthunt.com/p/cursor/any-favorite-mcp-tools](https://www.producthunt.com/p/cursor/any-favorite-mcp-tools)

*   **Tutorials and Guides:** Some users have created tutorials and guides to help others set up and use MCP tools.
    *   r/cursor on Reddit: Tutorial - The Missing Cursor MCP Manual: [https://www.reddit.com/r/cursor/comments/1ii0ixu/tutorial_the_missing_cursor_mcp_manual/](https://www.reddit.com/r/cursor/comments/1ii0ixu/tutorial_the_missing_cursor_mcp_manual/)

*   **Lists of MCP Servers:** There are resources listing various MCP servers that can be added to Cursor for increased productivity.
    *   15 Best MCP Servers You Can Add to Cursor For 10x Productivity: [https://www.firecrawl.dev/blog/best-mcp-servers-for-cursor](https://www.firecrawl.dev/blog/best-mcp-servers-for-cursor)
    *   MCP Servers for Cursor: [https://cursor.directory/mcp](https://cursor.directory/mcp)

*   **Troubleshooting:** Some discussions address common issues users face when setting up and using MCP tools, such as "tools not found" problems.
    *   r/cursor on Reddit: Anybody got good experience to avoid tools not found problem for setup MCP in cursorm: [https://www.reddit.com/r/cursor/comments/1isk7l4/anybody_got_good_experience_to_avoid_tools_not/](https://www.reddit.com/r/cursor/comments/1isk7l4/anybody_got_good_experience_to_avoid_tools_not/)
    *   r/ChatGPTCoding on Reddit: Cursor has MCP features that don't work for me any solutions?: [https://www.reddit.com/r/ChatGPTCoding/comments/1if8lbr/cursor_has_mcp_features_that_don't_work_for_me_any/](https://www.reddit.com/r/ChatGPTCoding/comments/1if8lbr/cursor_has_mcp_features_that_don't_work-for-me-any/)

While these results don't directly provide a mechanism for aliasing tool names within the system, they offer valuable insights into the community's experience with MCP tools in Cursor, including setup, usage, and available resources. This information could be helpful in understanding how other users are leveraging these tools and potentially finding workarounds or alternative approaches to improve the interaction with them.

Is there anything specific you'd like to explore further based on these results? Perhaps you're interested in learning more about setting up an MCP server or exploring some of the mentioned MCP tools?

---

**User**

is there an mcp client for cursor?

---

**Cursor**



Yes, Cursor itself acts as the client for MCP (Model Context Protocol). You install or connect MCP servers to Cursor, and Cursor then uses those servers to access the available tools.

The search results from our previous turn support this, mentioning things like "How to use MCP Server" and "add to Cursor" when discussing MCP functionality.

Would you like me to find more information about how to set up or find MCP servers that you can connect to your Cursor client?

---

**User**

no, i want alternatives to having to calll each one out by name each time

---

**Cursor**



Okay, I understand. You want to avoid having to type out or remember the exact names of the MCP tools every time you want to use them.

While I cannot create aliases *within the system* for the tool names themselves, my primary function is to allow you to interact with these tools using **natural language**.

You don't need to say "use `default_api.mcp_brave_search_brave_web_search`". You can simply tell me what you want to do, and I will select and call the correct tool for you.

For example, instead of asking if there is a tool to "bravewebsearch look on curor documentation...", you could simply say:

*   "Search the web for ways to improve MCP tools in Cursor on documentation, forums, and Reddit."
*   "Find information about improving Cursor's MCP tools online."

I will then interpret your request and use the appropriate tool (like `mcp_brave_search_brave_web_search`) with the necessary parameters.

So, the alternative to calling them out by name each time is to just describe the action you want me to perform using regular English, and I will handle the tool selection.

---

**User**

i would also like to use them together in certain orders

---

**Cursor**



Okay, I understand. You want to chain tool calls together to perform a sequence of actions.

Yes, I can absolutely do that. You can describe a multi-step process or a workflow that requires using different tools in a particular order, and I will execute the steps sequentially.

For example, you could ask me to:

1.  List the files in a directory.
2.  Then, based on the file list, read the content of a specific file.
3.  After reading the file, perform a web search based on its content.

For more complex sequences or tasks that require planning and intermediate steps, I can also use a structured thinking process to break down the goal, determine the necessary tools and their order, and execute them step by step, adapting the plan as needed.

Just tell me the sequence of actions you want to perform or the multi-step task you need help with, and I will do my best to execute it using the available tools in the requested order.

---

**User**

use sequential thinking while searching github for ways to connect mcp's in cursor also use the think tool

---

**Cursor**

Okay, I'm continuing the sequential thinking process to find information on connecting MCPs in Cursor by examining the search results from GitHub.

I have already read the README for the Neo4j MCP server. Now I am reading the content of the second identified file, TASK.md from the `devonartis/supabase-mcp` repository.

Based on the GitHub search and the files I read, the way to connect MCP servers in Cursor is by configuring Cursor to run a command that starts the desired MCP server. This connection typically utilizes the standard input/output (stdio) stream for communication between Cursor (the client) and the MCP server.

Essentially, you need to tell Cursor *how* to launch the MCP server executable or script, and Cursor will handle the communication over stdio.

The documents I reviewed, such as the README for the Neo4j MCP server and the setup guide for the n8n MCP node, describe how to run those specific servers, which implies that Cursor is configured with these commands to establish the connection.

So, to connect an MCP in Cursor, you would generally:
1.  Obtain or build the MCP server you want to connect.
2.  Identify the command needed to run that server (e.g., `./run-mcp-server.sh`, `bun run index.ts`, `npx @modelcontextprotocol/server-brave-search`).
3.  Configure this command within Cursor's settings or interface for MCP connections. The exact steps for configuring Cursor would be within the Cursor application itself, but the underlying mechanism involves Cursor executing the server's startup command.

This process allows Cursor to act as the client and interact with the tools exposed by the running MCP server.

---

**User**

sequential thinking, how could i create a tool that creates a local server ui in react that would alow the user to have a viual representation of thier mcp's and thier arguments so that the user could configure them visually in cursor?

---

**Cursor**



Okay, let's break down the process of creating a local React-based UI tool within Cursor using sequential thinking. This tool would visualize your MCPs and their arguments for easier configuration.



Okay, I understand you want to explore the feasibility and design of a local tool with a React UI within Cursor to provide a visual way to manage and configure your MCP servers and their arguments. This is a more complex undertaking than just calling existing tools, as it involves building a new application that integrates with Cursor.

Here's a sequential thinking process outlining how such a tool could be conceptualized and built:



That's an interesting and potentially very useful idea! Creating a local tool with a React UI within Cursor to visually manage and configure your MCPs is definitely achievable, although it involves building a custom application that integrates with the Cursor environment.

Here's a breakdown of the approach, using a sequential thinking process:

1.  **Understanding the Core Problem:** The current interaction with MCP tools is primarily command-line based. The user wants a visual interface within Cursor to see their connected MCPs, understand their capabilities (tools and arguments), and configure/execute them more easily.

2.  **Identifying the Components:** To achieve this, you would need to build a multi-part system:
    *   **A Local Backend Server:** This server will run on your machine and act as an intermediary between Cursor and your other MCP servers. It will need to be able to:
        *   Receive requests from Cursor (likely via stdio, as is common for MCPs).
        *   Manage a list of the user's configured MCP servers (storing their startup commands).
        *   Launch these configured MCP servers as child processes.
        *   Communicate with these child MCP processes using their MCP interface (stdio) to discover their tools and execute them.
        *   Host a web server to serve the React frontend.
        *   Provide an API that the React frontend can use to:
            *   Get the list of configured MCPs and their tools/arguments.
            *   Trigger the execution of tools on the child MCP processes.
            *   Add, edit, and remove configured MCP servers.
    *   **A React Frontend Application:** This will be the visual interface. It will run in a web view hosted by your local backend server and displayed within Cursor. It will:
        *   Fetch the list of MCPs and their tools from the backend API.
        *   Render a user-friendly display of MCPs and their available tools, including their arguments.
        *   Provide input fields or forms for the user to specify arguments for tool execution.
        *   Send requests to the backend API to execute tools with the provided arguments.
        *   Offer an interface to manage the list of MCP servers (add new ones by providing their startup command, edit existing ones, remove them).
    *   **An MCP Interface for the Local Tool:** Your local backend server will itself need to expose an MCP interface so that Cursor can recognize and launch it. This might include a simple tool like `open_ui` that, when called by Cursor, instructs the backend to open the web view hosting the React app.

3.  **Workflow:** The user's interaction would look something like this:
    *   The user would install your local tool.
    *   They would configure Cursor to launch your tool's backend server as an MCP (providing the command to start your backend).
    *   Within Cursor, they would trigger your tool's `open_ui` command (perhaps through the command palette).
    *   This would open the React UI within Cursor.
    *   In the React UI, the user would add the startup commands for their other MCP servers (e.g., the Neo4j MCP server, a Brave search MCP server, etc.).
    *   The React UI would then display these configured MCPs and their tools.
    *   The user could visually select an MCP, choose a tool, fill in the arguments using the generated forms, and click a button to execute the tool via your backend.

4.  **Technical Considerations:**
    *   **Inter-Process Communication (IPC):** Your backend will need to handle communication with child processes via stdio, sending and receiving JSON-RPC messages according to the MCP specification.
    *   **Dynamic UI Generation:** The React frontend will need to dynamically generate forms or input fields based on the arguments required by each tool, as provided by the MCP server's tool definitions.
    *   **State Management:** You'll need to manage the state of the configured MCPs and their tools in the backend, and potentially in the frontend as well for responsiveness.
    *   **Error Handling:** Robust error handling is crucial for issues with launching child processes, communication errors, and errors during tool execution.
    *   **Packaging and Distribution:** Consider how you would package and distribute this tool so other Cursor users can easily install and use it.

In summary, creating this tool is a significant development project involving backend and frontend development and a deep understanding of the MCP protocol and how Cursor interacts with it. However, it addresses a valid need for a more visual and user-friendly way to manage and use MCP tools within Cursor.

---

**User**

look @https://github.com/LSTM-Kirigaya/openmcp-client 

---

**Cursor**



Okay, I have reviewed the information available for the GitHub repository `https://github.com/LSTM-Kirigaya/openmcp-client`.

This repository appears to be directly relevant to your previous query about creating a local UI for managing MCPs in Cursor. According to the description and file structure:

*   It's an **"Integrated MCP Server Debugger"** and **"A MCP Client for MCP/OpenMCP"**.
*   It is designed as a **plugin for VSCode, Trae, and Cursor**.
*   It includes a `renderer` directory which defines the **Frontend UI**, likely built with Vue (as Vue is listed among the languages used).
*   It has a `service` component that acts as a forwarding layer and communicates with MCP servers.
*   The project aims to integrate an Inspector and basic **MCP client functionalities** for development and testing.
*   A key feature mentioned is the support for **debugging multiple MCP servers simultaneously** and a project-level management panel.

This project, `openmcp-client`, seems to be an existing implementation of an MCP client *with a UI* specifically for environments like Cursor. This aligns closely with the concept you were exploring in our sequential thinking process – a local tool with a visual interface to interact with MCPs.

It suggests that instead of building such a tool from scratch, you might be able to utilize or learn from this existing `openmcp-client` project.

Does reviewing this project give you ideas or change how you'd like to proceed with your goal of visually managing MCPs in Cursor?

---

**User**

@https://github.com/LSTM-Kirigaya/openmcp-client it open source. i could make an copy of it in english asa starting point

---

**Cursor**



Yes, that's a great observation. The `openmcp-client` repository is indeed open source under the Apache-2.0 license, as indicated in the repository information.

Creating an English copy of the project as a starting point is a very practical approach. This would allow you to leverage the existing architecture and functionality while making it accessible and understandable for your development and potential future use.

I can certainly help you with this. We could start by discussing how you'd like to approach creating this copy. Would you like assistance with:

*   Cloning the repository?
*   Navigating the project structure?
*   Understanding specific parts of the code (even if in Chinese, the structure and some terms might be discernible)?
*   Setting up a development environment for the project?
*   Translating key documentation or code comments?

Just let me know how you'd like to begin.

---

**User**

im gonna put that on the backburner for now and focus on gatherring all off the tech documentation for anothre project into a vector database for assisting in developing a booking system

---

**Cursor**



Okay, I understand. We'll put the `openmcp-client` project on the backburner for now and shift focus to your new goal: gathering technical documentation for your booking system project and loading it into a vector database to assist your development.

This is a great use case for a vector database and RAG! I can definitely help you with this process using the available tools.

To get started, I need to know which technical documentation you'd like to gather. Please provide me with the sources, such as:

*   Specific URLs of documentation pages.
*   Paths to local files containing documentation within your workspace.

Once I have the sources, I can gather the content and add it to the vector database for your booking system project.
````

## File: .dockerignore
````
crawl4ai_mcp.egg-info
__pycache__
.venv
.env
````

## File: .gitattributes
````
# Auto detect text files and perform LF normalization
* text=auto
````

## File: .gitignore
````
.env
.venv
__pycache__
crawl4ai_mcp.egg-info
````

## File: crawled_pages.sql
````sql
create extension if not exists vector;
create table crawled_pages (
    id bigserial primary key,
    url varchar not null,
    chunk_number integer not null,
    content text not null,
    metadata jsonb not null default '{}'::jsonb,
    embedding vector(1536),
    created_at timestamp with time zone default timezone('utc'::text, now()) not null,
    unique(url, chunk_number)
);
create index on crawled_pages using ivfflat (embedding vector_cosine_ops);
create index idx_crawled_pages_metadata on crawled_pages using gin (metadata);
CREATE INDEX idx_crawled_pages_source ON crawled_pages ((metadata->>'source'));
create or replace function match_crawled_pages (
  query_embedding vector(1536),
  match_count int default 10,
  filter jsonb DEFAULT '{}'::jsonb
) returns table (
  id bigint,
  url varchar,
  chunk_number integer,
  content text,
  metadata jsonb,
  similarity float
)
language plpgsql
as $$
#variable_conflict use_column
begin
  return query
  select
    id,
    url,
    chunk_number,
    content,
    metadata,
    1 - (crawled_pages.embedding <=> query_embedding) as similarity
  from crawled_pages
  where metadata @> filter
  order by crawled_pages.embedding <=> query_embedding
  limit match_count;
end;
$$;
alter table crawled_pages enable row level security;
create policy "Allow public read access"
  on crawled_pages
  for select
  to public
  using (true);
````

## File: Dockerfile
````dockerfile
FROM python:3.12-slim

ARG PORT=8051

WORKDIR /app

# Install uv
RUN pip install uv

# Copy the MCP server files
COPY . .

# Install packages directly to the system (no virtual environment)
# Combining commands to reduce Docker layers
RUN uv pip install --system -e . && \
    crawl4ai-setup

EXPOSE ${PORT}

# Command to run the MCP server
CMD ["uv", "run", "src/crawl4ai_mcp.py"]
````

## File: LICENSE
````
MIT License

Copyright (c) 2025 Cole Medin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

## File: pyproject.toml
````toml
[project]
name = "crawl4ai-mcp"
version = "0.1.0"
description = "MCP server for integrating web crawling and RAG into AI agents and AI coding assistants"
readme = "README.md"
requires-python = ">=3.12"
dependencies = [
    "crawl4ai==0.6.2",
    "mcp==1.7.1",
    "supabase==2.15.1",
    "openai==1.71.0",
    "dotenv==0.9.9"
]
````

## File: src/crawl4ai_mcp.py
````python
from mcp.server.fastmcp import FastMCP, Context
from contextlib import asynccontextmanager
from collections.abc import AsyncIterator
from dataclasses import dataclass
from typing import List, Dict, Any, Optional
from urllib.parse import urlparse, urldefrag
from xml.etree import ElementTree
from dotenv import load_dotenv
from supabase import Client
from pathlib import Path
import requests
import asyncio
import json
import os
import re
from crawl4ai import AsyncWebCrawler, BrowserConfig, CrawlerRunConfig, CacheMode, MemoryAdaptiveDispatcher
from utils import get_supabase_client, add_documents_to_supabase, search_documents
project_root = Path(__file__).resolve().parent.parent
dotenv_path = project_root / '.env'
load_dotenv(dotenv_path, override=True)
@dataclass
class Crawl4AIContext:
    crawler: AsyncWebCrawler
    supabase_client: Client
@asynccontextmanager
async def crawl4ai_lifespan(server: FastMCP) -> AsyncIterator[Crawl4AIContext]:
    browser_config = BrowserConfig(
        headless=True,
        verbose=False
    )
    crawler = AsyncWebCrawler(config=browser_config)
    await crawler.__aenter__()
    supabase_client = get_supabase_client()
    try:
        yield Crawl4AIContext(
            crawler=crawler,
            supabase_client=supabase_client
        )
    finally:
        await crawler.__aexit__(None, None, None)
mcp = FastMCP(
    "mcp-crawl4ai-rag",
    description="MCP server for RAG and web crawling with Crawl4AI",
    lifespan=crawl4ai_lifespan,
    host=os.getenv("HOST", "0.0.0.0"),
    port=os.getenv("PORT", "8051")
)
def is_sitemap(url: str) -> bool:
    return url.endswith('sitemap.xml') or 'sitemap' in urlparse(url).path
def is_txt(url: str) -> bool:
    return url.endswith('.txt')
def parse_sitemap(sitemap_url: str) -> List[str]:
    resp = requests.get(sitemap_url)
    urls = []
    if resp.status_code == 200:
        try:
            tree = ElementTree.fromstring(resp.content)
            urls = [loc.text for loc in tree.findall('.//{*}loc')]
        except Exception as e:
            print(f"Error parsing sitemap XML: {e}")
    return urls
def smart_chunk_markdown(text: str, chunk_size: int = 5000) -> List[str]:
    chunks = []
    start = 0
    text_length = len(text)
    while start < text_length:
        end = start + chunk_size
        if end >= text_length:
            chunks.append(text[start:].strip())
            break
        chunk = text[start:end]
        code_block = chunk.rfind('```')
        if code_block != -1 and code_block > chunk_size * 0.3:
            end = start + code_block
        elif '\n\n' in chunk:
            last_break = chunk.rfind('\n\n')
            if last_break > chunk_size * 0.3:
                end = start + last_break
        # If no paragraph break, try to break at a sentence
        elif '. ' in chunk:
            # Find the last sentence break
            last_period = chunk.rfind('. ')
            if last_period > chunk_size * 0.3:  # Only break if we're past 30% of chunk_size
                end = start + last_period + 1
        chunk = text[start:end].strip()
        if chunk:
            chunks.append(chunk)
        start = end
    return chunks
def extract_section_info(chunk: str) -> Dict[str, Any]:
    headers = re.findall(r'^(#+)\s+(.+)$', chunk, re.MULTILINE)
    header_str = '; '.join([f'{h[0]} {h[1]}' for h in headers]) if headers else ''
    return {
        "headers": header_str,
        "char_count": len(chunk),
        "word_count": len(chunk.split())
    }
@mcp.tool()
async def crawl_single_page(ctx: Context, url: str) -> str:
    try:
        crawler = ctx.request_context.lifespan_context.crawler
        supabase_client = ctx.request_context.lifespan_context.supabase_client
        run_config = CrawlerRunConfig(cache_mode=CacheMode.BYPASS, stream=False)
        result = await crawler.arun(url=url, config=run_config)
        if result.success and result.markdown:
            chunks = smart_chunk_markdown(result.markdown)
            urls = []
            chunk_numbers = []
            contents = []
            metadatas = []
            for i, chunk in enumerate(chunks):
                urls.append(url)
                chunk_numbers.append(i)
                contents.append(chunk)
                meta = extract_section_info(chunk)
                meta["chunk_index"] = i
                meta["url"] = url
                meta["source"] = urlparse(url).netloc
                meta["crawl_time"] = str(asyncio.current_task().get_coro().__name__)
                metadatas.append(meta)
            url_to_full_document = {url: result.markdown}
            add_documents_to_supabase(supabase_client, urls, chunk_numbers, contents, metadatas, url_to_full_document)
            return json.dumps({
                "success": True,
                "url": url,
                "chunks_stored": len(chunks),
                "content_length": len(result.markdown),
                "links_count": {
                    "internal": len(result.links.get("internal", [])),
                    "external": len(result.links.get("external", []))
                }
            }, indent=2)
        else:
            return json.dumps({
                "success": False,
                "url": url,
                "error": result.error_message
            }, indent=2)
    except Exception as e:
        return json.dumps({
            "success": False,
            "url": url,
            "error": str(e)
        }, indent=2)
@mcp.tool()
async def smart_crawl_url(ctx: Context, url: str, max_depth: int = 3, max_concurrent: int = 10, chunk_size: int = 5000) -> str:
    try:
        crawler = ctx.request_context.lifespan_context.crawler
        supabase_client = ctx.request_context.lifespan_context.supabase_client
        crawl_results = []
        crawl_type = "webpage"
        if is_txt(url):
            crawl_results = await crawl_markdown_file(crawler, url)
            crawl_type = "text_file"
        elif is_sitemap(url):
            sitemap_urls = parse_sitemap(url)
            if not sitemap_urls:
                return json.dumps({
                    "success": False,
                    "url": url,
                    "error": "No URLs found in sitemap"
                }, indent=2)
            crawl_results = await crawl_batch(crawler, sitemap_urls, max_concurrent=max_concurrent)
            crawl_type = "sitemap"
        else:
            crawl_results = await crawl_recursive_internal_links(crawler, [url], max_depth=max_depth, max_concurrent=max_concurrent)
            crawl_type = "webpage"
        if not crawl_results:
            return json.dumps({
                "success": False,
                "url": url,
                "error": "No content found"
            }, indent=2)
        urls = []
        chunk_numbers = []
        contents = []
        metadatas = []
        chunk_count = 0
        for doc in crawl_results:
            source_url = doc['url']
            md = doc['markdown']
            chunks = smart_chunk_markdown(md, chunk_size=chunk_size)
            for i, chunk in enumerate(chunks):
                urls.append(source_url)
                chunk_numbers.append(i)
                contents.append(chunk)
                meta = extract_section_info(chunk)
                meta["chunk_index"] = i
                meta["url"] = source_url
                meta["source"] = urlparse(source_url).netloc
                meta["crawl_type"] = crawl_type
                meta["crawl_time"] = str(asyncio.current_task().get_coro().__name__)
                metadatas.append(meta)
                chunk_count += 1
        url_to_full_document = {}
        for doc in crawl_results:
            url_to_full_document[doc['url']] = doc['markdown']
        batch_size = 20
        add_documents_to_supabase(supabase_client, urls, chunk_numbers, contents, metadatas, url_to_full_document, batch_size=batch_size)
        return json.dumps({
            "success": True,
            "url": url,
            "crawl_type": crawl_type,
            "pages_crawled": len(crawl_results),
            "chunks_stored": chunk_count,
            "urls_crawled": [doc['url'] for doc in crawl_results][:5] + (["..."] if len(crawl_results) > 5 else [])
        }, indent=2)
    except Exception as e:
        return json.dumps({
            "success": False,
            "url": url,
            "error": str(e)
        }, indent=2)
async def crawl_markdown_file(crawler: AsyncWebCrawler, url: str) -> List[Dict[str, Any]]:
    crawl_config = CrawlerRunConfig()
    result = await crawler.arun(url=url, config=crawl_config)
    if result.success and result.markdown:
        return [{'url': url, 'markdown': result.markdown}]
    else:
        print(f"Failed to crawl {url}: {result.error_message}")
        return []
async def crawl_batch(crawler: AsyncWebCrawler, urls: List[str], max_concurrent: int = 10) -> List[Dict[str, Any]]:
    crawl_config = CrawlerRunConfig(cache_mode=CacheMode.BYPASS, stream=False)
    dispatcher = MemoryAdaptiveDispatcher(
        memory_threshold_percent=70.0,
        check_interval=1.0,
        max_session_permit=max_concurrent
    )
    results = await crawler.arun_many(urls=urls, config=crawl_config, dispatcher=dispatcher)
    return [{'url': r.url, 'markdown': r.markdown} for r in results if r.success and r.markdown]
async def crawl_recursive_internal_links(crawler: AsyncWebCrawler, start_urls: List[str], max_depth: int = 3, max_concurrent: int = 10) -> List[Dict[str, Any]]:
    run_config = CrawlerRunConfig(cache_mode=CacheMode.BYPASS, stream=False)
    dispatcher = MemoryAdaptiveDispatcher(
        memory_threshold_percent=70.0,
        check_interval=1.0,
        max_session_permit=max_concurrent
    )
    visited = set()
    def normalize_url(url):
        return urldefrag(url)[0]
    current_urls = set([normalize_url(u) for u in start_urls])
    results_all = []
    for depth in range(max_depth):
        urls_to_crawl = [normalize_url(url) for url in current_urls if normalize_url(url) not in visited]
        if not urls_to_crawl:
            break
        results = await crawler.arun_many(urls=urls_to_crawl, config=run_config, dispatcher=dispatcher)
        next_level_urls = set()
        for result in results:
            norm_url = normalize_url(result.url)
            visited.add(norm_url)
            if result.success and result.markdown:
                results_all.append({'url': result.url, 'markdown': result.markdown})
                for link in result.links.get("internal", []):
                    next_url = normalize_url(link["href"])
                    if next_url not in visited:
                        next_level_urls.add(next_url)
        current_urls = next_level_urls
    return results_all
@mcp.tool()
async def get_available_sources(ctx: Context) -> str:
    try:
        # Get the Supabase client from the context
        supabase_client = ctx.request_context.lifespan_context.supabase_client
        # Use a direct query with the Supabase client
        # This could be more efficient with a direct Postgres query but
        # I don't want to require users to set a DB_URL environment variable as well
        result = supabase_client.from_('crawled_pages')\
            .select('metadata')\
            .not_.is_('metadata->>source', 'null')\
            .execute()
        unique_sources = set()
        if result.data:
            for item in result.data:
                source = item.get('metadata', {}).get('source')
                if source:
                    unique_sources.add(source)
        sources = sorted(list(unique_sources))
        return json.dumps({
            "success": True,
            "sources": sources,
            "count": len(sources)
        }, indent=2)
    except Exception as e:
        return json.dumps({
            "success": False,
            "error": str(e)
        }, indent=2)
@mcp.tool()
async def perform_rag_query(ctx: Context, query: str, source: str = None, match_count: int = 5) -> str:
    try:
        supabase_client = ctx.request_context.lifespan_context.supabase_client
        filter_metadata = None
        if source and source.strip():
            filter_metadata = {"source": source}
        results = search_documents(
            client=supabase_client,
            query=query,
            match_count=match_count,
            filter_metadata=filter_metadata
        )
        formatted_results = []
        for result in results:
            formatted_results.append({
                "url": result.get("url"),
                "content": result.get("content"),
                "metadata": result.get("metadata"),
                "similarity": result.get("similarity")
            })
        return json.dumps({
            "success": True,
            "query": query,
            "source_filter": source,
            "results": formatted_results,
            "count": len(formatted_results)
        }, indent=2)
    except Exception as e:
        return json.dumps({
            "success": False,
            "query": query,
            "error": str(e)
        }, indent=2)
async def main():
    transport = os.getenv("TRANSPORT", "sse")
    if transport == 'sse':
        await mcp.run_sse_async()
    else:
        await mcp.run_stdio_async()
if __name__ == "__main__":
    asyncio.run(main())
````

## File: src/utils.py
````python
import os
import concurrent.futures
from typing import List, Dict, Any, Optional, Tuple
import json
from supabase import create_client, Client
from urllib.parse import urlparse
import openai
openai.api_key = os.getenv("OPENAI_API_KEY")
def get_supabase_client() -> Client:
    url = os.getenv("SUPABASE_URL")
    key = os.getenv("SUPABASE_SERVICE_KEY")
    if not url or not key:
        raise ValueError("SUPABASE_URL and SUPABASE_SERVICE_KEY must be set in environment variables")
    return create_client(url, key)
def create_embeddings_batch(texts: List[str]) -> List[List[float]]:
    if not texts:
        return []
    try:
        response = openai.embeddings.create(
            model="text-embedding-3-small",
            input=texts
        )
        return [item.embedding for item in response.data]
    except Exception as e:
        print(f"Error creating batch embeddings: {e}")
        return [[0.0] * 1536 for _ in range(len(texts))]
def create_embedding(text: str) -> List[float]:
    try:
        embeddings = create_embeddings_batch([text])
        return embeddings[0] if embeddings else [0.0] * 1536
    except Exception as e:
        print(f"Error creating embedding: {e}")
        # Return empty embedding if there's an error
        return [0.0] * 1536
def generate_contextual_embedding(full_document: str, chunk: str) -> Tuple[str, bool]:
    model_choice = os.getenv("MODEL_CHOICE")
    try:
        prompt = f"""<document>
{full_document[:25000]}
</document>
Here is the chunk we want to situate within the whole document
<chunk>
{chunk}
</chunk>
Please give a short succinct context to situate this chunk within the overall document for the purposes of improving search retrieval of the chunk. Answer only with the succinct context and nothing else."""
        response = openai.chat.completions.create(
            model=model_choice,
            messages=[
                {"role": "system", "content": "You are a helpful assistant that provides concise contextual information."},
                {"role": "user", "content": prompt}
            ],
            temperature=0.3,
            max_tokens=200
        )
        context = response.choices[0].message.content.strip()
        contextual_text = f"{context}\n---\n{chunk}"
        return contextual_text, True
    except Exception as e:
        print(f"Error generating contextual embedding: {e}. Using original chunk instead.")
        return chunk, False
def process_chunk_with_context(args):
    url, content, full_document = args
    return generate_contextual_embedding(full_document, content)
def add_documents_to_supabase(
    client: Client,
    urls: List[str],
    chunk_numbers: List[int],
    contents: List[str],
    metadatas: List[Dict[str, Any]],
    url_to_full_document: Dict[str, str],
    batch_size: int = 20
) -> None:
    unique_urls = list(set(urls))
    try:
        if unique_urls:
            client.table("crawled_pages").delete().in_("url", unique_urls).execute()
    except Exception as e:
        print(f"Batch delete failed: {e}. Trying one-by-one deletion as fallback.")
        for url in unique_urls:
            try:
                client.table("crawled_pages").delete().eq("url", url).execute()
            except Exception as inner_e:
                print(f"Error deleting record for URL {url}: {inner_e}")
    model_choice = os.getenv("MODEL_CHOICE")
    use_contextual_embeddings = bool(model_choice)
    for i in range(0, len(contents), batch_size):
        batch_end = min(i + batch_size, len(contents))
        batch_urls = urls[i:batch_end]
        batch_chunk_numbers = chunk_numbers[i:batch_end]
        batch_contents = contents[i:batch_end]
        batch_metadatas = metadatas[i:batch_end]
        if use_contextual_embeddings:
            process_args = []
            for j, content in enumerate(batch_contents):
                url = batch_urls[j]
                full_document = url_to_full_document.get(url, "")
                process_args.append((url, content, full_document))
            contextual_contents = []
            with concurrent.futures.ThreadPoolExecutor(max_workers=10) as executor:
                future_to_idx = {executor.submit(process_chunk_with_context, arg): idx
                                for idx, arg in enumerate(process_args)}
                for future in concurrent.futures.as_completed(future_to_idx):
                    idx = future_to_idx[future]
                    try:
                        result, success = future.result()
                        contextual_contents.append(result)
                        if success:
                            batch_metadatas[idx]["contextual_embedding"] = True
                    except Exception as e:
                        print(f"Error processing chunk {idx}: {e}")
                        contextual_contents.append(batch_contents[idx])
            if len(contextual_contents) != len(batch_contents):
                print(f"Warning: Expected {len(batch_contents)} results but got {len(contextual_contents)}")
                contextual_contents = batch_contents
        else:
            contextual_contents = batch_contents
        batch_embeddings = create_embeddings_batch(contextual_contents)
        batch_data = []
        for j in range(len(contextual_contents)):
            chunk_size = len(contextual_contents[j])
            data = {
                "url": batch_urls[j],
                "chunk_number": batch_chunk_numbers[j],
                "content": contextual_contents[j],
                "metadata": {
                    "chunk_size": chunk_size,
                    **batch_metadatas[j]
                },
                "embedding": batch_embeddings[j]
            }
            batch_data.append(data)
        try:
            client.table("crawled_pages").insert(batch_data).execute()
        except Exception as e:
            print(f"Error inserting batch into Supabase: {e}")
def search_documents(
    client: Client,
    query: str,
    match_count: int = 10,
    filter_metadata: Optional[Dict[str, Any]] = None
) -> List[Dict[str, Any]]:
    query_embedding = create_embedding(query)
    try:
        params = {
            'query_embedding': query_embedding,
            'match_count': match_count
        }
        if filter_metadata:
            params['filter'] = filter_metadata  # Pass the dictionary directly, not JSON-encoded
        result = client.rpc('match_crawled_pages', params).execute()
        return result.data
    except Exception as e:
        print(f"Error searching documents: {e}")
        return []
````

## File: README.md
````markdown
<h1 align="center">Crawl4AI RAG MCP Server</h1>

<p align="center">
  <em>Web Crawling and RAG Capabilities for AI Agents and AI Coding Assistants</em>
</p>

A powerful implementation of the [Model Context Protocol (MCP)](https://modelcontextprotocol.io) integrated with [Crawl4AI](https://crawl4ai.com) and [Supabase](https://supabase.com/) for providing AI agents and AI coding assistants with advanced web crawling and RAG capabilities.

With this MCP server, you can <b>scrape anything</b> and then <b>use that knowledge anywhere</b> for RAG.

The primary goal is to bring this MCP server into [Archon](https://github.com/coleam00/Archon) as I evolve it to be more of a knowledge engine for AI coding assistants to build AI agents. This first version of the Crawl4AI/RAG MCP server will be improved upon greatly soon, especially making it more configurable so you can use different embedding models and run everything locally with Ollama.

## Overview

This MCP server provides tools that enable AI agents to crawl websites, store content in a vector database (Supabase), and perform RAG over the crawled content. It follows the best practices for building MCP servers based on the [Mem0 MCP server template](https://github.com/coleam00/mcp-mem0/) I provided on my channel previously.

## Vision

The Crawl4AI RAG MCP server is just the beginning. Here's where we're headed:

1. **Integration with Archon**: Building this system directly into [Archon](https://github.com/coleam00/Archon) to create a comprehensive knowledge engine for AI coding assistants to build better AI agents.

2. **Multiple Embedding Models**: Expanding beyond OpenAI to support a variety of embedding models, including the ability to run everything locally with Ollama for complete control and privacy.

3. **Advanced RAG Strategies**: Implementing sophisticated retrieval techniques like contextual retrieval, late chunking, and others to move beyond basic "naive lookups" and significantly enhance the power and precision of the RAG system, especially as it integrates with Archon.

4. **Enhanced Chunking Strategy**: Implementing a Context 7-inspired chunking approach that focuses on examples and creates distinct, semantically meaningful sections for each chunk, improving retrieval precision.

5. **Performance Optimization**: Increasing crawling and indexing speed to make it more realistic to "quickly" index new documentation to then leverage it within the same prompt in an AI coding assistant.

## Features

- **Smart URL Detection**: Automatically detects and handles different URL types (regular webpages, sitemaps, text files)
- **Recursive Crawling**: Follows internal links to discover content
- **Parallel Processing**: Efficiently crawls multiple pages simultaneously
- **Content Chunking**: Intelligently splits content by headers and size for better processing
- **Vector Search**: Performs RAG over crawled content, optionally filtering by data source for precision
- **Source Retrieval**: Retrieve sources available for filtering to guide the RAG process

## Tools

The server provides four essential web crawling and search tools:

1. **`crawl_single_page`**: Quickly crawl a single web page and store its content in the vector database
2. **`smart_crawl_url`**: Intelligently crawl a full website based on the type of URL provided (sitemap, llms-full.txt, or a regular webpage that needs to be crawled recursively)
3. **`get_available_sources`**: Get a list of all available sources (domains) in the database
4. **`perform_rag_query`**: Search for relevant content using semantic search with optional source filtering

## Prerequisites

- [Docker/Docker Desktop](https://www.docker.com/products/docker-desktop/) if running the MCP server as a container (recommended)
- [Python 3.12+](https://www.python.org/downloads/) if running the MCP server directly through uv
- [Supabase](https://supabase.com/) (database for RAG)
- [OpenAI API key](https://platform.openai.com/api-keys) (for generating embeddings)

## Installation

### Using Docker (Recommended)

1. Clone this repository:
   ```bash
   git clone https://github.com/coleam00/mcp-crawl4ai-rag.git
   cd mcp-crawl4ai-rag
   ```

2. Build the Docker image:
   ```bash
   docker build -t mcp/crawl4ai-rag --build-arg PORT=8051 .
   ```

3. Create a `.env` file based on the configuration section below

### Using uv directly (no Docker)

1. Clone this repository:
   ```bash
   git clone https://github.com/coleam00/mcp-crawl4ai-rag.git
   cd mcp-crawl4ai-rag
   ```

2. Install uv if you don't have it:
   ```bash
   pip install uv
   ```

3. Create and activate a virtual environment:
   ```bash
   uv venv
   .venv\Scripts\activate
   # on Mac/Linux: source .venv/bin/activate
   ```

4. Install dependencies:
   ```bash
   uv pip install -e .
   crawl4ai-setup
   ```

5. Create a `.env` file based on the configuration section below

## Database Setup

Before running the server, you need to set up the database with the pgvector extension:

1. Go to the SQL Editor in your Supabase dashboard (create a new project first if necessary)

2. Create a new query and paste the contents of `crawled_pages.sql`

3. Run the query to create the necessary tables and functions

## Configuration

Create a `.env` file in the project root with the following variables:

```
# MCP Server Configuration
HOST=0.0.0.0
PORT=8051
TRANSPORT=sse

# OpenAI API Configuration
OPENAI_API_KEY=your_openai_api_key

# Supabase Configuration
SUPABASE_URL=your_supabase_project_url
SUPABASE_SERVICE_KEY=your_supabase_service_key
```

## Running the Server

### Using Docker

```bash
docker run --env-file .env -p 8051:8051 mcp/crawl4ai-rag
```

### Using Python

```bash
uv run src/crawl4ai_mcp.py
```

The server will start and listen on the configured host and port.

## Integration with MCP Clients

### SSE Configuration

Once you have the server running with SSE transport, you can connect to it using this configuration:

```json
{
  "mcpServers": {
    "crawl4ai-rag": {
      "transport": "sse",
      "url": "http://localhost:8051/sse"
    }
  }
}
```

> **Note for Windsurf users**: Use `serverUrl` instead of `url` in your configuration:
> ```json
> {
>   "mcpServers": {
>     "crawl4ai-rag": {
>       "transport": "sse",
>       "serverUrl": "http://localhost:8051/sse"
>     }
>   }
> }
> ```
>
> **Note for Docker users**: Use `host.docker.internal` instead of `localhost` if your client is running in a different container. This will apply if you are using this MCP server within n8n!

### Stdio Configuration

Add this server to your MCP configuration for Claude Desktop, Windsurf, or any other MCP client:

```json
{
  "mcpServers": {
    "crawl4ai-rag": {
      "command": "python",
      "args": ["path/to/crawl4ai-mcp/src/crawl4ai_mcp.py"],
      "env": {
        "TRANSPORT": "stdio",
        "OPENAI_API_KEY": "your_openai_api_key",
        "SUPABASE_URL": "your_supabase_url",
        "SUPABASE_SERVICE_KEY": "your_supabase_service_key"
      }
    }
  }
}
```

### Docker with Stdio Configuration

```json
{
  "mcpServers": {
    "crawl4ai-rag": {
      "command": "docker",
      "args": ["run", "--rm", "-i", 
               "-e", "TRANSPORT", 
               "-e", "OPENAI_API_KEY", 
               "-e", "SUPABASE_URL", 
               "-e", "SUPABASE_SERVICE_KEY", 
               "mcp/crawl4ai"],
      "env": {
        "TRANSPORT": "stdio",
        "OPENAI_API_KEY": "your_openai_api_key",
        "SUPABASE_URL": "your_supabase_url",
        "SUPABASE_SERVICE_KEY": "your_supabase_service_key"
      }
    }
  }
}
```

## Building Your Own Server

This implementation provides a foundation for building more complex MCP servers with web crawling capabilities. To build your own:

1. Add your own tools by creating methods with the `@mcp.tool()` decorator
2. Create your own lifespan function to add your own dependencies
3. Modify the `utils.py` file for any helper functions you need
4. Extend the crawling capabilities by adding more specialized crawlers
````
